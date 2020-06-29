# Marlin4Clay

<img src="Images/print.JPG"  width="400" >

This is an adaptation of [Marlin](https://github.com/MarlinFirmware/Marlin) firmware, for the use in Clay 3D Printing. 

The firmware enables the interaction between a [Ramps 1.4](https://reprap.org/wiki/RAMPS_1.4) Arduino Mega Shield board, and BioFeeder. 

The comunication uses through [Experimental I2C](https://marlinfw.org/docs/gcode/M260.html). 

BioFeeder is an Arduino Uno Shield that controls paste extrusion system, I have been using it for BioComposites, but if can be used for sodering paste, clay, etc. 

## Arquitecture

<img src="Images/arquitecture.png"  width="800" >

### The Extruder
<img src="Images/extruder.jpg"  width="400" >

The extruder is an [auger screw](http://unfoldfab.blogspot.com/2012/08/road-to-better-paste-extrusion-episode.html) based system wich control comes directly from the Marlin firmware, wich follows the Gcodes instructions from the slicer. 

