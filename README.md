A guide on how to install mods in Baldur's Gate 3. This guide mostly focuses on the Steam version, but most steps should work with **GOG** and other versions. There are also instructions on how to use the BG3 Mod Launcher.

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://blog.moddingcommunity.com/how-to-install-mods-for-baldur-gate-3/)

Modding Baldur's Gate 3 can add new spells, companions, visual overhauls, or even QoL improvements.

**WARNING** - Modding is only officially supported in **Baldur's Gate 3 Patch 4 and later**. Mods can break your game after updates, so be sure to always back up your saves before installing anything!

## Table of Contents
- [Requirements](#requirements)
- [Installing BG3 Mod Manager](#installing-bg3-mod-manager)
- [Downloading Mods](#downloading-mods)
- [Locating the Mods Folder](#locating-the-mods-folder)
- [Add Mods to the Manager](#add-mods-to-the-manager)
- [Launch the Game & Test](#launch-the-game--test)
- [Uninstalling Mods](#uninstalling-mods)
- [Fix Load Order Issues (Optional)](#fix-load-order-issues-optional)
- [Notes & Tips](#notes--tips)
   - [Notes for GOG & Non-Steam Versions](#notes-for-gog--non-steam-versions)
- [Conclusion](#conclusion)
- [See Also](#see-also)

## Requirements
* Baldur's Gate 3 installed onto your PC.
* [7-Zip](https://www.7-zip.org/) or a program similar to extract compressed files and archives.
* A basic understanding of navigating folders on Windows and copying/pasting folders and files.
* An Internet connection.

## Installing BG3 Mod Manager
The Baldur's Gate 3 Mod Manager is the easiest way to manage mods.

1. Download BG3 Mod Manager from GitHub [here](https://github.com/LaughingLeader/BG3ModManager).

2. Extract the ZIP file using a program like [7-Zip](https://www.7-zip.org/) and then run `BG3ModManager.exe`.

**WARNING** - Make sure you launch the game at least once beforehand so the necessary folders get generated.

## Downloading Mods
The most popular website to download BG3 mods from is [Nexus Mods](https://nexusmods.com). The following steps goes over the process of downloading mods.

1. Go to [Nexus Mods - Baldur's Gate 3](https://www.nexusmods.com/baldursgate3).
2. Pick and choose which mods you'd like to download.
   - Most mods come in a `.pak` format.
   - Some mods may include additional steps or dependencies. Read their descriptions carefully!

**NOTE** - Mods like *Party Limit Begone*, *Customizer's Compendium*, and *Tav's Hair Salon* are popular beginner mods.

## Locating the Mods Folder
You'll now want to locate the folder to place the mod files in.

On Windows, this is typically the following path.

```
%LocalAppData%\Larian Studios\Baldur's Gate 3\Mods
```

**NOTE** - You can paste that path directly into File Explorer's address bar.  
**NOTE** - If the `Mods` folder doesn't exist, create it manually.

## Add Mods to the Manager
Next, you'll want to add the downloaded mods to the mod manager.

1. Move the downloaded `.pak` files into the `Mods` folder.
2. Open the `BG3ModManager.exe` executable file.
3. On the left, you'll see the available mods. Drag them into the **Active Mods** column on the right.
4. Click the **Save Load Order** button (the disk icon in the top-left).
5. Lastly, click **Export Order to Game** (the gear icon next to it).

This creates or updates the `modsettings.lsx` file that tells the game which mods to load.

## Launch the Game & Test
You can now launch Baldur's Gate 3 normally via Steam or GOG. If everything is set up correctly, your mods should be active.

If a mod isn't working, make sure to check the following.
- Double-check if it requires other dependencies.
- Make sure your mod manager exported the order properly.
- Some mods may require new saves to take effect.

## Uninstalling Mods
If you no longer want to have a mod installed or a mod is causing issues, you can remove the mod using the following steps.

1. Remove the `.pak` file from the `Mods` folder.
2. Remove it from the **Active Mods** list in BG3 Mod Manager.
3. Re-export your load order.

**WARNING** - Some mods may leave behind changes in your save file. For a clean uninstall, use a save from before the mod was installed.

## Fix Load Order Issues (Optional)
Some mods require being loaded before or after others.

- You can manually rearrange mods in the BG3 Mod Manager.
- If you experience crashes or mods not loading, try disabling mods one by one to isolate the issue.

## Notes & Tips
- Always **back up your saves** before modding.
- Some mods may **break after major updates** to the game.
- Whenever you're having an issue, check the mod's **comments** to see if others are having the same issue and if they've provided a potential fix.

### Notes for GOG & Non-Steam Versions
- The install path and Mod Manager usage are the same.
- You still need to launch the game at least once so the `Larian Studios` folder is generated.

## Conclusion
You should have a basic understanding of how to download, install, and manage mods in Baldur's Gate 3.

Whether you're tweaking visuals or changing gameplay mechanics, mods can make your BG3 experience even more enjoyable. Just be careful, and always read the mod pages for extra instructions or updates!

## See Also
- [BG3 Mod Manager](https://github.com/LaughingLeader/BG3ModManager)
- [Nexus Mods - Baldur's Gate 3](https://www.nexusmods.com/baldursgate3)

This guide is a *work-in-progress* and will be updated over time. If you have any feedback, feel free to reach out!

Happy modding!