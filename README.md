# Marlin4Clay

<img src="images/print.JPG"  width="400" >

Marlin4Clay is an I2C enabled [Marlin](https://github.com/MarlinFirmware/Marlin) version for, and a specific firmware for extrusion systems for viscous materials 3D printers.

The system enables the interaction between the feeder, and the extruder. 

## Arquitecture

<img src="arquitecture/print.JPG"  width="400" >

### The Extruder
<img src="arquitecture/print.JPG"  width="400" >

The extruder is an [auger screw](http://unfoldfab.blogspot.com/2012/08/road-to-better-paste-extrusion-episode.html) based system wich control comes directly from the Marlin firmware, wich follows the Gcodes instructions from the slicer. 

### The Feeder

The feeder stores the material away from the extruder, to reduse the systems inertia. It can be operated through a Stepper motor and a lead screw, or an air pump. 

## BioFeeder

BioFeeder is a DIY Arduino Uno Shield developed to provide the following functions: 

- I2C Comunication
- Stepper Motor control
- Air pump control
- Air pressure sensor through I2C comunication

### Bill of Materials

 Materials

| Qty |  Description    |  Price  |           Link           | Notes  |
|-----|-----------------|---------|--------------------------|--------|
| 2   | LM8UU Linear Bearings    |  1.00 $| https://www.amazon.com/gp/product/B0711SNV4N?pf_rd_p=1581d9f4-062f-453c-b69e-0f3e00ba2652&pf_rd_r=R9JVPX22R85X7FW7D5QV   |    Order many, as those packages are more convinient than the unit price.    |
| 2   | Chrome Linear Guides    |  6.00 $| https://www.amazon.com/dp/B07H9HDNYP/?coliid=I3FH7XXY9FZOZL&colid=IKZOWO2NXR68&psc=0&ref_=lv_ov_lig_dp_it   |        |
| 1   | Nema 23 Steel Mounting Support  |  6.59 $| https://www.amazon.com/Stepper-Bracket-Support-Mounting-Engraving/dp/B075L92Y6B/ref=sr_1_1?keywords=nema+23+base&qid=1553722704&s=gateway&sr=8-1  |        |
| 1   | Nema 23 Lead Screw   |  112.49 $| https://www.amazon.com/STEPPERONLINE-Precision-Actuator-External-1-5875mm/dp/B07PTZ8JN4/ref=sr_1_5?crid=2S7PKB6A38INJ&keywords=nema+23+lead+screw&qid=1553722758&s=gateway&sprefix=nema23+lead%2Caps%2C135&sr=8-5   |        |
| 1   | Ball Bearing  |  6.97 $| https://www.amazon.com/ABI-Enduro-cartridge-bearing-9-5x22-2x7/dp/B001GSKOB0/ref=sr_1_18?keywords=ball+bearing+9.5mm&qid=1553723200&s=gateway&sr=8-18   | This one is expensive, but you just need it to fit your lead screw from the motor.        |
| 2   | O'Ring  |  1.52 $| https://www.amazon.com/uxcell-Rings-Nitrile-Rubber-Diameter/dp/B07HRRTRP9/ref=sr_1_13?keywords=o+ring+50mm&qid=1553723371&s=gateway&sr=8-13   |     I used a 50mm diam with a 3mm thickness   |
| 1   | Thread Seal |  1.2 $| https://www.amazon.com/Everflow-811-5-Thread-Plumbers-White/dp/B00538ITFW/ref=sr_1_2?keywords=teflon&qid=1553723450&s=gateway&sr=8-2   |        |
| 1   | PVC Tube |  - $| |     You can find it easily in a Home Depot store. I used an 52mm inner diam and 61 mm outer diam.   |

I also used a kit of [heated thread](https://www.amazon.com/DYWISHKEY-Knurled-Threaded-Embedment-Assortment/dp/B07MWBJB67/ref=sr_1_1?crid=3L2FCJJJOUFU8&keywords=thread+heat+set&qid=1553723758&s=gateway&sprefix=thread%2Caps%2C142&sr=8-1-spell), but they can be replaced by simple nuts.
