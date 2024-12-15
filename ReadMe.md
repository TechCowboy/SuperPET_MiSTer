# SuperPET for [MiSTer Board](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

# Documentation

The SuperPET is a 8032 PET with one or two added boards that were designed at the University of Waterloo. The computer has a built-in RS-232C interface and many built-in programming languages. In Europe, this machine was called the MicroMainFrame 9000, or MMF 9000.

https://www.zimmers.net/anonftp/pub/cbm/firmware/computers/pet/SuperPET/index.html

## Installation:
Copy the *.rbf file at the root of the SD card. Copy roms (*.prg,*.tap) to **SuperPET** folder.

### Notes:
* PRG apps are directly injected into RAM. Load command is not required.
* TAP files are loaded through virtual tape input. press **F1** to issue LOAD command, and then choose TAP file in OSD.
* **F12** opens OSD.

### System ROM structure
* 0000-0FFF - unused, all zeros
* 1000-7FFF - mapped to 9000-FFFF

## Download precompiled binaries
To Be Announced
