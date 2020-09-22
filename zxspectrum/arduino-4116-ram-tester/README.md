# Arduino-based tester for 4116 DRAM

This is a KiCad schematic of an Arduino based tester for the 4116 DRAM chips used in the lower 16K of RAM in the ZX Spectrum.

The majority of the board is to generate the +5v, -5v and +12v voltages required to power the 4116 DRAM chip.

You can read the details of this project on [this blog](https://www.evolutional.co.uk/post/arduino-4116-dram/).

## Bill of Materials

| Designator | Qty | Desc | Value | Note |
|---|---|---|---|--|
| C1, C2, C5, C6 | 4 | Electrolytic Capacitor | 10uF | |
| C3, C4 | 2 | Electrolytic Capacitor | 100uF | |
| D1, D2 | 2 | Small signal switching diode | | |
| U1, U2 | 2 | 7660 charge pump IC | LMC7660 | |
| U3 | 1 | 7812 12v regulator | LM7812 (TO220) | |
| U4 | 1 | 7805 5v regulator | LM7805 (TO220) | |
| A1 | 1 | Arduino Nano | |
| S1 | 1 | 16 pin ZIF Socket | |

A breadboard, strip board or matrix board will be required for layout.

Additionally, 2xLEDs and a switch will be required to signal the good/bad status.
