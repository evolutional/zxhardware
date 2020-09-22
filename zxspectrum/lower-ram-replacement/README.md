# ZX Spectrum Lower RAM Replacement Board

This contains information about building a Lower RAM Replacement board for the ZX Spectrum.

There is a small blog series on the creation of this [part 1](https://www.evolutional.co.uk/post/zxspectrum-4116-ram-board/) and [part 2](https://www.evolutional.co.uk/post/zxspectrum-4116-ram-board-2/).

## Breadboard Prototype

![Lower RAM Breadboard prototype](docs/lower-ram-breadboard.png?raw=true)

This board has a few glitches, likely due to the HC parts and wire lengths.

### Bill of Materials

| Designator | Qty | Desc | Value | Note |
|---|---|---|---|--|
| U1 | 1 | 74 series logic inverter | 74HC04 | An LS or HCT part would be better! |
| U2 | 1 | 74 series octal register | 74HC374 | An LS or HCT part would be better! |
| U3 | 1 | 256kbit (32kbit x 8) SRAM | IDT71256L | This is 20ns RAM, after testing it might be too fast! |
| C1, C2, C3 | 3 | Ceramic Capacitor | 10uF | |

You'll need a full sized breadboard and various hookup & jumper wires.

This was tested by using the hookup wires and connecting directly into the sockets on the ZX Spectrum main board.
