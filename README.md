# Amiga-kickstart-switch-with-lcd

This kit consists of several parts and can work in different configurations.

This kit is intended for installation on all versions and revisions of the Amiga, but for simplicity I will describe an example of use on the Amiga A1200

The kit consists of a main control board on an STM32 microcontroller, this board has an LCD screen, two control buttons and an encoder for controlling the Gotek floppy disk drive emulator 
The second board, which is installed instead of two standard Kickstart microcircuits, contains 4 ROMs
The third board is an IDE adapter into which they are installed two IDE-SD adapters, for SD cards you can switch boot between two different OS
The fourth board is a small board for connecting to Gotek.

![Kit](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/1705765117936.jpg)

Installation on Amiga:
Take the corner pin from the kit and solder it to the second pin of the TP1 connector on the Amiga board.

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/2.png)

Solder to the second pin from the left -

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/3.jpg)

Take the ROM adapter, turn it over and connect the black wire to the Reset pin

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/4.jpg)

Install the ROM adapter in the Amiga, the first contacts should be empty, 
the adapter has fewer contacts than the panel in the Amiga, as is the case with the native kickstart.
Also connect the black wire to the pin you soldered.

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/5.jpg)

Install IDE adapter

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/6.jpg)

Carefully pull out the latches in the connectors, be careful not to pull too hard so as not to break them -

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/7.jpg)

Insert the cables into the IDE and ROM connectors

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/8.jpg)

Then you can immediately thread the cables through the top cover of the Amiga, 
or do it later after checking. The cables must be routed through the first mesh.

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/9.jpg)
![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/10.jpg)
![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/11.jpg)












