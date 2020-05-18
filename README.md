# ACNH BCAT activation guide
If you're new, please follow this guide step by step to prevent undesirable results, like losing your game progress.

## Index
* [Index](#index)
* [Guide](#guide)
  * [Summery](#summery)
  * [1. Download JKSV and switch-time](#1-download-jksv-and-switch-time)
  * [2. Create a savegame backup](#2-create-a-savegame-backup)
* [Credits](#credits)

## Guide
### Summery
BCATs are needed to activate some special, time limited events in game.  
The guide shows you how to backup your game progress and inject right BCAT files into your game.  
Once you know how it works, you can repeat all steps for each new BCAT coming out.


### 1. Download JKSV and switch-time
Before we begin, we need right tools to backup savegame, restore BCAT and set synced time.
1. Download latest [JKSV](https://github.com/J-D-K/JKSV/releases) version from the [release page](https://github.com/J-D-K/JKSV/releases).  
   The current version is from 4th April, but you should always prefer the latest one.
   
2. To download a file from a GitHub release, first of all expand "Assets", then in the most cases there is an nro file or an archive like a zip. In this case we need only the **JKSV.nro**.  
   ![JKSV-release](resources/tools/JKSV-release.png)
3. The same is for the [switch-time](https://github.com/3096/switch-time/releases) homebrew.
   Download the nro from the latest release.  
    ![switch-time-release](resources/tools/switch-time-release.png)
4. Now copy **JKSV.nro** and **switch-time.nro** to the switch directory on your sd card.  
   I'm using FTP and it looks like this.  
   Root of the sd card:  
   ![sdcard-root](resources/tools/sdcard-root.png)  
   Switch directory:  
   ![switch-directory](resources/tools/switch-directory.png)

### 2. Create a savegame backup
This is the **most important** step! Nobody wants to lose his progress.

1. Open the Homebrew menu and start the JKSV, that we have installed in the first step.
   ![in-hb-menu](resources/JKSV/in-hb-menu.png)
2. Navigate and open **Device Saves**.  
   ![device-saves](resources/JKSV/device-saves.png)
3. Now choose the game you want to backup.
4. ![device-saves-choose-game](resources/JKSV/device-saves-choose-game.png)
5. Create a new savegame backup by choosing New and pressing the A-Button.
   ![device-saves-game](resources/JKSV/device-saves-game.png)
6. You have created a savegame from your game. I recommend you to make a backup copy of this save to your PC and maybe even better to a cloud service like Dropbox, Google Drive etc.
   ![device-saves-new-backup](resources/JKSV/device-saves-new-backup.png)
7. We are done here, if something bad happens, you can always restore this savegame file to restore your progress.

### 3. Create a savegame backup

## Credits
Name | Reason
---- | ---------
Igromanru | This guide and latest BCAT files for International Museum Day and Wedding Season
Eevee | Dumped May Day BCAT 