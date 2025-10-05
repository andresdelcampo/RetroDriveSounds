# Retro Drive Sounds
This repo intends to conserve the sounds of old PC disk drives (floppies or hard disks). 
Started as a collaboration to 86Box for the disk drive noise sounds feature, who know if this might grow more.
Contains sounds from at least 15 different drives including drives from other sources.


## Drives from own recordings:
Recorded with a TASCAM DR-05X in WAV 16 bit 48 KHz mono.

- Alps Electric Co Ltd model DF354H148F, 3 1/2 1.44 MB, black color. I think its sounds are quite the standard of what I remember of the drives of the era at least, and quite clean. This one was obtained purchased second hand. Recorded in a 486 with AMI BIOS.

- Panasonic JU-256, 3 1/2 1.44 MB, black color. I am not as convinced as with the Alps Electric, but an alternative set of sounds that some people prefer. This one was obtained purchased second hand. Recorded in a 486 with AMI BIOS.

- Panasonic JU-475-5 (a 5 1/4 floppy disk drive, black color, new old stock from PolyPlay) running in a NuXTv2 (8088, NEC V20 CPU). Trimmed with Audacity. It includes all kind of sounds, from inserting a disk, closing the drive, to accessing the drive with no disk, with an unformatted disk, or formatting a disk in full. Of course, loading MS-DOS -several versions, etc. Recorded in two sessions. The second one, only POSTs, in a 486 with AMI BIOS. 

- Teac FD-55GFR, a 5 1/4 white floppy disk drive. Unfortunately it would not read correctly the disks during the recording, so files are limited. Recorded in a 486 with AMI BIOS.

License: https://creativecommons.org/licenses/by/4.0/


## Drives from other sources:

- 2 Floppy drives samples from MAME (https://github.com/mamedev/mame)
- 2 Floppy drives, plus CDROM, modem, etc sounds from IBMulator (https://github.com/barotto/IBMulator)
- 7 different floppy drives from flopster (http://shiru.untergrund.net/files/flopster.zip)

IMPORTANT: Read their respective licenses


## Notes

Open to contributions.



## About PCDoctor diagnostics

- 5 1/4 Panasonic running in XT, with a 360 KB disk (40 sectors). This drive supports 1.2 disks too but I do not have any. Ran 12 tests -seems like the second batch is repeated from the first one, but not 100% sure. 
- 3 1/2 Panasonic running in XT with a 1.44 MB disk (80 sectors). Ran 6 tests.
- 3 1/2 Alps running in 486 -much shorter diagnostic. Also in 1.44 MB disk (80 sectors). Ran 6 tests.

Tests include edge to edge seeks, progression of edge to center seeks (i.e. 1, 80, 2, 79, 3, 78...), random seeks, linear verification, random verification, etc.