# Bonelab Mods

This is a tutorial on installing Bonelab mods on both PCVR and Quest standalone. 

>[!IMPORTANT]
>Mandatory Mods You MUST download are listed below:
> - Thunderstore Mod Assistant[^1]
> - BoneLib[^2]

***

# Standalone Quest
>[!NOTE]
> If you already have SideQuest, go to [This Link](#3-downloading-lemonloader), which will skip the part where you need to download SideQuest.

## 1. Enabling Meta Quest Developer Mode
First, go to [Meta Verify Dashboard](https://developers.meta.com/horizon/manage/verify/) and add a phone Number, Credit card, or 2FA. Once done, you should be able to enable developer mode.

## 2. Downloading SideQuest
First, you want to download the [SideQuest](https://github.com/SideQuestVR/SideQuest/releases/latest).exe file inside the latest release. Once the SideQuest-Setup-X.X.X-x64-win.exe has downloaded, open it to start the installation process. Once that is done, make sure Developer Mode is on, then connect your headset to your PC and make sure the **green** circle appears at the top left. If it has an **orange** circle, hover over it with your mouse to see the error.

## 3. Downloading LemonLoader
Go to [This Link](https://github.com/LemonLoader/MelonLoader/releases/latest), which is on Version 0.6.5.1 as of the writing date, which goes to the latest LemonLoader download. Make sure you download lemoninstaller-win-x64.zip. This is the Download File that uses LemonLoader.

## 4. Backing Up Game Files
>[!CAUTION]
> This step is very important before doing step 5. Make sure to do these steps properly, or you MAY lose your save file.

Go to SideQuest and click on the folder icon at the top left to open your VR's Local Storage. Go to:
```
Android --> data --> com.StressLevelZero.BONELAB --> files
```
Back up your 'Mods' folder and 'Saves' folder to your PC. You should now have saved your BONELAB save file to your PC, since it does not save to the Meta Cloud.

If you have access to your Quest Storage from File Explorer, then do the same thing by going to this path in File Explorer:
```
This PC\Quest #\Internal shared storage\Android\data\com.StressLevelZero.BONELAB\files
```

>[!TIP]
> You can access your VR storage directly from File Explorer by doing the following:
> ```
> 1. Click on the wrench at the top right of SideQuest.
> 2. Scroll down to the 'Experimental & Miscellaneous' section.
> 3. Enable 'MTP (Media Transfer Protocol).
> ```

## 5. Installing LemonLoader into Bonelab
Once you have backed up your save files and mods, you don't necessarily need to download your mods; you can open MelonLoader.Installer.App.exe. This will show a menu of ADB Devices. Make sure you select your Quest 2/3/3s and press 'Use This Device'. This will show your games that can be patched and unpatched; make sure you select BONELAB (it won't say patched for you).
<img width="385" height="94" alt="image" src="https://github.com/user-attachments/assets/3947e87b-bd2f-4552-82cc-e26ca0dea3cf" />
It will show a menu like this; make sure to press "Patch". Not any of the grey buttons; just press "Patch". This will start the patching process. Once it's done, it may say something like this:
```
### Unable to restore
Lemon is unable to restore app data. Do you want to open the folder containing the backup now? It will not be deleted after patching is complete.
```
This is just saying that it couldn't back up your saves and mods folder. If you already did [Step 4](#4-backing-up-save-files), you can go ahead and press No. Otherwise, press Yes and back the Save folder and Mods folder now.

To finish installation, go ahead and open BoneLab. When you open BoneLab, it will say something like this image below:
<img width="341" height="342" alt="image" src="https://github.com/user-attachments/assets/f9c91d12-f482-4a43-ac0e-628f10c1e90f" />

>[!CAUTION]
> Make sure you always press ***"Open App"*** and never "Restore". If you do press "Restore", it will reinstall the game, deleting your save file and your mods folder too.

Wait until you have loaded and bonelab has opened. You do not need to wait for the shader cache to download; make sure to close Bonelab once you reach shader cache installation.

## 6. Reinstalling Necessary Mods
Go ahead and take BoneLib[^2] and add it to this folder:

[^1]: Thunderstore Mod Assistant is Optional for both Quest Standalone and PCVR, helping to download mods in-game. After downloading mods in-game, you will have to restart your game to install the mods on your device fully. Link Here: https://thunderstore.io/c/bonelab/p/notnotnotswipez/ThunderstoreModAssistant/
[^2]: BoneLib is a Library for all mods, mandatory for installation. Link Here: https://thunderstore.io/c/bonelab/p/bonelib/BoneLib/
