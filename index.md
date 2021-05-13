# This is an Underwater ROV project

We want to build an underwater ROV. The features and objectives of this ROV are

- Simple to build using easily available comodity components.
- Fail safe so that in case of failure ROV is positively boyant
- Umbilical to surface only carries data no power.


## Motors

The motors will be outrunners. We choose this as there are not brushes that will corrode.

## Microcontroler

Currently we plan to use an Arduino. But might have to upgrade to something more powerful to handle video.

## Communication with surface.

Two wire and serial communication to the Arduino is what we were planning currently. Currently not sure if this can handle the video bandwidth. Moreover the arduino cannot handle the video. The video part of the communication is still TBD.

## Failsafe surfacing

We plan to design the ROV so that it has possitive boyancy. We will add a ejectable weight with a deadmans switch. If the battery or electorics die an normally open solenoid will release the weight causing the ROV to surface automatically.
