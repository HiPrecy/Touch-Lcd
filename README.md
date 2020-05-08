# Touch Lcd

This UI only work with LEO 2.0.x firmware.

https://github.com/HiPrecy/Firmware-HiPrecy/tree/LEO/2.0.x

https://github.com/HiPrecy/Firmware-HiPrecy/tree/LEO/2.0.x-TMC2209

## Uploade screen firmware to screen

Step 1：Format the TF card and copy files

run windows command system as administrator, then enter：

format g:/fs:fat32/a:4096/q

Note: 
g is the disk number of your TF card，and the card size must be 1-16G.

Unzip your download zip file and copy DWIN_SET folder to your sd card.

Step 2：Flash the firmware to TF card

Insert the TF card into the card socket (left slot at back side of the screen) ,and then power on the screen. 
Wait for the blue screen and appear on the first line of the screen “SD Card Process... END !” it’s may take 1-2minutes.
Turn off the power and re-power the screen Wait for the boot screen，it’s may take 1-5s.