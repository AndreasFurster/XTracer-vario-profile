# XTracer Vario Profile

To edit:
- https://www.windeckfalken.de/special/xctracer/handson/main.html
- _Edit Config File_ and paste config below

To use:
- Replace tones in config file

```ini
varioTone=Custom

# Quiet between -2 m/s and -1 m/s (normal glide)
SinkToneOnThreshold=-2
SinkToneOffThreshold=-2
ClimbToneOnThreshold=-1
ClimbToneOffThreshold=-1

# Sink tone below -2 m/s
tone=-7.00,200,200,100 
tone=-1.00,400,200,100

# Sniffer between -1 m/s and 0 m/s (something is happening)
tone=-1.00,325,250,8
tone=0.00,375,175,8

# Normal vario higher than 0 m/s
tone=0.00,600,500,70
tone=10.0,1500,170,70
```
