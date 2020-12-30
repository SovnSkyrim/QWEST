# Project: QWEST

- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Graphical Settings](#graphical-settings)
    - [Getting an ENB](#getting-an-enb)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Performance stuff](#Performance-stuff)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

Project: QWEST was born after a few friends were talking about how some of their friends couldn't enjoy cool quests in modded Skyrim, even with Wabbajack, due to the hardware requirements. This list has very few graphical enhancements which can be removed if you find you're struggling to run it.

I chose mods that overhaul almost all of the vanilla quests, added some major mods such as Legacy of the Dragonborn, Interesting NPC's, Wyrmstooth and the Forgotten city, and also overhauled the animations a bit. You'll also find new music, new armors and weapons that are linked to LotD and vanilla enhancing weathers and lighting.

If you can run vanilla Skyrim, you should be able to run this.

It is a fork of the amazing SME/FT list; if you want to build your own list check it out [here](https://github.com/EzioTheDeadPoet/SME-FT-)!

The name and picture are a reference to the amazing and wholesome webcomic Quest Sprout comic available on [swordscomic.com](https://swordscomic.com), their official Twitter is [here](https://twitter.com/swordscomic).

## Installation
### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Library

If you have your steam library in program files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133)

If you ever used Vortex to mod Skyrim SE, using the Shredder becomes a critically important step, as Vortex will conflict heavily with any Wabbajack installation, so backup your stuff or shred it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the .Wabbajack from the #links channel in my discord. If you dont have it here's a link: https://discord.gg/ZgjVrXp

Download the release to a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Load _Project: QWEST!.wabbajack file_ from Disk (it'll be in your downloads)
3. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "QWEST!".
4. Select the created folder in 3. as your installation folder.
5. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish.
6. Select the created folder in 5. as your downloads folder.
7. Click the Go/Begin button.
8. Wait for Wabbajack to finish.

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

#### Graphical Settings

On a Ryzen 5 2400G paired with a GTX 950 2GB VRAM and 24GB RAM (never used more than 14GB, so 8GB RAM should be fine, **WHEN** installed on an SSD, if you use an HDD 16GB RAM minimum is recommended):
- BethINI(Low)(locked to 60 FPS):
  - Everywhere(where it got tested): 60FPS

- BethINI(Normal)(locked to 60 FPS): 
  - Outdoors: 30-40 FPS (average 40)
  - Cities: 40-60 FPS (average 50)
  - Indoors: 60FPS

- If you have 8GB RAM and **NO SSD** or if it still has frame drops, then I recommend:
  - Disabling:
    - The following mods in MO2 : [Project Clarity](http://prntscr.com/wchkqq)
  - And testing:
    - BethINI(Normal) -> BethINI(Poor) and stopping by the preset that has a playable framerate for you.

#### Getting an ENB

This list is aimed towards very low end PCs, but that doesn't mean ENB isn't an option.

I recommend anyone with a 2GB card to skip this step and test in game, then check afterwards for what's following, ENB is the biggest performance hit in modding (if you don't go nuts with textures which I didn't). For the lucky ones with more than 2GB of VRAM but still low end, I really recommend [The Truth](https://www.nexusmods.com/skyrimspecialedition/mods/9162) which is the best enb in my opinion for how little it impacts FPS.
There is also another option which is ReShade, it's even less heavy but does less, instructions on this option are below The Truth ENB's installation instructions.

To install The Truth ENB, follow these:
- Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.
- Download The Truth ENB from [here](https://www.nexusmods.com/skyrimspecialedition/mods/9162) and copy the contents of the .rar to your game folder.
**Note : Please check that vsync is set to disable in enblocal.ini otherwise you will be stuck compiling shaders**

Now Let's talk about the ReShade option.
ReShade is simpler than ENBs, they generally focus on color correction but if rightly used, they can enhance the game graphics nicely with even lower fps loss, couple that with a SKyrim set on Low and even the weaker gpus can experience more than vanilla Skyrim lighting.
For Skyrim, it's very common for ReShade to be made with a certain ENB in mind, but some exist to be used on top of Vanilla Skyrim. I'll introduce you to 2 of them.
- [BTS - Beautifully Textured Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/25489)
- [Ulver](https://www.nexusmods.com/skyrimspecialedition/mods/40433)

You can have both at the same time in your Skyrim, so if you want to try both you can download them and follow the installation instructions:

- Download the latest ReShade Version from [here](https://reshade.me/)
- Open ReShade.exe, Select SkyrimSE.exe as the game you want to install it to. 
- Select Direct3D 10/11/12 as the rendering API
- Check/Tick every single box until ReShade is installed.
Now we'll go back to the presets downloaded
- Open the ReShade Preset archive and paste it to your game folder.
- When Skyrim launches (Refer to the next step in the readme if lost on this step), press the home button on your keyboard and select the .ini file you just put in your Skyrim Folder as the loaded .ini
- Press home again to close the window.
Know that you can switch any ini at anytime during your gameplay, so if you want to compare between the 2 that I recommend, you can totally do that in game.

## How to start up Project: QWEST!

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
Once the game has loaded. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

#### Game Difficulty
- The difficulty in this game is very vanilla like but still generally harder, if you're used to Legendary you will have a hard time. I suggest playing in Expert or Master and if found too easy, crank it up.

#### A Matter of Time

- Presets :
  - Load User Settings

#### AGO
- Settings
  - Enable/Disable
    - Arrow Wounds (Player) : Disabled
    - Arrow Wounds (NPCs) : Disabled
    - Persistant Arrows : Disabled
    
#### All Geared up Derivative
- Misc. Player :
  - Enable Misc. Item Display : Disabled
  - Require Torso Armor : Enabled
- NPC :
  - Enable Weapons : Enabled
  - Enable Misc. Item Display : Disabled

#### Follower Framework
- System :
  - Load From File 
  
#### Immersive HUD
- Activation
  - Compass Activation
    - Key press toggles : Enabled

#### Growl Werebeasts 
- Features
  - Invulnerable During Transformation: Enabled
- If you want to be a Werebear instead:
  - Immersion : Werebear : Enabled

#### Imperious Racials
- Nothing is really important, you can toggle stuff depending on your Race tho!
Reminder that you can't switch race/sex using Showracemenu because of such a mod!

#### LOTD Settings
- LOTD Settings → General → Shippment Crate Locations : 
  - Carriages: Enabled
  - Inns: Enabled
  - Player Houses: Enabled

#### moreHUD
- Presets
  - Save Settings with FISS
    - Load User Settings? : GO
    
#### Simple Horse
- Call Horse Key : change it if you want to! (I leave it on default)

#### SkyUI
- General → Item List :
  - Font Size : Small
  - Category Icon Theme : CELTIC
- Advanced → SWF Version Checking : 
  - Map Menu : Disabled
  - Favorites Menu : Disabled
  - Inventory Menu : Disabled
  - Barter Menu : Disabled
  - Container Menu : Disabled
  - Crafting Menu : Disabled

#### SmoothCam  -for 3rd person players-
- Presets
  - Load Preset
    There are 2 presets available for your to use, I personally prefer the Modern one but some prefer EasyEase's, try both and see which you prefer!
    
#### The Ultimate Dodge Mod  
 - Configure your dodge key and your sneak key! As written, it is your vanilla sneak key. This step is very important
 A Keybinding example would be:
 - Vanilla Sneak key within Options: C
 - Sneak key within TUDM's MCM: Left Control
Now your character will roll/sidestep with C and Sneak with Left Control
I also would recommend to use sidestep (personal preference)

- Npc Settings :
  - NPC Dodge AI: Disabled

#### Thieves Guild Requirements
- Misc Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)
  
#### Timing is Everything
- Extra Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)

#### VioLens
- Load Preset

#### Wildcat
- Disable Injuries: Enabled
- Allow Wildcat to manage difficulty: Enabled

## How to start playing

Simply step up to the statue of mara and choose a start.

## FAQ

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Xanza, Jdsmith inspiring me to make this, y'all are neat.
- Luca for all the testing, feedback and recommendations, you are amazing.
- Althro for being such a resourceful person and helping with the Discord and development a lot.
- Every each of my Patreons for supporting me, and with the Special Folks of my discord, for helping with the development.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the Discord. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU** but you can safely ping me in #unofficial-modlist-support or my own Discord, I'll answer whenever I can.

## Changelog

See [Changelog](https://github.com/SovnSkyrim/QWEST/blob/main/Changelog.md).
