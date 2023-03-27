# Kobra-Kai-with-Thumbnail-preview
This is a basically malebuffy's Kobra Kai firmware forked to run in the Anycubic Kobra Standard with some extra features from jojos38 firmware.
Features:

From jojos38:
-Replace booting music with a single bip
-Faster auto leveling
-Faster homing
-Slightly faster printing when using default printer settings
-Slightly faster booting speed
-Reduced noise (motherboard fan)
(No linear Advance and rolled back mods to make it work)

From Malebuffy:
-Added G-Code Preview function
-Cura Post-Script (lowered resolution to 10% as 30% was making it crush)
-Cobra Kai UI
-Z offset babysteps at 0.01
-M117 Enabled for comments (Layer height etc)

https://github.com/jojos38/anycubic-kobra-improved-firmware

https://github.com/malebuffy/Kobra-Max-Cobra-Kai-UI-and-Firmware

Instructions for installing printer firmware:

-Put the firmware.bin into the root of the SD and insert it to the 3D printer SD slot (Not the LCD)
-Switch the 3D printer on and wait for the beeps.

Instructions for installing the UI:

-Put the DWIN_SET folder into the root of the SD and insert it to the 3D LCD SD slot (Not the printer slot)
-Switch the 3D printer on and wait for the blue screen. After it's done,remove the SD card and restart the printer

Instructions for installing G-Code Thumbnail Script in Cura:

-Open the Config folder (Help - Show configuration Folder). Navigate to the Script folder. If that doesnt work the folder ist usually in the C:\Users\Your Name\AppData\Roaming\cura\5.x\scripts
-Download and put the script here. Must have a .py extension
-Restart Cura and go to Extensions - Post Processing - Modify G-Code and Add Script. Select Create Kobra Thumbnail.
-Now whenever you slice a script, a thumbnail is created in the G-Code file that the Kobra Max can read. Only Thumbnails with this scripts are recognised.