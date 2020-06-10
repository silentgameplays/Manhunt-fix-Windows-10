# Manhunt-fix-Windows-10
Manhunt-Fix-Windows-10-for-all-builds

How to get Manhunt working on Windows 10:
# NB!The latest fix without any folders is here it does not require previous ones and works across builds moved all the old fixes to other repo!

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support
1.Install through Steam

2. Download and extract all the files 

3. Copy/Paste into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

4. Run the Manhunt Fix.bat file

# 5. (NVIDIA Users Only) Fixing other crashes and glitches:

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>Preferred Refresh Rate>Application Controlled

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>:Vsync:on

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>:Tripple Buffering:on

NB:AMD users same thing only in the AMD control panel(or ignore this step).

6. Fixing the annoying sound loops with poop sounds and porn sounds:

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\PORN folder and find the file named PORN.RIB and change it to something like p0rn.RIB

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\GASPOUR folder and find the file named GASPOUR.RIB and change it to something like g@spour.RIB

# For people who are having issues-YOU NEED TO INSTALL THIS FIX ON A CLEAN INSTALL OF THE GAME. PLEASE READ IF YOU ARE TRYING TO USE IT ON A GAME WITH A BUNCH OF WEIRD FIXES INSTALLED FROM DIFFERENT SOURCES AND START EXPERIENCING ISSUES! Thank you!
 0. Copy your saves somewhere from User\Documents\Manhunt User Files\SaveGames\ then delete the \Manhunt User Files\SaveGames\ folder (skip if no saves)
 1. Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support
 2. Uninstall Manhunt through Steam and delete the main folder Manhunt,location C:\Program Files (x86)\Steam\SteamApps\common\Manhunt
 3. Install the game again,download the fix again and extract,copy paste into C:\Program Files (x86)\Steam\SteamApps\common\Manhunt
 4. Run the Manhunt Fix.bat file
 5. Launch the game.
 6. Quit the game.(skip if no saves)
 7. Find this folder location User\Documents\Manhunt User Files\SaveGames\ drop your previous saved games there.(skip if no saves)

That's it,you are good to go,enjoy the game.

All the credit goes to the creators of the original Manhunt fix patch and the d3d8.dll wrapper find them somewhere here in Steam threads,also additional credit goes to the creator of WideScreen Patch ThirteenAG and crosire for creating the FPS limit wrapper.I just combined everything that worked for me,hopefully will work for you as well and you will avoid the headache with workarounds.NB added wine-based wrapper for Windows 10 2004 build support. 

Cheers! #gimalaji_blake
