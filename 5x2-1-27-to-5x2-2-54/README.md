# 2x5 pin 1.27 mm male to 2.54 mm male header adapter PCB

This board was created to convert  between the "small" J-Link EDU Mini Programmer-Debbuger 1.27 mm pitch connector to a 2.54 mm male header.

![PCB 3D picture](assets/5x2-1-27-to-5x2-2-54.png)

The J-Link EDU Mini sports a 2x5 1.27 mm male connector and includes a female to female 2x5 1.27 mm ribbon cable for target connection.

If for some reason your target doesn't have the same connector (debug pins scattered somewhere on the PCB), or want to connect to a circuit on a breadboard, this PCB will ease the task. 
## How to use this repository

The PCB was developed in KiCad V6.0.

## Directory structure

* The root folder contains KiCad files: project, schematic and PCB.
* gerber/single directory contains ready to manufacture files, for a single board.
* gerber/panel_100mmx100mm directory contains ready to manufacture files that fits in a 100mm x 100mm panel (use Vcuts!).
* assets directory some additional info about the project.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This is an Open Hardware project and is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
