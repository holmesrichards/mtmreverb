This is a work in progress; better README to come soon. Meanwhile:

**Untested hardware and software — Do not assume anything works!**

# Spring Reverb

This is a Kosmo format adaptation of the Music Thing Modular Spring Reverb. 

# Circuit changes

Only very minor tweaks to the original circuit:

* Expansion module (consisting of a potentiometer and a pair of RCA jacks incorporated into main module
* Single rail-to-rail bypass caps replaced with dual rail-to-ground
* Power reversal protection diodes added
* AC coupling capacitors C1, C2 changed from 10 µF electrolytic to 1 µF film
* Footprint for 100k resistor to ground on IN_2 (FEEDBACK) left in place but marked "OMIT?"

## Current draw
 mA +12 V,  mA -12 V


## Photos

![]()

![]()

## Documentation

* [Schematic](Docs/.pdf)
* PCB layout: [front](Docs/_layout_front.pdf), [back](Docs/_layout_back.pdf)
* [BOM](Docs/BOM/springReverbRev2_bom.md)
* [Build notes](Docs/build.md)

## GitHub repository

* [https://github.com/holmesrichards/mtmreverb](https://github.com/holmesrichards/mtmreverb)
