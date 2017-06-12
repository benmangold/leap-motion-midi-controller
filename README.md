#LEAP Midi Controller

Turning the LEAP Motion into a MIDI controller

##Functionality

The LEAP's raw output is processed and scaled for reliability within the Pure Data patch 'pd-leap-midi-controller.pd'.

MIDI output is sent from Pd application, which allows routing to a Digital Audio Workstation (DAW) (Ex. Ableton Live, Pro Tools) or external hardware via a MIDI output.

Maintained by Ben Mangold

Underlying 'leapmotion' Pd Object Developed by Chikashi Miyama: http://puredatajapan.info/?page_id=1514

##Installation 

1) Install PureData (Pd) and LEAP Motion software

2) Plug in LEAP Motion

##Configuring Pd MIDI Output and Running the Patch

2) Open Pd Patch, File>Open 'pd-leap-motion-midi-controller.pd' 

3) Configure Pd MIDI Output, Pd>Preferences>MIDI Settings..

4) Configure DAW to recieve MIDI cc

5) Begin MIDI Performance

##Configuring your DAW to recieve MIDI

TODO