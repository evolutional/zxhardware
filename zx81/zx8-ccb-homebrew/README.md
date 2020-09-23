# ZX8-CCB Homebrew

The [ZX8-CCB](https://www.sellmyretro.com/uploaded/img/ZX8-CCB_V12_Sync%20-%20manual.pdf) is the creation of Karl-Heinz Dahlmann (aka [PokeMon](http://www.sellmyretro.com/user/profile/PokeMon) / ginger-electronic.com).

This project is an imperfect home made recreation of the original project on stripboard, intended for educational purposes.

See the [accompanying blog](https://www.evolutional.co.uk/post/zx81-homebrew-zx8ccb/) for more details.

## Layout

![Layout](docs/zx8-ccb-perf-v1.png?raw=true)

You will need [DIY Layout Creator](https://github.com/bancika/diy-layout-creator) to view and modify the DIY file provided.

## Bill of Materials

Here's the parts that are used to build this:

|Designator | Qty | Desc | Value | Note |
|---|---|---|---|--|
| C1, C2 | 2 | Ceramic Capacitor | 10uF | |
| C3 | 1 | Ceramic Capacitor | 1uF | |
| R1, R2 | 2 | Variable Resistor | 5K | |
| R3, R4 | 2 | Resistor | 10K | |
| R5 | 1 | Resistor | 22R | The original uses 220R here |
| R6 | 1 | Resistor | 330R | The original uses 390R here |
| D1, D2 | 2 | Small Signal Diode | 1N4148 | The original uses a double-diode SMD package here |
| D3 | 1 | Small Signal Schottky Diode | BAT42 | |
| SW1 | 1 | Small SPDT Switch | | Used for the colour inverter. You can make this permanent by using a wire link |
| IC1 | 1 | 74 'XOR' logic IC | SN74LS86AN | |
| IC2 | 1 | 74 'AND' logic IC | SN74LS08N | The original used 2x single AND ICs, but this has 4 gates |
| S1, S2 | 2 | DIL socket | 14-pin | This is optional, you can skip this if you don't want to socket your ICs |

In addition to this, both wire jumper links and insulated wire is required; 30AWG is fine.

Finally, a piece of stripboard of at least 23 columns and 15 rows is needed for this layout.

## Result

![Final build v1](docs/zx8-ccb-homebrew-v1.jpg?raw=true)