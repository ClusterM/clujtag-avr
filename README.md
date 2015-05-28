clujtag
===========

Very simple JTAG programmer based on AVR microcontroller with hardware USB.

You can use it to flash SVF or XSVF files via JTAG interface. 

How to build:
* You need LUFA library, download it here: http://www.fourwalledcubicle.com/LUFA.php
* Edit Makefile, set path to LUFA library and microcontroller type
* Edit *defines.h* to set JTAG pins and optionally led pin
* Compile and flash it

Device should be detected as virtual serial port. Under Windows use *clujtag.inf* as driver if necessary. Now you can use client to play SVF or XSVF files: https://github.com/ClusterM/clujtag-client
