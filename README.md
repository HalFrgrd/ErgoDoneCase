# ErgoDoneCase
An acrylic case for the ErgoDone PCBs
---
I bought two [ErgoDone PCB's from KBDFans](https://kbdfans.myshopify.com/collections/pcb/products/ergodone-keyboard-pcb-1pcs-free-shipping?variant=37178300237) and modified [Litster's ErgoDox acrylic case](https://github.com/bishboria/ErgoDox). The PCBs are a little different to the standard ErgoDox design:

* Microcontroller is an Arduino Pro Micro instead of Teensy.
* Microcontroller is on left handside instead of right handside.
* IO expander changed from MCP23018 to MCP23017.
* IO expander is now on the right handside.
* Resistors have changed place and orientation.
* LEDs are located on the lefthandside on the top right.

Like Litster's, 3mm acrylic should be used for layers 1 and 5, and 4mm acrylic for the middle layers.
I only had 3mm acrylic so I needed a few washers to raise the PCB.

If you want the design without a handrest, replace the bottom half of my designs with the bottom edge of the handrestless designs from Litster. 