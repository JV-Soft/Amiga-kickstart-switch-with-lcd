# Amiga-kickstart-switch-with-lcd

This kit consists of several parts and can work in different configurations.

This kit is intended for installation on the Amiga A1200

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

Connect the IDE cable to the IDE adapter and the ROM cable to the ROM adapter

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/12.jpg)

Now you can turn on the Amiga and check the operation of the kickstart switch
When you turn it on for the first time, the current version of kickstart will be displayed on the screen.
Push left button to select the kickstart you want,push right button to reset the Amiga.

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/13.jpg)

Now you can install IDE-SD adapters(IDE-SD adapters are not included)
The IDE adapter has markings for the first contact  
The left adapter is face up and the right adapter is face down
They should be installed like this -

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/14.jpg)
![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/15.jpg)

Now you can connect the Gotek control if you need it, there is a special adapter for this.
There are a lot of Gotek options, but the essence comes down to taking signals
at the encoder connection point and two signals for the LCD screen.
The encoder has 5 pins, 3 pins on one side are rotation,
two pins on the other side are the button when you press the encoder.
The encoder needs to be unsoldered, and the original Gotek LCD screen must be turned off or removed.

Here is the connection diagram -

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/16_2.jpg)

This requires certain skills. Find the documentation for your Gotek model so you know where these connection points are.
In my case it turned out like this -

![](https://github.com/JV-Soft/Amiga-kickstart-switch-with-lcd/blob/main/Pictures/17.jpg)

After that, connect the cable to this small board and connect it to the main board in the IDE connector,
after that, when you select ROM, you will see information about the ROM
, and after resetting, the screen will display information from Gotek






















