# LEAP Midi Controller

Turning the LEAP Motion into a MIDI controller using Puredata(Pd)

Pd is an open source signal processing software, included in this repo for OSX

Windows requires a Pd Installation, MIDI routing which I have not tested

PureData recieves incoming LEAP data streams, and parses select streams to MIDI, which is send to the destination of your choice.  Ex. Ableton Live, Pro Tools

Visible Here, DJing with Ableton Live: https://www.instagram.com/p/1bMso-jXQF/?taken-by=bmngld

## Functionality

The LEAP's raw output is processed and scaled for reliability within the Pure Data patch 'pd-leap-midi-controller.pd'.

MIDI output is sent from Pd application, which allows routing to a Digital Audio Workstation (DAW) (Ex. Ableton Live, Pro Tools) or external hardware via a MIDI output.

Maintained by Ben Mangold

Underlying 'leapmotion' Pd Object Developed by Chikashi Miyama: http://puredatajapan.info/?page_id=1514

## Installation 

1) Install PureData (Pd) and LEAP Motion software

2) Plug in LEAP Motion

## Configuring Pd MIDI Output and Running the Patch

2) Open Pd Patch with PureData, File>Open 'pd-leap-motion-midi-controller.pd' 

3) Configure Pd MIDI Output, Pd>Preferences>MIDI Settings..

4) Configure DAW to recieve MIDI

5) Begin MIDI Performance

## Configuring your DAW to recieve MIDI

TODO
