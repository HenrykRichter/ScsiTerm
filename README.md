# SCSITerm 08-15 

This project is a design of an active SCSI terminator for DB-25 ports.

## Pictures

The picture below shows Revision3 of the board.
![front view](https://raw.githubusercontent.com/HenrykRichter/ScsiTerm/main/Pics/scsiterm0_3.jpg)


## Parts list
- 1  DB-25 male (solder cup)
- 1  Voltage regulator SOT-223 LD1117 SC-R (or similar)
- 18 Resistors 110R 0805
- 1  Resistor 680R 0805 (R19, optional)
- 1  LED 0805 (optional)
- 3  Capacitors 10uF 0805
- 1  Resistor 220R 0805 (R21)
- 1  Resistor 330R 0805 (R20)
- 1  Resistor 2k 0805 (C3, instead of a previously planned capacitor for accurate 2.85V)

## Building and installation notes
Soldering should be straightforward for the SMD components and the DB-25 connector. Please don't forget the resistors on the underside of the PCB.

The PCB was designed with typical DB-25 shells in mind to be used as enclosure. Nevertheless, a custom case design for 3D printing is part of the repository. Just print the design twice and fasten it using M2.5 x 10 cylindrical screws and matching nuts.

## License

The material in this project may be used under the terms of the Attribution-NonCommercial-ShareAlike 4.0 International creative commons license. Please refer to https://creativecommons.org/licenses/by-nc-sa/4.0/ for details or see the LICENSE file in this repository.
