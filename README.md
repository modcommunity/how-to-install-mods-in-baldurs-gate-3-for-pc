How to install mods in Baldur's Gate 3. This guide mostly focuses on the Steam version of the game, but most steps should work with **GOG** and other versions as well! There are also instructions on how to use the BG3 Mod Launcher.

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://blog.moddingcommunity.com/how-to-install-mods-for-baldur-gate-3/)

Modding Baldur's Gate 3 can add various new spells, companions, visual overhauls, and even QoL improvements to the game. The process of installing mods is relatively straight-forward to most users, but it can be a bit confusing for new modders. This guide will walk you through the steps to get your mods up and running in no time!

## Table of Contents
- [Requirements](#requirements)
- [Downloading & Installing Mods](#downloading--installing-mods)
   - [Baldur's Gate 3 Official Website (Recommended)](#baldurs-gate-3-official-website-recommended)
   - [Nexus Mods](#nexus-mods)
      - [Using Vortex](#using-vortex)
      - [Manually (Advanced)](#manually-advanced)
         - [Locating the Mods Folder](#locating-the-mods-folder)
   - [The BG3 Mod Manager](#the-bg3-mod-manager)
      - [Installing the Mod Manager](#installing-the-mod-manager)
      - [Add Mods Through The Manager](#add-mods-through-the-manager)
- [Launch the Game & Test](#launch-the-game--test)
- [Uninstalling Mods](#uninstalling-mods)
- [Notes](#notes)
   - [Mod Fixer](#mod-fixer)
- [Conclusion](#conclusion)
- [See Also](#see-also)

## Requirements
This guide is intended for users running **Windows**, but you should be able to get this working for other operating systems like Linux by using tools like [Wine](https://www.winehq.org/) or [Proton](https://github.com/ValveSoftware/Proton).

* Baldur's Gate 3 installed on your PC.
* [7-Zip](https://www.7-zip.org/) or a program similar to extract compressed files and archives.
* A basic understanding of navigating, copying, and pasting folders and files on your operating system.

## Downloading & Installing Mods
The most popular websites to download BG3 mods from are [Baldur's Gate 3 Official Website](https://baldursgate3.game/mods#/) and [Nexus Mods](https://nexusmods.com).

### Baldur's Gate 3 Official Website (Recommended)
BG3's official mod website is a trending source for mods. It is recommended since it'll **automatically** download and update mods for you when you launch the game.

1. Go to Baldur's Gate 3 [Official Website](https://baldursgate3.game/mods#/).
![BG3 Official Website](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/bg3_off-site.png)
2. Sign into the website if necessary.
   * In order to subscribe to mods, you need to have an account and be signed in.
2. Browse and select the mods you'd like to download.
3. Click the **Subscribe** button.
![BG3 Subscribe Button](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/bg3_off-sub.png)
4. Launch or restart the game.
   * The mod will now be downloaded and updated automatically when you launch the game.

### Nexus Mods
[Nexus Mods](https://nexusmods.com) is one of the most popular websites for mods and has a large variety of mods for Baldur's Gate 3. While using the BG3 official website for mods is recommended, you can also find mods on Nexus Mods that aren't on the official website.

There are two ways to download and install mods through Nexus Mods; the manual way and the automatic way using [Vortex](https://www.nexusmods.com/vortex), which is Nexus Mods' official mod manager. It is recommended to use Vortex, but some mods may not support it.

#### Using Vortex
1. Download and install Vortex from the Nexus Mods website [here](https://www.nexusmods.com/site/mods/1).
![Vortex Download Button](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/nm_vortex-dl.png)
2. Open Vortex and log in using your Nexus Mods account if necessary.
3. Go to the mod's page on Nexus Mods and click the **Mod Manager Download** button.
![Nexus Mods Mod Manager Download Button](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/nm_downloads.png)
4. Vortex should automatically detect the download and prompt you to install the mod.
   * You may receive a pop-up from your web browser asking if it's okay for Vortex to open. Click **Open Vortex** or the equivalent option in your browser!
5. After installing the mod, make sure to enable it in Vortex, adjust your mod load order if necessary, and finally restart your game for the changes to take effect.

#### Manually (Advanced)
Some mods don't support Vortex, so you may need to download and install them manually (or you just prefer doing it that way).

1. Go to the mod's page on Nexus Mods.
2. Click the **Files** tab and download the mod's files.
3. Download and extract the mod's files using a program like [7-Zip](https://www.7-zip.org/).
4. Place the extracted `.pak` files into the `Mods` folder (see next section).

##### Locating the Mods Folder
The `Mods` folder is where you need to place the downloaded `.pak` files for the game to load them. The path to the `Mods` folder is as follows:

```
%LocalAppData%\Larian Studios\Baldur's Gate 3\Mods
```

**NOTE #1** - You can paste that path directly into File Explorer's address bar.  

**NOTE #2** - If the `Mods` folder doesn't exist, create it manually.

### The BG3 Mod Manager
The Baldur's Gate 3 Mod Manager makes it easy to install and manage mods. While it isn't *required* when installing mods manually, it is highly recommended since it provides a user-friendly interface to manage your mods and their load order.

#### Installing the Mod Manager
1. Download the BG3 Mod Manager from GitHub [here](https://github.com/LaughingLeader/BG3ModManager).
   * The tool's latest releases may be found [here](https://github.com/LaughingLeader/BG3ModManager/releases).

![BG3 Mod Manager GitHub](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/mm_releases.png)

2. Extract the ZIP file using a program like [7-Zip](https://www.7-zip.org/) and then run `BG3ModManager.exe`.

After extracting the ZIP contents, the extracted file/folders list should look something like below depending on your OS.

![File Listing](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/mm_contents.png)

3. Run the executable. Afterwards, ensure you have the **Game Data** and **Game Executable** path settings set inside of **Settings** -> **Preferences**.
   * If these settings are changed, you will need to restart the mod manager for it to take effect.
   * **Common Game Paths on Steam**:
      * **Data Path**: `C:/Program Files (x86)/Steam/steamapps/common/Baldurs Gate 3/Data`
      * **Executable Path**: ` C:/Program Files (x86)/Steam/steamapps/common/Baldurs Gate 3/bin/bg3.exe`

![BG3 Mod Manager Game Data Path](https://github.com/modcommunity/how-to-install-mods-in-baldurs-gate-3-for-pc/raw/main/images/mm_gamedata.png)

**NOTE #2** - After arranging your mod load order, make sure to click the **Export to Game** button to save your load order to the `modsettings.lsx` file. Load order changes require a *game restart*.

#### Add Mods Through The Manager
There are two ways to install mods through the BG3 Mod Manager. You can either import the ZIP file you downloaded from Nexus Mods or the official website, or you can add the `.pak` file to your mods folder.

1. Import the mod's ZIP file or add the `.pak` file to your `Mods` folder.
   * If you're importing the ZIP file, open the BG3 Mod Manager, click the **File** drop-down menu, click **Import Mod**, and select the ZIP file you downloaded.
2. Once the mod(s) are imported, they will be inactive by default. To activate them, drag them from the **Inactive Mods** list to the **Active Mods** list (on the left side).
3. Apply the changes and restart the game for the changes to take effect.

## Launch the Game & Test
You can now launch Baldur's Gate 3 normally via Steam or GOG. If everything is set up correctly, your mods should be active.

If a mod isn't working, make sure to check the following.
*  Double-check if the mods you've installed require any additional dependencies.
*  Make sure your mod manager exported the order properly.

## Uninstalling Mods
If you no longer want to have a mod installed or a mod is causing issues, you can remove the mod using the following steps.

1. Remove the `.pak` file from the `Mods` folder.
2. Remove it from the **Active Mods** list in BG3 Mod Manager (or deactivate the mod).
3. Re-export your load order.

**WARNING** - Some mods may leave behind changes in your save file. For a clean uninstall, use a save from before the mod was installed.

## Notes
- Always **back up your saves and data files** before modding.
- Some mods may **break after major updates** to the game. Though most mods are usually fine and if not, are updated by the mod author quite quickly (depending on the mod, of course).
- Whenever you're having an issue, check the mod's **comments** to see if others are having the same issue and if they've provided a potential fix.

### Mod Fixer
If you're running BG3 **patch 6 or below**, you may need to download and install the [BG3 Mod Fixer](https://www.nexusmods.com/baldursgate3/mods/141) to get mods working properly.

This mod forces the story to recompile, allowing certain or all mods to work with the full release of the game.

Install this mod by simply placing the `.pak` file into your `Mods` folder as explained above. You can also import the ZIP file through the BG3 Mod Manager.

## Conclusion
You should have a basic understanding of how to download, install, and manage mods in Baldur's Gate 3.

Whether you're tweaking visuals or changing gameplay mechanics, mods can make your BG3 experience even more enjoyable. Just be careful, and always read the mod pages for extra instructions or updates!

## See Also
- [BG3 Official Website (Mods)](https://baldursgate3.game/mods#/)
- [BG3 Mod Manager](https://github.com/LaughingLeader/BG3ModManager)
- [Nexus Mods - Baldur's Gate 3](https://www.nexusmods.com/baldursgate3)

This guide is a *work-in-progress* and will be updated over time. If you have any feedback, feel free to reach out!

Join our [Discord server](https://discord.moddingcommunity.com) if you have any questions or you're looking for a modding community to engage with!

Happy modding!