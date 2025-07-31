A guide on how to **install mods** in **Minecraft** (Java Edition) for **singleplayer and multiplayer** gameplay. We’ll also cover popular mod loaders like [Forge](https://files.minecraftforge.net/) and [Fabric](https://fabricmc.net/), explain how to manage mods, and share trusted websites to download mods from.

This guide is primarily for **Windows users**, but Linux and macOS users can follow similar steps with minor adjustments.

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://blog.moddingcommunity.com/how-to-download-install-mods-in-minecraft/)

Minecraft is one of the most heavily modded games of all time. Mods can add entirely new dimensions, overhaul game mechanics, and introduce simple QoL improvements. This guide should give you a basic understanding on how to download and install mods on Minecraft!

## Table Of Contents
* [Requirements](#requirements)
* [Game Version Notes & Folder Locations](#game-version-notes--folder-locations)
    * [Minecraft Mods Folder](#minecraft-mods-folder)
* [Backup Your Game Files!](#backup-your-game-files)
* [Choosing A Mod Loader](#choosing-a-mod-loader)
* [Installing Your Mod Loader](#installing-your-mod-loader)
    * [Installing Forge](#installing-forge)
    * [Installing Fabric](#installing-fabric)
* [Where To Download Mods](#where-to-download-mods)
* [Downloading & Installing Mods](#downloading--installing-mods)
* [Managing Mods With Mod Managers](#managing-mods-with-mod-managers)
* [Common Issues & Troubleshooting](#common-issues--troubleshooting)
    * [Game Crashes on Launch](#game-crashes-on-launch)
    * [Incompatible Mods](#incompatible-mods)
    * [Performance Drops](#performance-drops)
* [Conclusion](#conclusion)
* [See Also](#see-also)

## Requirements
* **Minecraft: Java Edition** installed on your PC (you can also use others like Bedrock, but steps may differ)
* A [Minecraft Launcher](https://www.minecraft.net/en-us/download)
* [Java 17 or higher](https://www.java.com/en/download/manual.jsp) (required for modern versions).
* Archive extraction software like [7-Zip](https://www.7-zip.org/)
* An Internet connection and basic undestanding of how to navigate and copy folders and files.

## Game Version Notes & Folder Locations
Many mods are version-specific, meaning a mod for **Minecraft 1.20.1** may not work with **1.20.2**.

Always check which version of Minecraft your chosen mods require, and install the appropriate loader.

### Minecraft Mods Folder
Depending on the operating system (OS) you're running, the path to the folder that most mod loaders run mods from differs.

Here are common paths to the main Minecraft folder for mods depending on your OS.

* **Windows**: `%appdata%\.minecraft\mods`
* **MacOS**: ` ~/Library/Application Support/minecraft/mods`
* **Linux**: `~/.minecraft/mods`

Keep note of these folder location(s) above for your OS! You also may need to create the `mods` sub-folder if your mod loader uses the path above.

## Backup Your Game Files!
Before installing mods, we strongly recommend **backing up** your Minecraft worlds. Mods can corrupt saves or cause crashes.

1. Open the Minecraft folder (path above):
2. Copy the **saves** folder to another location on your PC (e.g. your desktop).

## Choosing A Mod Loader
There are multiple mod loaders that can be used in Minecraft. Here are a few of them that are popular.

* [**Forge**](https://files.minecraftforge.net/net/minecraftforge/forge/) - Most widely supported by mod developers.
* [**Fabric**](https://fabricmc.net/) - Lightweight, faster updates, but fewer mods compared to Forge.
* [**Quilt**](https://quiltmc.org/) - A newer alternative that’s compatible with most Fabric mods.

## Installing Your Mod Loader
After choosing your mod loader, you'll want to download the tool from the mod loader's website. Websites for popular mod loaders are linked above.

We've also included instructions on downloading and installing Forge and Fabric.

**NOTE** - Many Fabric mods require the [Fabric API](https://modrinth.com/mod/fabric-api)! If you're using Fabric, we recommend downloading and installing the Fabric API as well!

### Installing Forge
1. Head over the Forge downloads page [here](https://files.minecraftforge.net/net/minecraftforge/forge/).
2. Download the **installer** for your Minecraft version.
3. Run the installer and select **Install client**.
4. Launch the Minecraft Launcher and select the **Forge profile**.

### Installing Fabric
1. Visit Fabric's website [here](https://fabricmc.net/use/installer/).
2. Download and run the Fabric Installer.
3. Choose your Minecraft version and click **Install**.
4. Launch the Minecraft Launcher and pick the **Fabric profile**.

## Where To Download Mods
There are *many* websites that host mods for Minecraft. Here is a list of the more common and trusted websites used.

* [CurseForge](https://www.curseforge.com/minecraft/mc-mods)
* [Modrinth](https://modrinth.com/mods)
* [Planet Minecraft](https://www.planetminecraft.com/resources/mods/)
* [Minecraft Forum](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods)
* [Nexus Mods](https://www.nexusmods.com/games/minecraft)

**NOTE** - We recommend reading the mod's description along with the user comments before downloading mods to ensure it's safe and you haven't missed any additional steps or dependencies.

## Downloading & Installing Mods
Downloading and installing mods depends on the mod loader and website you're using.

When finding mods from the websites mentioned earlier, many mods contain specific versions for mod loaders like Forge and Fabric. Make sure to select the correct version depending on your Minecraft version and mod loader!

1. Download your mod’s `.jar` file from a trusted source.
2. Navigate to the`%appdata%\.minecraft\mods` folder.
   * If the **mods** folder doesn’t exist, create it!
3. Place the mod's `.jar` file into the **mods** folder.
4. Launch Minecraft with the Forge or Fabric profile.

Your mod should now be active!

## Managing Mods With Mod Managers
A dedicated mod manager can simplify the process of downloading, installing, and updating mods and their dependencies. It also helps manage mod packs as well!

Here are some popular mod managers!

* [CurseForge Launcher](https://www.curseforge.com/download/app)
* [Prism Launcher](https://prismlauncher.org/)
* [MultiMC](https://multimc.org/)

## Common Issues & Troubleshooting
### Game Crashes on Launch
* Make sure the mod version matches your Minecraft and Forge/Fabric version.
* Check for required libraries (e.g. Fabric API or Architectury).
* Disable or remove mods one-by-one or in batches to narrow what mod is causing issues.

### Incompatible Mods
* Some mods conflict. Remove mods one by one to find the culprit.
* Use the latest version of the mod loader.

### Performance Drops
* Install [Sodium](https://modrinth.com/mod/sodium) or [OptiFine](https://optifine.net/) which help optimize Minecraft (just to note, OptiFine is less Fabric-compatible generally from our experience).
* Use performance mod packs like **Fabulously Optimized**.

## Conclusion
By now, you should have a basic understanding of downloadind and installing mods along with how to use mod loaders like Forge and Fabric!

With thousands of mods available, you can transform your Minecraft experience into anything you imagine!

## See Also
* [Forge Downloads](https://files.minecraftforge.net/)
* [Fabric Installer](https://fabricmc.net/use/installer/)
* [Prism Launcher](https://prismlauncher.org/)
* [Minecraft Modding Subreddit](https://www.reddit.com/r/MinecraftModding/)

This guide will be updated over time! If you see any improvements that can be made, please reach out!

Happy modding!