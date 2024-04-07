  ___  ____  _   _ _____  __     ______    ___  
 / _ \|  _ \| \ | |___ /  \ \   / /___ \  / _ \ 
| | | | |_) |  \| | |_ \   \ \ / /  __) || | | |
| |_| |  __/| |\  |___) |   \ V /  / __/ | |_| |
 \___/|_|   |_| \_|____/     \_/  |_____(_)___/ 

PC-9801/9821 Soundboard
2024.3 by RLB (Gekko3622)
Original schematic by Ethy1ene

Intro:

This ZIP archive contains all files related to my implementation of Ethy1ene's publicly released OPN3 schematic. Please feel free to modify or improve it in any way you see fit.

------------------------------------------------------------------------------------------------------

ZIP Contents:

1. KiCAD Project - Contains the full KiCad project for my version of the OPN3 soundboard.

2. Production Files - Contains all files necessary to produce the exact PCB that I have. 
   
   I HIGHLY RECOMMEND paying your PCB fabricator to supply and assemble the small SMD devices. 
   This folder includes turnkey BOM and top placement files formatted for JLCPCB.
   
   This will include my logo on the PCB, as it is guaranteed to be an exact match to my own design.
   If you wish to produce a PCB without my logo, you will need to export new fabrication files from KiCad.

3. JEDEC File - Contains a .JED file that must be programmed to the GAL20V8.
                This is mandatory. Please ensure you have a programmer that can write to a GAL20V8.

4. DigiKey Order List - Lists all components I purchased from DigiKey. Anything not on this list was 
   purchased for assembly by JLCPCB or needed to be purchased used or new old stock (see below).

------------------------------------------------------------------------------------------------------

Used/New Old Stock Parts Required:

1. YMF288-M Sound Chip
2. NEC UPD6379GR 16-Bit DAC
3. Lattice GAL20V8B-25LP Programmable Logic Device (PLD)

Note 1: UPD6379A is a pin-reversed variant. If you use it for some reason, it needs to be rotated 180 degrees.
Note 2: National Semiconductor makes a GAL20V8 which is still available. I have not tested it and cannot tell you which part number would be the best match.

------------------------------------------------------------------------------------------------------

Credits:

HUGE thanks to Ethy1ene for releasing his original OPN3 soundboard schematic and providing advice and troubleshooting. Without his help, this project wouldn't exist.

Thanks also to TD-Linux and i509VCB for their advice and guidance, pushing me to learn better practices as I worked.