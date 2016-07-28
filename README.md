# Streaming Hackerspace

This h/w software rig will allow you to stream audio from a hacker space (area scalable) and allow input from non-local hackers (internauts!).  

## H/W

### H/W List

###### Required
* [CM-1000](http://www.tvps.com/Products/SoundTech-CM-1000-35-mm-Omni-directional-Conference-Microphone__VE-CM-1000.aspx?gclid=Cj0KEQjw2ua8BRDeusOkl5qth4QBEiQA8BpQcEzraEod0I0oIfpKnNXbVrMCCfnl6lJWGDmkY90C65QaAl_l8P8HAQ) - for recording audio
* A speaker
* USB Audio Card - for getting audio into and out of the pi
* RPi - For recieving audio


###### Optionals (for flare)
* LED - for lighting up when outsiders speak

### H/W Layout

```
mic --> audio in on USB soundcard -> shoutcast -> RPi
speaker <-- audio out on USB soundcard <- mumble server <- RPi
```

## Software Setup

* Shoutcast (streams the CM-1000 mic to the network)
* Mumble Server (allows outsiders to speak to the hackerspace)
* Desktop Streaming software or listener...
* Web application for listening and possibly streaming via a web browser


