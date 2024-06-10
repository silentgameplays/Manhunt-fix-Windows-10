# Manhunt-fix-Windows-10
Manhunt-Fix-Windows-10-for-all-builds
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not afraid to take the risk of learning some new stuff in the process.

How to get Manhunt working on Windows 10 (21H1) and Windows 11:
# NB!The latest fix without any folders is here it does not require previous ones and works across builds moved all the old fixes to other repo!

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

1. Install through Steam

# # NB!Currently based on user feedback there are more folders in this fix: 

2. Download and extract all the files from this fix corresponding to your Windows 10 build.

3. Copy/Paste from the required folder into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

4. Run the Manhunt Fix.bat file

5. Disabling audio sound loops completely by renaming/removing audio files manually:
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\PORN folder and find the file named PORN.RIB and change it to something like p0rn.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB
6. For fixing broken sound in-game just install openal using the oalinst provided in this repository

# Fixing audio loops without removing/renaming the files by using ermaccers audio fix:
* There is a folder called Manhunt Audio Fix Experimental copy/paste the files from that folder into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

# NB! For Dual GPU laptops ONLY!Experimental might not work in every case:
1. Download everything extract.

2. Copy all files from Reshade Dual GPU's Laptops folder C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

3. Go to your NVIDIA Control Panel>3D Settings>Global find the preferred GPU and set it to NVIDIA

4. Run the Manhunt Fix.bat file

5. Enjoy

# For people who are having issues-YOU NEED TO INSTALL THIS FIX ON A CLEAN INSTALL OF THE GAME. PLEASE READ IF YOU ARE TRYING TO USE IT ON A GAME WITH A BUNCH OF WEIRD FIXES INSTALLED FROM DIFFERENT SOURCES AND START EXPERIENCING ISSUES! Thank you!
 
 0. Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable and Direct Play .NET 3.5 Framework support
 1. Uninstall Manhunt through Steam 
 2. Delete the main folder Manhunt,location C:\Program Files (x86)\Steam\SteamApps\common\
 3. Install the game again,download the fix again 
 4. Extract,Copy/Paste into C:\Program Files (x86)\Steam\SteamApps\common\Manhunt
 4. Run the Manhunt Fix.bat file
 5. Launch the game.
 
 # For recovering save games before doing all the above (skip if no saves)
 1. Find this folder location User\Documents\Manhunt User Files\SaveGames\ 
 Copy/Paste your previous saved games from there files usually look like this MANHUNT0.SAV (skip if no saves)
 # After doing the fresh install launch the game at least once,launch a new game,quit (skip if no saves) 
 2. Find this folder,location User\Documents\Manhunt User Files\SaveGames\ 
 Copy/Paste your previous saved games files usually look like this MANHUNT0.SAV (skip if no saves)

 # Manhunt Fix Linux

1. Install mangohud for your distro
2. Install Manhunt through Steam
3. Go into Manhunt folder and rename manhunt.exe to manhunt.exe.old
4. Rename testapp.exe into manhunt.exe
5. Go to Steam>Manhunt>Compatibility>General>Launch Options
6. MANGOHUD_CONFIG="fps_limit=60,no_display" mangohud %command%
7. (Optional) If the defalt Steam Proton version does not work try a custom proton version from Glorious Eggroll, latest tested with this fix was 9.7. https://github.com/GloriousEggroll/proton-ge-custom/releases 
8. Enjoy the game

# silentgameplays
 
That's it,you are good to go,enjoy the game.

# All the credit goes to the creators of the original Manhunt fix patch AJ Collins,credit goes to ThirteenAG for .ini FPS limiter visit his site for more goodness:https://thirteenag.github.io/wfp 
# Credit for audio fix goes to ermaccer,visit his website for more Manhunt goodies:https://ermaccer.github.io/
# NB Updated to Windows 11 22H2 build version
# Combination of fixes,testing,manual configuration is done by silentgamepls. Hopefully will work for everyone and will save time looking for workarounds.
# NB added audio fix by ermaccer,experimental,check his repo also: https://github.com/ermaccer/Manhunt.AudioFix/releases/tag/1.0b5
# NB Audio Fix Has been removed from the main fix and placed into a separate repository https://github.com/fkortsagin/Manhunt-Fix-Alternative due to reports of false positives from Virus Total,related to using the ThirteenAG's dinput8.dll wrapper and ermaccers AudioFix.asi required for the audio fix to work,use at your own risk if you want functional audio in game and/or if you require the ThirteenAG's Widescreen Patch.
# NB! Added folder Manhunt Fix Newer Version with the latest Wine Build, use the files there in  case you have trouble detecting newer hardware.
# User safety is a priority,if you require functional audio and/or ThirteenAG's Widescreen Patch please use the files provided in https://github.com/fkortsagin/Manhunt-Fix-Alternative repository
# NB for all the users,please report any issues to the issues section in the github repo,not on my gaming youtube channel under unrelated videos!

# Cheers! 
# silentgamepls
