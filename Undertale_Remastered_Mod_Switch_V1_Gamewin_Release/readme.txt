For use with Delta Patcher 3.0.1: https://www.romhacking.net/utilities/704/


Project Github: https://github.com/EZonTheEyes/undertale-remastered-NS

Port of the Undertale Remastered Mod to the Nintendo Switch by patching the game.win file. 

Original Mod created by Michael_King for use with the PC Release of Undertale: https://www.moddb.com/mods/na29410

Port by EZonTheEyes: https://github.com/EZonTheEyes, https://allmylinks.com/ezontheeyes

Made with Undertale Mod Tools: https://github.com/krzys-h/UndertaleModTool



Requirements:
- Hacked Switch running CFW (See Hekate, Atmosphere, Ect.) 
(Hekate: https://github.com/CTCaer/hekate/releases) 
(Atmosphere: https://github.com/Atmosphere-NX/Atmosphere/releases) 

- The nxdumptool homebrew application
(NXDumptool: https://github.com/DarkMatterCore/nxdumptool/releases)

- PC Capabble of running Delta Patcher 
(https://www.romhacking.net/utilities/704/)

- A LEGITIMATE, LEGAL copy of Undertale for the Nintendo Switch
(https://www.nintendo.com/us/store/products/undertale-switch/)


INSTALLATIONS:



---Atmosphere / Switch CFW---


Step 1:
With Undertale installed on your switch, run the hbmenu (hold right should while launching any game from the switches home menu), and navigate to your nxdumptool homebrew, run it.

Step 2:
Select 'Dump installed SD card / emmc content', navigate to your Undertale title

Step 3: 
Select 'RomFS options', turn 'Save data to CFW directory (LayeredFS):' to Yes, leave 'Use update/DLC' to 'No', select 'RomFS section data dump'

Step 4:
Your romfs dump will be located in 
/sd/atmosphere/content/010080B00AD66000/romfs

We only need the game.win file, Copy this to your PC

Step 5:
Run the Delta Patcher excecutable, direct the 'original file' to your coppied game.win from the romfs dump.

Set the 'xdelta patch' to the .xdelta included in this archive. 

Select 'Patch', you should see Success

Step 6: 
Copy this newly modified game.win back into the '/sd/atmosphere/content/010080B00AD66000/romfs' folder

You will be asked if you want to replace the existing one with the modified one, select 'Yes'

Final:

You can now play Undertale on your switch, Enjoy!


---Yuzu (Desktop/Android)---


Step 1:
On a PC, Right click your copy of Undertale, select 'Dump romfs', select 'full', Yuzu will automatically open the dump folder (Windows:) 'C:\Users\UserName\AppData\Roaming\yuzu\load\010080B00AD66000'

take note of this directory & the game.win location

Step 2:
Run the Delta Patcher excecutable, direct the 'original file' to your dumped game.win from the romfs dump.

Set the 'xdelta patch' to the .xdelta included in this archive. 

Select 'Patch', you should see Success

Step 3:
Copy this romfs dump folder to your Undertale Mods folder location,

Right Click and Select 'Open Mod Data Location' on Undertale, (Windows): C:\Users\UserName\AppData\Roaming\yuzu\load\010080B00AD66000

Place the modified romfs in this folder

Step 4 **(ANDROID ONLY):**

Copy the mod data location folder (\yuzu\load\010080B00AD66000)
 
to your Yuzu android files, located at

\Internal storage\Android\data\org.yuzu.yuzu_emu\files\load\010080B00AD66000

Final:

You can now play Undertale Remastered in Yuzu, Enjoy!


---Ryujinx (Desktop)--- 


Step 1:
On a PC, Right Click your copy of Undertale, Select 'Extract', select romfs. Choose a dump location for your folder.

take note of this directory & the game.win location

Step 2. 
Run the Delta Patcher excecutable, direct the 'original file' to your dumped game.win from the romfs dump.

Set the 'xdelta patch' to the .xdelta included in this archive. 

Select 'Patch', you should see Success

Step 3:
In Ryujinx, right click Undertale, click open mods directory, create a new folder named 'Remaster', place romfs within this folder '(Windows:)‘C:\Users\Name\AppData\Roaming\Ryujinx\mods\contents\010080b00ad66000’'

Final:

You can now play Undertale Remastered in Ryujnix, Enjoy!


--- YANU (ex. Skyline, Strato) ---
Step 1:
On your hacked switch, run hbmenu by holding right shoulder as you launch any game on your home screen, select NXDumpTool

Step 2: 
Select Undertale, select 'Nintendo Submission Package (NSP) dump', select 'Dump base application NSP', set 'Remove console specific data', select 'Start NSP dump proccess'

Your dump will be located in /sd/switch/NXDumptool/NSP/ , Copy this off your switch to your PC, take note of the copy directory and location

Step 3:
Run yanu.exe, navigate to unpack, select the NSP you've dumped under Base File, select 'unpack'. You should see Success.

Your romfs, NCA, and exefs dumps will be located at \yanu\base.obROU3 

Take note of this romfs directory & the game.win file location

Step 4:
Run the Delta Patcher excecutable, direct the 'original file' to your dumped game.win from the romfs dump.

Set the 'xdelta patch' to the .xdelta included in this archive. 

Select 'Patch', you should see Success

Step 5:
In yanu, select 'Pack',
 
For the Control NCA:
Select the file from basedata that's 118kb and begins with 7, other .nca files from here may work aswell.

For TitleID:
Type "010080B00AD66000"

For RomFS folder:
Select \yanu\base.obROU3\romfs

For ExeFS folder:
Select \yanu\base.obROU3\exefs

Select 'Pack', you should see Success. Your repacked, modified NSP file will be in the \yanu\ folder.

Final:

You have now repacked Undertale Remastered to an NSP, Enjoy!
