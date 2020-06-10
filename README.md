# Manhunt-fix-Windows-10
Manhunt-Fix-Windows-10-for-all-builds

How to get Manhunt working on Windows 10:
# NB! For each build of Windows 10 starting from 1809,1909 there is a separate folder for fixes!The latest and "greatest" Windows 10 build fixes are without a folder,copy/paste the fixes depending on the Windows 10 build version you have!

1.Install through Steam

2.Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

3.Fixing the gate bug and other crashes:

-Download and extract all the files depending on your version of Windows 10 using this link: https://github.com/fkortsagin/Manhunt-fix-Windows-10/ into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

4.Run the Manhunt Fix.bat file

5.(NVIDIA Users Only)Fixing other crashes and glitches:

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>Preferred Refresh Rate>Application Controlled

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>:Vsync:on

-For Nvidia users>Nvidia Control Panel>Manage 3D Settings>Program Settings>:Tripple Buffering:on

NB:AMD users same thing only in the AMD control panel(or ignore this step).

6.Fixing the crashes after Scenes 1,2 an later for Windows builds 1903,1909 and later(finally)

-Be sure that these files are put as well into the manhunt directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt:
Manhunt.WidescreenFix.asi,Manhunt.WidescreenFix,modupdater.asi,dinput8.dll

7.Fixing the annoying sound loops with poop sounds and porn sounds:

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\PORN folder and find the file named PORN.RIB and change it to something like p0rn.RIB

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB

-Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\GASPOUR folder and find the file named GASPOUR.RIB and change it to something like g@spour.RIB

# For people who are having issues-YOU NEED TO INSTALL THIS FIX ON A CLEAN INSTALL OF THE GAME. PLEASE READ IF YOU ARE TRYING TO USE IT ON A GAME WITH A BUNCH OF WEIRD FIXES INSTALLED FROM DIFFERENT SOURCES AND START EXPERIENCING ISSUES! Thank you!
 0. Copy your saves somewhere from User\Documents\Manhunt User Files\SaveGames\ then delete the \Manhunt User Files\SaveGames\ folder
 1. Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support
 2. Uninstall Manhunt through Steam and delete the main folder Manhunt,location C:\Program Files (x86)\Steam\SteamApps\common\Manhunt
 3. Install the game again,download the applicable fix for your Windows 10 build again copy paste into C:\Program Files (x86)\Steam\SteamApps\common\Manhunt
 4. Run the Manhunt Fix.bat file
 5. Launch the game start it up play a bit,exit
 6. Quit the game
 7. Find this folder location User\Documents\Manhunt User Files\SaveGames\ drop your previous saved games there.

That's it,you are good to go,enjoy the game.

All the credit goes to the creators of the original Manhunt fix patch and the d3d8.dll wrapper find them somewhere here in Steam threads,also additional credit goes to the creator of WideScreen Patch ThirteenAG and crosire for creating the FPS limit wrapper.I just combined everything that worked for me,hopefully will work for you as well and you will avoid the headache with workarounds.NB added wine-based wrapper for Windows 10 2004 build support. 

Cheers! #gimalaji_blake
