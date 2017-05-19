pi-top Accessory Board Template
===============================

This is a blank pi-top "accessory" board.  It is a template for creating custom accessory boards that fit within the pi-top laptop and pi-topCEED Raspberry Pi based computers.  It contains the board outline with the accessory buss connectors placed correctly to fit with the pi-top HUB board, pi-topSPEAKER or pi-topPROTO.

## BOM Notes:
The BOM for this project is the board itself, plus the two connectors.  Unfortunately 2x34 pin connectors are not readily available from my preferred vendor, Digi-Key.  I therefore stacked smaller connectors side-by-side to make a total of 34 pins.  

On the socket side (J2) this is constructed one Harwin M22-6550542R (Digi-Key 952-3191-1-ND) and two Harwin M22-6550642R (Digi-Key 952-3192-1-ND).

On the header (pins) side (J1) this is constructed from one 3M 951224-4620-AR-PR (Digi-Key 3M9210CT-ND) and one 3M 951210-4620-AR-PR (Digi-Key 3M9205CT-ND).

This project was done partly to contribute to the pi-top community and partly to learn KiCAD. (I'm switching from Eagle CAD due to their change in licensing.)

## Status:
The board has not been fab'd and therefore is not tested, but I did a 1:1 printout and compared that to the pi-topPROTO.  Everything checks out so far.