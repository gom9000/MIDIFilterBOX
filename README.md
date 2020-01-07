# MIDIFilterBOX
This is an open-source, home didactic project, for a *cheap magic box* able to filter MIDI message groups on a selected MIDI channel.
The MIDI messages that is possible to filter are grouped by:
- CC Channel-Volume message (0x7)
- All other CC messages (no Channel-Volume)
- Note-On and Note-Off messages
MIDI message groups can be filtered individually or simultaneously.

![midifilterbox-mercury.jpg](images/midifilterbox-mercury.jpg)


## Features
- 5-12V DC power plug for external power supply
- MIDI-in and MIDI-out connectors
- MIDI in/out leds activity
- 4-bit switch-array to configure the midi channel, bcd coded: *0000 -> 0=all channels*, *0001* -> channel 1, ..., *1111 -> channel 15*
- 3-bit switch-array to configure the groups of MIDI messages to filter (Channel-Volume, CC, Note On/Off)
- 3-bit led-array to show the actual filter status


## Changes
See file [CHANGES](CHANGES.md) for the project resources change logs


## Future Plans
See file [TODO](TODO.md) for the project future plans


## About
Author : Alessandro Fraschetti (mail: [gos95@gommagomma.net](mailto:gos95@gommagomma.net))


## License
This project is licensed under the [Creative Commons BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/) License