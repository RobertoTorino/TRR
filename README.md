# TRR - Tekken Revolution Reborn

> ## Tekken Revolution (鉄拳レボリューション) an online only free-to-play fighting game was first released in June 2013 for the PlayStation 3. Sadly on March 20th, 2017 when the game was already pulled from the PlayStation Store connection with the hosting servers was ended making the game unplayable.

### Fixing memory allocation
RPCS3 uses a lot of memory regions and sometimes gives you an error about allocating memory.
In your Windows search menu type msconfig and open it, then click on the Boot tab.
Click on Advanced Options and uncheck Maximum memory.
Checkmark Number of processors and set it to the highest number. Click OK Apply then restart your PC.

### RPCS3
Use the RPCS3 version included in this package: rpcs3-v0.0.23-13837-fddb6a31_win64. Installing is pretty straight forward. Unpack the archive, run the exe, confirm the popups, optionally you can disable the search for updates option in settings/GUI/Check for updates on startup.
First install the PlayStation3 Firmware, since this game was released for version 4.40, I added that version to the package.

### RPCS3 settings
Run the emulator, click on Configuration and select GPU.
Set the Renderer to Vulkan.
Set the resolution according to your monitor’s native resolution.
Make sure VSync is unchecked.

### The game
Install Tekken Revolution, just drag and drop the files on the RPCS3 GUI.
When applying the updates in RPCS3 do them one by one, also just drag and drop.
Going from update 1.01 through 1.05 in that order.
Remove black borders: copy the custom_configs folder (which contains config_NPEB01406) to the config directory of RPCS3.
Run the game, it may take a few reboots to finally get it going, but it will eventually work.

### CheatEngine for RPCS3
Open Cheat Engine and click on the Edit option to open the Edit menu.
Select the Settings option, and click on Extra Custom Types.
Enable all three options there: 2 Byte Big Endian, 4 Byte Big Endian and Float Big Endian.
Still in settings make sure All Custom Types and MEM_MAPPED options are checked.
Close CheatEngine.

### Start CheatEngine
Double-click the CheatEngine table: rpcs3-NPEB01406.CT to open CheatEngine again.
On the right side under Memory Scan Options make sure All is selected.

For all the Cheat Engine options follow Dennis's guide.

```shell
Guide was NOT made by me, all credits to Dennis Stanistan.
I copied his guide in text document for offline use to preserve his work.

Be sure to read through the entire guide thoroughly.
Best regards, Dread.
```

> ### EXTRAS
> Added the PlayStation3 Firmware update PUP for version 4.40 and 4.91.             
> Added a DDS viewer to be able to read the PlayStation3 Manuals: Windows_DDS_Texture_Viewer_v089b.             
> Added winexp to the package (winexpsrc_2.7z), this a tool to manipulate application windows, sometimes an application can not run full screen, this tool can fix that, full description in the archive. It can also destroy the window in case an application hangs and can not be stopped by task manager, it basically kills the process then.              
> Added the original website for preservation.             
> Added CheatEngine 7.5 without bloatware to make it a complete package, just make a shortcut for one of the cheatEngine .exe files.            
> Added a sample video to show what is possible.            

---

**Refreshed the instructions and the package in July 2024.**

