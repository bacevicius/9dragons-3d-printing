# 9dragons-3d-printing
Tracking the progress of converting legacy game models to 3D prints

### What is 9Dragons?
9Dragons is a free to play MMORPG me and my friends used to play back in 2007-2012. It was quite popular back in the day and is based on ancient martial arts.

### What is this project?
Driven by nostalgia and having acquired access to a 3D printer, I decided to try to 3D print some of the game models since they are pretty iconic and cool-looking. I also needed something to gift to my friends for Christmas.

Just to get this out of the way, this project is non-commercial and I am not planning to sell any of the prints. This is purely a hobby project.

# Acquiring the game models

All tools and scripts used in this project are in `Tools` folder.

For this project, we are interested in two game data folders:

```C:\Program Files (x86)\Steam\steamapps\common\9Dragons\Data\Model```  for models;
```C:\Program Files (x86)\Steam\steamapps\common\9Dragons\Data\Texture``` for textures.

For integrity purposes, I will not be uploading the raw game files. Instead, I will explain how to extract the files from the Steam installation yourself.

### Processing the raw game files
(To complete this part, I found a [forum post](https://progamercity.net/game-files/3088-9dragons-online-xp-packer-extractor.html) by someone name h4x0r, dating all the way back to 2012. Thanks, h4xor.)

9Dragons model and texture files are compressed into .XP files. These files have to be unpacked before we can do anything else with them.

To unpack .XP files located in `Model` and `Texture` folders, we use a program called QuickBms.

To use QuickBms, simply open the `quickbms.exe` in the `QuickBms` folder. When opened, it will ask for a script to run. Choose the file `9dragons bms script.txt` located in the same folder.

Then it will ask for input files. I extracted all .XP files in `Model` and `Texture` folders and placed them into one shared folder. 

### Inspecting the models
https://forum.xentax.com/viewtopic.php?f=16&t=8317