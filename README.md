# NFC/RFID Breakout Board and Antenna

Breakout and antenna board for a 13.56 MHz NFC/RFID smartcard IC in the contactless MOB package.

![PCB](https://raw.githubusercontent.com/StarGate01/rfid-breakout/master/images/render.jpg)

## Usage

Use [KiCad](https://www.kicad.org/) with my [CustomComponents](https://github.com/StarGate01/KiCadLibs) library to view and edit the hardware project, or download the [fabrication files](https://github.com/StarGate01/rfid-breakout/tree/master/fabrication/rev1_1/gerber) for PCB manufacturing. I used the [RF-Tools for KiCAD](https://github.com/easyw/RF-tools-KiCAD) to create the rounded traces.

## Specification

The `39 mm * 39 mm` dual-side PCB carries a `35 mm * 35 mm` coil on the top side.

The antenna coil has a theoretical inductance of `2.196 µH`. To achieve the ideal inductance of `2.46 µH` (for an IC input capacitance of `56 pF`), a tuning capacitor `C1` (0805 size) of `TBA pF` has to be added.

## Thanks To

This project has been generously sponsored and manufactured by [PCBWay](https://www.pcbway.com/). [TODO: review]

Special thanks to *Satur9* for the [Coil Inductance Calculator](https://forum.dangerousthings.com/t/coil-inductance-calculator/4952) and also general help with the PCB design.
