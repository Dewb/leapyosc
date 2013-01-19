## Leap Python OSC Client

### Converting Leap data into OSC messages with pyOSC.

> This code is in early alpha and will definitely break a bunch still.

Tested on Mac OS X 10.8 Lion

### Pre-requisites:
- The Leap_SDK folder
- pyOSC

### Important files

+ LeapProject
|--+ Leap_SDK
|--+ leapyosc           # This repository folder
   |--+ bootstrap.sh    # Setup a virtualenv in folder `ve`; install pyOSC into it
   |--+ client.sh       # For running the OSC client


### Usage

The default hostname is `localhost` the default port is `8000`.
<pre>
	./client.sh [hostname] [port]
</pre>