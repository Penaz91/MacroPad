My Macropad Project
====================

!! This circuit has never been tested, I take no responsibility for any damage or loss that comes from this project !!

This is the project of a MicroPython-programmable (via [KMK](http://kmkfw.io/)) Macro Pad using a Raspberry Pi Zero and some components.

This came from the fact that no available Commercial Mechanical Macro Pad has 20 Keys and 4 Rotary Encoders, plus their configuration programs don't really look flexible enough for my taste.

Required Software
-----------------

You will need to following software to open and edit this project:

- [KiCad](https://www.kicad.org/) 7.0.9 or Higher: for the Schematic Files
- Any CAD Program (Like [FreeCad](https://www.freecad.org/)) that supports DXF Files: for viewing the plate

Known Issues
------------

- ERC Shows "Input Power pin not driven by any Output Power pins" on U1 for pins:
    - Pin 13 (GND)
    - Pin 36 (3V3)
- DRC Shows 16 Violations "Silkscreen clipped by solder mask"

I have no idea how to fix these.
