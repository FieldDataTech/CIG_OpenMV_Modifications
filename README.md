These files need to be added to a Linux Visual Code project that contains the OpenMV firmware project. 
These files need to be added to the following folders in the project:
[TOP LEVEL OPENMV FOLDER]/src/bootloader/src/main.c.
[TOP LEVEL OPENMV FOLDER]/src/micropython/stm/boards/FDTV4
[TOP LEVEL OPENMV FOLDER]/src/omv/boards/FDTV4
[TOP LEVEL OPENMV FOLDER]/src/omv/ports/STM32/main.c
Additionally, the bootFDT.py script from the related repo needs to be added to
[TOP LEVEL OPENMV FOLDER]/scripts/libraries/bootFDT.py
