# HSW Screwdriver Holder

A screwdriver holder for the honeycomb storage wall.

## Usage

Typically the only parameter you are concerned with is `arms`.

To adapt it to your situation, take calipers and measure the maximum diameter of your scredriver-head and -shaft. This will be used for the holes, so measure the largest diameter, so everything will fit.

Then measure the largest diameter of the handle. This will be used to calculate the spacing between the arms.

I've added 0.5 mm to the diameter of the screwdriver-shaft and 1.0 mm to the handle as it was too tight otherwise (I did a couple of test prints, more on that below).

Add your corrected measurements as values in the `arms` parameter.

## Printing

I've printed this with PLA, 4 Perimeters, 20% infill, as that´s the settings I use for all HSW inserts and attachments.

You also need to have two HSW inserts to attach it to the wall, which you can find at the original [Honeycomb Storage Wall by RostaP page](https://www.printables.com/model/152592-honeycomb-storage-wall/files).
I've used M3 screws and nuts but youi can use whatever you have at hand. Make sure to adapt the `screw_m` parameter accordingly.

## Acknowledgements

This design is compatible to [Honeycomb Storage Wall by RostaP](https://www.printables.com/model/152592-honeycomb-storage-wall).
It also uses the [ISO/DIN standard Screw Holes library by Carlo Wood](https://github.com/reycf/mini-itx-atx/blob/master/screw_holes.scad).
