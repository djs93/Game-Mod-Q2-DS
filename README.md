# Quake 2 Mari0
Second IT266 game modification, this one is for Quake 2

# Quick Notes:
* You must use the included config for the portal gun to function properly!

# How to install (Windows):
* Go to your Quake 2 directory 
  * (for default Steam this is "C:\Program Files (x86)\Steam\steamapps\common\Quake 2")
* Create a new folder for the mod in this directory
* Clone/Download origin/final branch from this repository into the new folder
* Take the Quake2.exe from this repository and override the default executable
* (Or compile the game and quake2 projects yourself and place the resulting gamex86.dll in a separate mod folder and override the original quake2.exe, you MUST use this repo's config.cfg, however)

# How to open:
## Method 1: Create a shortcut (Steam)
* Go to your desktop and create a new shortcut to Steam.exe
* After the path to Steam and the final quotation mark in the "Target" category of the shortcut, add:
  * -applaunch 2320 +set game <name of folder with mod files in it>
* When you use this shortcut to launch the game, Quake 2 Mari0 will be loaded!
## Method 2: Create a shortcut (Other)
* Go to your desktop and create a new shortcut to Quake4.exe
* After the final quotation mark in the "Target" category of the shortcut, add:
  * +set game <name of folder with mod files in it>
* When you use this shortcut to launch the game, Quake 2 Mari0 will be loaded!
