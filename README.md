# Kobra-Kai-with-Thumbnail-preview
The firmware was created to be compatible with Anycubic's original Tri-Gorilla_ProA V1.0.4 motherboard and a DWIN LCD. 
Anycubic has made adjustments to their manufacturing process and some Kobra printers now come with the Tri-Gorilla_ProB V1.0.2 motherboard and a TJC screen. 
These are NOT compatible with this firmware.

v1.3

Added M600 support for filament change.

V1.2

Added Terminal menu screen to send GCODE directly from LCD (via malebuffy)

Added new UI options: Anycubic Dark Theme and Zelda botw.

![12w1](https://user-images.githubusercontent.com/116078892/229496903-855c0a31-1407-4904-86cf-3849d1e95249.jpg)      ![121](https://user-images.githubusercontent.com/116078892/229496925-5289a7b3-b8c4-4bb4-bf88-82c9ae8b0a4f.jpg)


************************************************************************

v1.1


Fixed Z-offset not being stored issue.(via malebuffy)

*************************************************************************
Features:


-Replace booting music with a single bip (via jojos38)

-Faster auto leveling(via jojos38)

-Faster homing(via jojos38)

-Slightly faster printing when using default printer settings(via jojos38)

-Slightly faster booting speed(via jojos38)

-Reduced noise (motherboard fan)

(No linear Advance and rolled back mods to make it work)

-Added G-Code Preview function(via malebuffy)

-Cura Post-Script (lowered resolution to 10% as 30% was making it crush)(via malebuffy)

-Cobra Kai UI(via malebuffy)

-M117 Enabled for comments (Layer height etc) ( displays in a new txt line in the print screen)(via malebuffy)

-Z offset babysteps at 0.01 (via wabbitguy)

-Automatic print screen when sending a print via Octoprint.(via wabbitguy)

SOURCES:

https://github.com/wabbitguy/Kobra_Max

https://github.com/jojos38/anycubic-kobra-improved-firmware

https://github.com/malebuffy/Kobra-Max-Cobra-Kai-UI-and-Firmware

<h2>Instructions for installing printer firmware:</h2>

-Put the firmware.bin into the root of the SD and insert it to the 3D printer SD slot (Not the LCD)

-Switch the 3D printer on and wait for the beeps.

Instructions for installing the UI:

-Put the DWIN_SET folder into the root of the SD and insert it to the 3D LCD SD slot (Not the printer slot)

-Switch the 3D printer on and wait for the blue screen. After it's done,remove the SD card and restart the printer

Instructions for installing G-Code Thumbnail Script in Cura:

-Open the Config folder (Help - Show configuration Folder). Navigate to the Script folder. If that doesnt work the folder ist usually in the C:\Users\Your Name\AppData\Roaming\cura\5.x\scripts

-Download and put the script here. Must have a .py extension

-Restart Cura and go to Extensions - Post Processing - Modify G-Code and Add Script. Select Create Kobra Thumbnail.

-Now whenever you slice a script, a thumbnail is created in the G-Code file that the Kobra can read. Only Thumbnails with this scripts are recognised.

-If you want the M117 codes to appear in your print screen such as the layer number that is currently being printed you also need to add the Display Filename And Layer on LCD post processing script:

![image](https://user-images.githubusercontent.com/116078892/230057957-8d03e84e-0af9-48f9-92a9-5296f5167feb.png)


After installing remember to do bed leveling, set Z-offset and your calibration routine. Enjoy!

