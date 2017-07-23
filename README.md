# GT2560_Marlin

*Note: To get the actual code, you need to checkout the "GT2560" branch. "master" only has this readme in it!*

This firmware is for a Monoprice Maker Select v2.1 3D Printer (aka Wanhao i3) running Marlin 1.x on a Geetech GT2560 board.

All the changes are in the configuration.h and additional pin configuration files. The original changes (look at commit history) are taken from the "GT2560" branch of the Marlin mainline and were submitted in a pull request. I pulled these out into a separate project because I made lots of changes to get it to finally work and thought people might havbe an easier time finding it if it were standalone.

Note:
The default Monoprice LCD screen was swapped out for a RepRap Graphic 128x64 LCD (http://reprap.org/wiki/RepRapDiscount_Full_Graphic_Smart_Controller) because the pinout for the connectors works better with the GT2560.

The LCD and board is nearly identical except that on original Meltzi board, the SD card is on built-in so there was no connector for wires to attach an SD card reader. 

Also, note that you need to rotate the connectors for the LCD and SD card by 180 at one end on some of the LCD boards because the polarized connector was soldered upside down. I had to do this and just cut the little polarizing key tab off one end of each ribbon cable.
