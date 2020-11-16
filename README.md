
# cyber60

A DIY-friendly 60% using nRF52840 and ZMK: the cyber.

## Status:
CAUSION, project is being tested and only an early rough ZMK-implementation is done (not in main repo, check my fork)

## Specs cyber60:
- Module: Holyiot YJ-18010
- Standard Tray Mount support
- Non constant drain battery measurement
- Lipo charger for single cell 3.7V li-po/li-ion batteries
- RGB-led under Capslock for multi function indicator
- Possible to build with just a soldering iron (no underside pads etc)

## Layout support cyber60:
![alt text](./readme-images/layout_support_cyber60_Rev_A2.jpg "Layout support")

## Altium view of - cyber60
![alt text](./readme-images/cyber60_Rev_A2.jpg "PCB View - Rev A")

## Revisions:
- A1 - initial revision/prototype
- A2 (prerelease) - flipped PMOS-transistor, error in design. Added pulldown on enable to battery voltage measurement circuit, so it does not have to be disabled in code, only enabled. Minor silkscreen changes.
