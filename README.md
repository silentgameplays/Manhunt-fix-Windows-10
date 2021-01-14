# Manhunt-fix-Windows-10
Manhunt-Fix-Windows-10-for-all-builds

How to get Manhunt working on Windows 10:
# NB!The latest fix without any folders is here it does not require previous ones and works across builds moved all the old fixes to other repo!

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

1. Install through Steam

# NB!Currently based on user feedback there are 2 more folders in this fix one is for Intel Integrated GPU's another is for older Windows 10 1909-1903 builds

2. Download and extract all the files from this fix corresponding to your Windows 10 build.

3. Copy/Paste from the required folder into the Manhunt Directory C:\Program Files (x86)\Steam\SteamApps\common\Manhunt

4. Run the Manhunt Fix.bat file

5. Disabling audio sound loops completely by removing audio:
Manually:
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\PORN folder and find the file named PORN.RIB and change it to something like p0rn.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB
- Go to C:\Program Files (x86)\Steam\steamapps\common\Manhunt\audio\PC\SCRIPTED\CRAPPER folder and find the file named CRAPPER.RIB and change it to something like cr@pper.RIB

# NB! For Dual GPU laptops ONLY!:
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

That's it,you are good to go,enjoy the game.

# All the credit goes to the creators of the original Manhunt fix patch AJ Collins,credit goes to ThirteenAG for .ini FPS limiter visit his site for more goodness:https://thirteenag.github.io/wfp 
# Combination of fixes,testing,manual configuration is done by gimalaji_blake. Hopefully will work for everyone and will save time looking for workarounds.
# NB added wine-based wrappers for Windows 10 2004 build support. 

# Cheers! 
# gimalaji_blake
