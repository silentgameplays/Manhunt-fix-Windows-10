# Manhunt-fix-Windows-11
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.

How to get Manhunt working on Windows 11:
# NB!The latest fix without any folders is here it does not require previous ones and works across builds moved all the old fixes to other repo!

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

1. Install through Steam

# NB!Currently based on user feedback there are more folders in this fix: 

2. Download and extract all the files from this fix corresponding to your Windows 10 build.

3. Copy/Paste from the required folder into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

4. Run the Manhunt Fix.bat file

5. Disabling audio sound loops completely by removing audio:
Manually:
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\PORN folder and find the file named PORN.RIB and change it to something like p0rn.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB

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
 
 # FOR RETAIL VERSIONS OF MANHUNT ONLY,CD's,ISO's,etc when you get Steam 02 error(DO NOT RUN THIS ON STEAM VERSIONS OF THE GAME!!!!!)
 1. Install the game
 2. Depending on your GPU use the appropriate folder with the fix files,f.e for some laptops use the Reshade Dual GPU's Laptops folder,on others enable NVIDIA Driver as main instead of Intel in the NVIDIA Control Panel>Program Settings>Set Primary GPU to NVIDIA instead of Intel HD
 3. Copy/paste the testapp.exe from Manhunt TestApp for non Steam Versions folder
 4. Run the Manhunt Fix.bat file,do not launch the game yet.
 5. Go into your Manhunt folder,look for the installation it can be custom in every case.
 6. Rename the manhunt.old.exe to that appears after the patching to manhunt.exe
 7. Rename manhhunt.exe to manhunt.old.exe
 8. Launch the game.
 
That's it,you are good to go,enjoy the game.


That's it,you are good to go,enjoy the game.

# All the credit goes to the creators of the original Manhunt fix patch AJ Collins,credit goes to ThirteenAG for .ini FPS limiter visit his site for more goodness:https://thirteenag.github.io/wfp 
# Combination of fixes,testing,manual configuration is done by silentgamepls. Hopefully will work for everyone and will save time looking for workarounds.
# NB added wine-based wrappers for Windows 10 2004 build support. 

# NB added audio fix by ermaccer,experimental,check his repo also: https://github.com/ermaccer/Manhunt.AudioFix/releases/tag/1.0b5
# NB for all the users,please report any issues to the issues section in the github repo,not on my gaming youtube channel under unrelated videos!

# Cheers! 
# silentgamepls
