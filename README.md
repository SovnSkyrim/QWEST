# QWEST!

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
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
    - [Getting an ENB](#getting-an-enb)
    - [Profiles](#Profiles)
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

QWEST! was born after a few friends were talking about how some of their friends couldn't enjoy cool quests in modded Skyrim, even with Wabbajack, due to the hardware requirements. This list has very few graphical enhancements which can be removed if you find you're struggling to run it.

I chose mods that overhaul almost all of the vanilla quests, added some major mods such as Legacy of the Dragonborn, Interesting NPC's, Wyrmstooth and the Forgotten city, and also overhauled the animations a bit. You'll also find new music, new armors and weapons that are linked to LotD and vanilla enhancing weathers and lighting. You even have the choice between EnaiRim and SimonRim with the 2 available Profiles!

If you can run vanilla Skyrim, you should be able to run this.

If you have any questions regarding the list, you're free to ask in the [Wabbajack Discord](https://discord.gg/wabbajack) or [my own personal server](https://discord.gg/ZgjVrXp).

It is a fork of the amazing SME/FT list; if you want to build your own list check it out [here](https://github.com/EzioTheDeadPoet/SME-FT-)!

The name and picture are a reference to the amazing and wholesome Quest Sprout comic available on [swordscomic.com](https://swordscomic.com). Their official Twitter is [here](https://twitter.com/swordscomic).

# READING THIS README IN ITS ENTIRETY IS REQUIRED FOR THE LIST TO WORK. IT WILL NOT WORK IF YOU DON'T READ. THIS ISN'T ROCKET SCIENCE SO BE PATIENT AND READ CAREFULLY. THE README DOESN'T END AT "HOW TO START UP THE LIST". I am going to answer "readme" to any question answered in this document - you have been warned. THIS LIST MASSIVELY CHANGES THE GAME, AND I'VE PUT MY OWN TWEAKS INTO IT. YOU WOULDNT HAVE THE SAME EXPERIENCE IF YOU MODDED THE GAME YOURSELF WITH THE SAME MODS; THUS, DO NOT REPORT ANY BUG/ERROR/ISSUE/PROBLEM TO MOD AUTHORS BUT ONLY TO ME THROUGH WABBAJACK'S OR MY DISCORD.

# Noteworthy Mods and what gameplay to expect.

Depending on the choice of profile, you will have a very different approach to the list. [EnaiRim](https://www.nexusmods.com/skyrimspecialedition/users/3959191) will make you and your enemies stronger overall while [SimonRim](https://www.nexusmods.com/skyrimspecialedition/users/67410746) will remain simple and closer to Vanilla.
If you're unfamiliar with those overhauls, you should read their modpages as the changes are at the base of everything.

## Survival
If you chose to not make any modifications and go with the survival mods, you will have way more micromanagement to do.

1. You will need to eat and sleep to survive. 
2. You will need to survive the cold or your stamina will drain and you'll die. 
3. You will need to clean yourself or you'll have very bad prices and everyone will smell you when trying to sneak.

You should definitely check the Skill Trees within your campfire on top of the vanilla skill trees. Your arrows will have weight and you will need to sleep to level up your Character. If you're unfamiliar with the survival mods, have a read of [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667), [Dirt and Blood](https://www.nexusmods.com/skyrimspecialedition/mods/40746), [Keep it Clean](https://www.nexusmods.com/skyrimspecialedition/mods/17846), and [SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/39414).

Fast travel is disabled in multiple of these mods so there's no easy way to reactivate it at all times but there's an alternative: [Horizon Zero Dawn Fast Travel](https://www.nexusmods.com/skyrimspecialedition/mods/35793).

Lastly, all profiles have way better horse management thanks to [Convenient Horses](https://www.nexusmods.com/skyrimspecialedition/mods/9519)!

## Added Quests

[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/30980) forms the core spine of the list. QWEST! is the list with the most addons for it, but many new lands aren't integrated with the museum. These include [Unslaad](https://www.nexusmods.com/skyrimspecialedition/mods/11789), [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423), and [Hammet's Dungeon Packs](https://www.nexusmods.com/skyrimspecialedition/mods/12186) - all of which you can find in QWEST!

[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194), [Skyrim Sewers 4](https://www.nexusmods.com/skyrimspecialedition/mods/9320), and [VIGILANT](https://www.nexusmods.com/skyrimspecialedition/mods/11849) are included as well, and provide artifacts alongside many new quests to do. You will also find The [Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168), [G.R.I.M](https://www.nexusmods.com/skyrimspecialedition/mods/41816), [The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179), [Wyrmstooth](https://tes-mods.fandom.com/wiki/Wyrmstooth), [Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673), and [Beyond Reach](https://www.nexusmods.com/skyrimspecialedition/mods/3008). A much more detailed Spreadsheet on the variety of quests in the list can be found [here](https://docs.google.com/spreadsheets/d/15h4lGfMr4z_1hqPp8LDVbTLLRqgjaQBUUSIYc6XtJGU/edit#gid=0).

## Overhauled Quests
From [Finding Derkeethus](https://www.nexusmods.com/skyrimspecialedition/mods/19550) to [Save the Icerunner](https://www.nexusmods.com/skyrimspecialedition/mods/34681) with [Thieves' Guild Night On the Town](https://www.nexusmods.com/skyrimspecialedition/mods/42069) or [Missives](https://www.nexusmods.com/skyrimspecialedition/mods/26788), many quests have been changed and expanded.

You should know that the [Thieves Guild have Requirements](https://www.nexusmods.com/skyrimspecialedition/mods/33256) now, and you can [Renounce the Daedra if you will](https://www.nexusmods.com/skyrimspecialedition/mods/36100), while [Vampires can skip Fort Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/25783). A much more detailed Spreadsheet on the changes can be found [here](https://docs.google.com/spreadsheets/d/15h4lGfMr4z_1hqPp8LDVbTLLRqgjaQBUUSIYc6XtJGU/edit#gid=0).

## Followers
[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) will provide a nice amount of high quality followers but there is still the unforgettable [Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035), [Auri](https://www.nexusmods.com/skyrimspecialedition/mods/11278) ([with her cute face overhaul!](https://www.nexusmods.com/skyrimspecialedition/mods/29345)), [Vilja](https://www.nexusmods.com/skyrimspecialedition/mods/6722), [Skeever](https://www.nexusmods.com/skyrimspecialedition/mods/47558), [Gladys](https://www.nexusmods.com/skyrimspecialedition/mods/50164), and even [Hoth](https://www.nexusmods.com/skyrimspecialedition/mods/16137). There is also [Serana Dialogue Edit](https://www.nexusmods.com/skyrimspecialedition/mods/16222) and [Add-on](https://www.nexusmods.com/skyrimspecialedition/mods/32161) for all those who love the goth cutie.

## Loot, Artefacts and Leveling 
[Reliquary of Myth](https://www.nexusmods.com/skyrimspecialedition/mods/31612) overhauls all vanilla Artifacts and [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308) - coupled with [Lock Related Loot](https://www.nexusmods.com/skyrimspecialedition/mods/11342) - makes sure you do not find spider webs in the dungeon chests. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) changes leveling so that exploring the world of Skyrim increases your character level, with individual skill levels increasing independently. There is a skill cap to avoid powerleveling which is determined by the player character level. More details on this can be seen on the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/17751), which I recommend you read.

## Enemies and General Difficulty 
QWEST! isn't here to make the game feel like it has a sort of "Dark Souls" difficulty. My philosophy on enemies is that diversity is more important than difficulty, and that diversity is going to naturally make the game more challenging. That is why you will find all kinds of bandits, draugrs, vampires, and dragons, while they all have new cool spells due to [EEOS](https://www.nexusmods.com/skyrimspecialedition/mods/37228). Their spawns are also increased due to [Genesis Unleashed](https://www.nexusmods.com/skyrimspecialedition/mods/23871).

A wide variety of mods are used to increase variety to the enemies you encounter across Tamriel. Draugrs have been diversified using [DUI](https://www.nexusmods.com/skyrimspecialedition/mods/21775), [BriDO](https://www.nexusmods.com/skyrimspecialedition/mods/26188) and [Cannibal Draugr on Solstheim](https://www.nexusmods.com/skyrimspecialedition/mods/21238). Bandit types have been implemented via [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145) and its Patrol addon. Vampires have been improved through the use of [Better Vampire NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/9510). Dragons are enhanced using [Splendor](https://www.nexusmods.com/skyrimspecialedition/mods/9670), [Diverse Dragons Collection](https://www.nexusmods.com/skyrimspecialedition/mods/695) and [Zim's Dragon Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/38693). This list is not exhaustive!

## Installation
### Pre-Installation

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Library

If you have your steam library in program files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be ``C:\SteamLibrary`` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

#### Change Steam's Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133).

If you ever used Vortex to mod Skyrim SE, using the Shredder becomes a critically important step, as Vortex will conflict heavily with any Wabbajack installation, so backup your stuff or shred it.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

## Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

Wabbajack will not work with Windows 7, I will not offer any kind of support for users of that operating system.

## Downloading and Installing

To prepare the download, and make sure Wabbajack doesn't stall on those files; download those 4 mods manually: 
- https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo
- https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0
- https://mega.nz/file/8T4ixLCB#YKQw5EDFdL1_e-5G_JB8WgmUkJ8N0kNtpzeOwUHZcZY
- https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg

**The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.**

1. Open Wabbajack
2. Browse the Gallery and Select QWEST!
3. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "QWEST!".
4. Select the created folder in 3. as your installation folder.
5. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish.
6. Select the created folder in 5. as your downloads folder. Place the downloaded MEGA files above AS IS in the downloads folder.
7. Click the Go/Begin button.
8. Wait for Wabbajack to finish.

Depending on hardware, the installation time may vary. As this is aimed at very low specs, expect it to take like 12h or more to complete. Leaving it over-night is recommended. Support queries where Wabbajack has not yet failed will not be taken into account.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

If Wabbajack stalls on the MEGA.NZ files, get the files below and place them AS IS in the downloads folder you've selected, then restart Wabbajack completely. It's only those 4.
- https://mega.nz/file/IS4EjJhC#inP4yfb3i-UO_sx790OpoFDk81x-WIRf9WcBeKxnmYo
- https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0
- https://mega.nz/file/8T4ixLCB#YKQw5EDFdL1_e-5G_JB8WgmUkJ8N0kNtpzeOwUHZcZY
- https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

## Copy Game Folder Files

When the installation is complete, copy the files in the `QWEST!\Game Folder Files` folder and paste them into your Skyrim folder (with the SkyrimSE.exe and the data folder). [HERE](http://prntscr.com/124984m).

## Graphical Settings

On a Ryzen 5 2400G paired with a GTX 950 2GB VRAM and 24GB RAM (never used more than 14GB, so 8GB RAM should be fine, **WHEN** installed on an SSD, if you use an HDD 16GB RAM minimum is recommended):
BethINI is located within `QWEST!/Tools`.
Make sure that Bethini is configured to the profile folder you will use in MO2 and not your vanilla INIs or any changes will be rendered worthless!
Here are the normal INI Paths that you should have in the Setup tab: [EnaiRim](https://prnt.sc/10ha499) [SimonRim](https://cdn.discordapp.com/attachments/793809552353132566/818888086079012915/Capture.PNG). If one or the other doesn't show properly, use the browse option to manually set it up.

- BethINI (Low) (locked to 60 FPS):
  - Everywhere (where it got tested): 60FPS

- BethINI (Medium) (locked to 60 FPS): 
  - Outdoors: 30-40 FPS (average 40)
  - Cities: 40-60 FPS (average 50)
  - Indoors: 60FPS

- If you have 8GB RAM and **NO SSD** or if it still has frame drops, then I recommend:
  - Testing:
    - BethINI (Medium) -> BethINI (Poor) and stopping by the preset that has a playable framerate for you.

## Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.
A pagefile is a file on your disk Windows will use when there is not enough RAM available.
Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:
1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

## Getting an ENB

This list is aimed towards very low end PCs, but that doesn't mean ENB isn't an option.

For anyone who has a 2GB VRAM card, I advise you to skip this step and test in-game first. Once you have tested, come back and read the following. 

ENB is the biggest performance hit in modding (provided you don't go crazy on textures and have lots of high poly stuff everywhere - which I didn't), and for the lucky ones with more than 2GB of VRAM but still not a lot, a custom tweaked version of [Zangdar's Rudy Cathedral](https://www.nexusmods.com/skyrimspecialedition/mods/39113) that was specifically made for this list is included. To install Zangdar's Rudy Cathedral, navigate to `Your Installation Folder\ENB Presets`([here](http://prntscr.com/10e2nl4)) and simply drag and drop the contents of either the performance one or the higher-end one to your Skyrim SE Directory (where the game .exe is). [Those](http://prntscr.com/10e2odv).

On 2GB Cards, the average fps is 30 with the Low End Preset and Medium Bethini Preset. This is very dependent on your PC, however, so your mileage may vary.

There is also another option which is ReShade. ReShade is simpler than ENBs as they generally focus on color correction, but if properly used, they can enhance the game's graphics nicely with even lower fps loss. Couple that with a Skyrim set on Low, and even the weaker GPUs can experience more than vanilla Skyrim lighting.

For Skyrim, it's very common for ReShade to be made with a certain ENB in mind, but some exist to be used on top of Vanilla Skyrim. I'll introduce you to three of them.
- [BTS - Beautifully Textured Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/25489)
- [Ulver](https://www.nexusmods.com/skyrimspecialedition/mods/40433)
- [Lucid-Icrous Lightweight](https://www.nexusmods.com/skyrimspecialedition/mods/45771)

You can have both at the same time in your Skyrim, so if you want to try both, you can download them and follow the installation instructions:

- Download the latest ReShade Version from [here](https://reshade.me/)
- Open ReShade.exe, Select SkyrimSE.exe as the game you want to install it to. 
- Select Direct3D 10/11/12 as the rendering API
- Check/Tick every single box until ReShade is installed.
Now we'll go back to the presets downloaded
- Open the ReShade Preset archive and paste it to your game folder.
- When Skyrim launches (Refer to the next step in the readme if lost on this step), press the home button on your keyboard and select the .ini file you just put in your Skyrim Folder as the loaded .ini
- Press home again to close the window.
Know that you can switch any ini at anytime during your gameplay, so if you want to compare between the 2 that I recommend, you can totally do that in game.

## Profiles 

QWEST! has two profiles: one with EnaiRim, one with SimonRim. The main difference is that EnaiRim is kinda unbalanced and very strong while SimonRim is kinda like what vanilla Skyrim should have been.
You can look them up here: [EnaiRim](https://www.nexusmods.com/skyrimspecialedition/users/3959191) and [SimonRim](https://www.nexusmods.com/skyrimspecialedition/users/67410746).

To change the profile, there's a dropdown menu on the top left of MO2. The default profile is EnaiRim, so only change this if you want SimonRim.

## Personalisation

On top of the two profiles available for the core gameplay mods, QWEST! comes with some quality of Life changes and gameplay mods that some may or may not enjoy. All of the modifcations detailed below are supported as written. No support will be given if any other modifications are made, or if you deviate from what is detailed below.

First possible modification is the [Survival Setup](https://prnt.sc/19gynoq). It is enabled by default as it has to be patched by both Synthesis and Nemesis, and has a specific Load Order for the right panel to work correctly. But if you follow carefully what I'm about to write, you will be able to remove it entirely. Yes, entirely, as I do not support removing only hypothermia or cleaning and washing while keeping food and sleep needs. There are two steps:
- Untick all the mods under ``Survival Stuff`` ( [those](https://prnt.sc/19gynoq) ) 
- Tick the ``Synthesis No Survival`` corresponding to your profile and ``Nemesis No Survival`` at  [the bottom of the left panel of MO2](http://prntscr.com/19h0hon).
Please note that there's a neat little mod on top of all of those that is disabled by default; called [Just Blood Lite](https://www.nexusmods.com/skyrimspecialedition/mods/46501). It enables blood to appear as you take damage on you and enemies, and goes away as you regenerate health! More detail on the modpage but if you want it, just enable it! It obviously doesn't work when Dirt and Blood is on so it's off by default. 

Second modification: [Paper Ui](http://prntscr.com/xb9im1). It is enabled by default but you can disable one or both of these depending on what you want.

Third modification: [Unequip Quiver](http://prntscr.com/xb9k5u). Disabled by default, it'll make your Player Character unequip it's ammunition every time you go out of combat if turned on.

Fourth modification: [Oblivion Style HUD](http://prntscr.com/xb9lrc). Disabled by default, it'll make the UI have an Oblivion style like [this](https://staticdelivery.nexusmods.com/mods/1704/images/463/463-1511538957-694432832.png).

Fifth Modification is the difficulty tweak that allows NPCs to have Ordinator Perks; disabled by default, it'll make the experience much more challenging but I play with it myself. Here's the [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/42022). There's also one for Adamant (also disabled by default); [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/47484).

Sixth Modification is [Quick Loot](http://prntscr.com/10eh3rd). Enabled by default, it adds a little box showing the inventory of whatever container or corpse that you're currently looking at, so you know what's inside without opening it. If you do not want that, simply untick the mod. (It's under the "Quality of Life" Separator in MO2)

Seventh is [NeverNude](http://prntscr.com/1152dvf). The list is Nude by default, ticking those (and unticking Bijin Skin) should make it NeverNude, which is way better for Twitch or a skeptical wife!

Eight modification: [Gamepad Guide](http://prntscr.com/xb9op3). Disabled by default, ask for the Gamepad guide in [MY Discord](https://discord.gg/ZgjVrXp) (not Wabbajack's) if you want the details on how to use a controller with QWEST!

## HyperCasual - Another Profile

QWEST! also comes with a unique profile called "HyperCasual", it removes all enemy modifications so the game is increasingly easier. It is selected just like you'd choose between EnaiRim or SimonRim, but this one features the full EnaiRim experience to make sure you become a powerful hero!

It is very different to the other profile so only those modifications can be made to it:
- Paper UI
- Unequip Quiver
- Oblivion Style HUD
- Quick Loot
- NeverNude
- Gamepad Guide

You cannot use SimonRim on this profile! Doing so voids support! 

## How to start up QWEST!

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

Upon pressing New Game, you will spawn on the walls of Helgen burning down. Once all the messages on the top left corner of the screen are gone, set the MCMs as instructed below.

If you press enter, you will be teleported to a location where you will be able to personalize your character.
After confirming your character, never use showracemenu to change its race or sex; you will then be able to start the game. If you want to customize the MCMs or need some more time to setup Skyrim Unbound, you can use the "Stay there" option.

Do NOT Select a NON DRAGONBORN OPTION within Skyrim Unbound! Doing so will result in broken questlines! You cannot escape your destiny!

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
Once the game has loaded, wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

MCMs are not automated due to a personal choice: There are many important tweaks, a mountain of informations, and useful stuff in them that can solve problems or make your experience better. Those are my own and what I recommend for the least amount of problems and a balanced experience.

Do NOT Select a NON DRAGONBORN OPTION within Skyrim Unbound! Doing so will result in broken questlines! You cannot escape your destiny!

#### Game Difficulty
- The difficulty in this Modlist is quite harder due to Genesis Spawns and enemy diversity brought by Draugr Upgrades and Improvements, OBIS, and Better Vampire NPCs. I highly suggest playing on Adept or Expert, and putting it higher only if you feel it's too easy.

#### A Matter of Time

- Presets :
  - Load User Settings

#### AGO
- Settings
  - Enable/Disable
    - Bow Camera : Disabled
    - Bow Crosshair : Disabled
    - Arrow Wounds (Player) : Disabled
    - Arrow Wounds (NPCs) : Disabled
    - Persistant Arrows : Disabled
    
#### All Geared up Derivative
- Weapons - Player
    - Shield Stay on arm while Equipped: Enable
    - Toggle un/equipping Torso Armor: Enable 
- Misc. Player :
  - Require Torso Armor : Enabled
  - (you can tweak stuff showing on you whenever you want, if something bothers you)
- NPC :
  - Enable Weapons : Enabled

#### Better Vampire NPCs
- Not an MCM   
    - In your inventory there's an item called "Vampire's Bloodgem" allowing to tweak stuff by clicking on it while crouched. 
        - I leave it as default. You can tweak it all you want. Experimental stuff may cause issues as expected. When done drop the bloodgem.

#### Campfire (Survival)
- Gameplay
  - Hotkeys
    - Set your Hotkeys however you want
    - I go by :
    - Create item : C
    - Build Campfire : B
    - Harvest wood : H
    - Instincts : Nothing

#### Diverse Dragons Col. 3
- Dragons
  - Nether Dragon : Disabled
  - Sanguine Dragon : Disabled
  - Vile Dragon : Disabled

#### Dynamic Things Alternative
- Deactivate All "Elk Skulls"

#### EVG Conditional Idles
- Player 
    - Modesty Male: Disabled
    - Modesty Female: Disabled
- NPC 
    - Modesty Male: Disabled
    - Modesty Female: Disabled

#### Follower Framework
- System :
- Settings
  - Load From File

#### Genesis Surface Spawns
  - Nights
    - Spawn Only Night Time: Enabled

#### Genesis Unleashed
  - Max Number of Dungeon Spawns: 5
  - Allow Spawning at Player: Disabled
  - Disable Surface Spawns: Enabled

#### Growl Werebeasts (EnaiRim)
- Features
  - Invulnerable During Transformation: Enabled
- If you want to be a Werebear instead:
  - Immersion : Werebear : Enabled

#### Heartbreaker (Optional) 
- Main Settings
    - Learn Spell Power: Enabled
    - It gives you a power to put npcs in stagger once per IRL hour so you can rip out their hearts; you can also bind it so you can do it anytime.
  
#### Immersive HUD
- Activation
  - Compass Activation
    - Key press toggles : Enabled

#### Immersive W. Encounters
- NEW EVENTS
  - NPCs: Jarl's Housecarls: Disabled (causes issues)
 
#### Imperious Racials (EnaiRim)
- Nothing is really important, you can toggle stuff depending on your Race though!
Remember that you can't switch race/sex using Showracemenu because of such a mod!

#### LOTD Settings
- LOTD Settings → General → Shippment Crate Locations : 
  - Carriages: Enabled
  - Inns: Enabled
  - Player Houses: Enabled
  - A lot of stuff is very nice in LOTD's MCMs, you should check them all just to know what they do, it'll be useful on the long run.

#### moreHUD
- Presets
  - Save Settings with FISS
    - Load User Settings? : GO

#### OBIS - Bandits
- Leave as is
    - Why? Enabling in the MCMs is only for the additional spawns option, but that is handled by Genesis Unleashed, so you'd end up with 50 bandits in Embershard Mine. Sounds fun? Enable it at your own peril.

#### OBIS - Patrols
- Settings
    - Enable: Enabled

#### Radiant Requirements
- Settings
  - Draugr Crypt 5
  - Forsworn Camp: 5
  - Vampire Lair : 10
  - Falmer Hive: 10

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
    There are two presets available for you to use. I personally prefer the Modern one but some prefer EasyEase's, try both and see which you like!
- Compatibility 
  - Archery Gameplay Overhaul: Enabled
  - Only this one needs to be enabled!

#### Sneak Tools (you should read that modpage if you want to play a sneak-oriented character)
- Patch
  - Allow talk mask: Enabled
    
#### SunHelm (Survival)
- General Settings
  - General
    - SunHelm Suvival : Enabled (close MCMs and wait a bit in game)
- It is a fully customizable mod so if something bothers you in game, you can go back to this MCM and tweak it.
    
#### Tentapalooza (Survival)
- Set all tents in all tabs as "Rain and Snow" instead of "No Protection"
    
#### The Ultimate Dodge Mod  
 - Here is where you configure which key will allow you to Sneak (or crouch) and which will allow you to Dodge. TUDM hijacks the vanilla sneak key to have no delay or script lag.
   - A Keybinding example would be:
      - Vanilla Sneak key within Options: C
      - Sneak key within TUDM's MCM: Left Control
  - Now your character will roll/sidestep with C and Sneak with Left Control
  - I also would recommend to use sidestep (personal preference)
  - Please Note: 
    - You cannot dodge in the Starting Cell, you need to choose a path first.
    - **The first time you dodge, you'll be stuck in a weird position in the air. Press G (or your dodge swap key) twice to be unstuck.**


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

#### Wildcat (EnaiRim)
- Disable Injuries: Enabled
- Allow Wildcat to manage difficulty: Enabled

## How to start playing

After you finish customizing all the MCMs, the last thing to check is the Skyrim Unbound MCM. You can safely experiment with all the options in there, EXCEPT choosing a Non-Dragonborn character.
Anything else in that menu can be customized to your liking. When you're ready, simply press the Start Adventure button in the Unbound MCM. You will then be prompted to create your character as usual.

Please Note: Do NOT change sex or race with showracemenu after first confirming your character.

## FAQ

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Ultrawide Options

Although I do not see why someone would have such a screen with the targeted minimals of the list, here's a document made by Mantis to help you solve such problems. [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

## I have a question

Ask it in my Discord, link [here](https://discord.gg/ZgjVrXp). The support channel in the Wabbajack Discord is for Installation questions, not support over in game stuff or suggestions.

## I have a bug

Report it in my Discord, link [here](https://discord.gg/ZgjVrXp). The support channel in the Wabbajack Discord is for Installation questions, not bug reports.

## A face part is crashing me! | Some hair/facial hair clips!

The 5th Facepart is a lie. Known and unsolvable. | Make sure to have selected a High Poly Head under Face Part, some hairstyle will remain bugged but it is known and I do not know how to fix them. The mod they're from doesn't only offer those bugged hairstyles so it remains for the rest of what it proposes.

Some NPCs have a neck seam, that's known, I'm waiting for an update of [EasyNPC](https://www.nexusmods.com/skyrimspecialedition/mods/52313?tab=description) to solve them, I talk to the author so don't worry, it'll come. Play with them for now.

## I can't talk to NPCs!

Headwear that conceals your identity will stop NPCs from interacting with you, for more details check [Sneak Tools' Modpage](https://www.nexusmods.com/skyrimspecialedition/mods/1863)

## First Person animations are weird, how do I fix??

1st person animations are overhauled by [First Person Combat Animations Overhaul 2.0](https://www.nexusmods.com/skyrimspecialedition/mods/45177). If it bothers you, you can safely disable it in MO2.

## What perk does the new weapons use?
- Rapiers get Sword perks
- Pikes get great sword perks
- Halberds get two handed axe perks
- Quarter Staffs get War Hammer perks
- Claws get dagger perks
- Whips get mace perks

## My character T-Poses!

Cap your framerate, either with BethINI, SSE Display Tweaks, or ENB.

## My Legacy of the Dragonborn (LOTD) Quests are not starting up even though I have the number of Relics the Wiki says I need!!
Due to having 4000 displays possible, we use [Quest and Reward Delay for LOTD](https://www.nexusmods.com/skyrimspecialedition/mods/44923). Use their new chart to know which number of relic you need to start the quests.

## The game is too dark! Brightness isn't right! I wanna modify the ENB shadow strength/brightness/lights settings!

The game is darker BY DESIGN, it is NORMAL that it's not as bright as the vanilla game!

For all users:
- Calibrate your monitor with deep range (google it, not hard, doesn't come natively on monitors though)  
- Use [Quick Light](https://www.nexusmods.com/skyrimspecialedition/mods/12633) (you can also make it brighter in its MCM)

For ENB Users:
- When in game, press Shift+Enter to open ENB Menu. In the right tab, called Shader Parameters at the top, select 'ENBEFFECT.FX' You will see different options for every time of day and night, and a separate slider for Interior Brightness. Dont forget to save configuration all the way in the top left.  
- A tip for editing the ENB menu in game: open the console first, otherwise you'll be mindlessly clicking and attacking things while the game is still actively reading your inputs.

Those are the ONLY tweaks available without changing LIGHTING MODS THEMSELVES, which is NOT SUPPORTED. You WILL need xEdit knowledge to do so, and it'd be EXTREMELY tedious.

## "I am bothered by the way NPCs look in the game!" and "How do NPCs look?? Are they rugged? Are they supermodels? Are they vanilla?"

I really do not care and won't take your opinion into account. I've scoured a lot of NPC overhauls (from Eeekies', Northbourne, to Bijin, Pandorable or the Re-imagined Series) and handpicked them for the list so it fits MY tastes.

If you wonder how they look, [here's a document which lists what overhauls who (for vanilla NPCs)](https://github.com/SovnSkyrim/QWEST/blob/main/NPC%20Merge%20Notes.md). 

If you do not find someone, they're either from [Pride of Skyrim AIO](https://www.nexusmods.com/skyrimspecialedition/mods/48904) if a male, or [Courageous Women of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/50812) if female. If neither of those have an overhaul, it'll be from [High Poly NPC Overhaul - Skyrim Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/44155). 

Any criticism on that is NOT welcome, and it is, in fact, the only aspect of the game I do not take ANY criticism from. Hearing complaints about this stuff gives me an instant headache. I cannot please everybody, so I decided to please myself.

## MAIN QUEST??? MIRMULNIR?? DRAGONS?? BLEAK FALLS BARROW??

Taken from [Skyrim Unbound Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/27962)'s Modpage:

The game begins with no dragons, Skyrim Unbound delays them depending on the MCM settings. By default, dragons at word walls appear after a week or two of in-game time. After another week or so, dragons start to appear randomly. In the MCM you can customize the delay and choose between timed and leveled modes.

The first few chapters of the main questline are bypassed, meaning you no longer have to obtain the Dragonstone for Farengar or defeat Mirmulnir for the Jarl of Whiterun. When you absorb a dragon soul for the first time, you'll be summoned to High Hrothgar by the Greybeards after a while. The first word of the Unrelenting Force will be learned automatically after this, or you can find it earlier in Bleak Falls Barrow.

The way of becoming a thane of Whiterun is changed. Complete The Blessings of Nature quest and talk to Jarl Balgruuf when the Gildergreen tree is repaired/the sappling blooms. He'll thank you and allow you to buy the Breezehome, and the standart thaneship quest (help people of the hold and buy a house to become a thane) will be avialable.

## Creation Club (CC Content) Support?

Never gonna happen. I don't like paid mods at all, I don't think they're that high quality, and maintaining two profiles is already painful, so two more (EnaiRim CC and SimonRim CC) would be extremely annoying (we're talking running Synthesis eight times, DynDOLOD and Occlusion four times each).

CC Content isn't considered like DLCs (Dawnguard/Dragonborn/Hearthfire) and will never be treated as such.

Using them with QWEST! would be like installing your own mods: Support is forfeited and they will NOT work without patching.

## Inigo...?

A majority of people like him. I personally don't. On top of that, users reported non-issues from other Wabbajack lists to his Nexus page which led them to make a public pinned post about their [non favorable stance with what we do](http://prntscr.com/1b2tt18) so I am not going to use him any further in QWEST!. This decision is final. A tutorial on how to restore him back has been added to #list-modifications [in my own Discord](https://discord.gg/ZgjVrXp) (Available only by opting in the Rules 11 role in #Important-info).

## I want to support your work!

I thank you for that thought but you should probably donate to Wabbajack first. Link [here](https://www.patreon.com/user/overview?u=11907933). If you still want to only support me, my patreon is [here](https://www.patreon.com/Sovn).

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Xanza and Jdsmith inspiring me to make this, y'all are neat.
- Luca for all the testing, feedback and recommendations, you are amazing.
- Althro for managing and curating the discord and being a very resourceful person. None of my work would simply exist without you. 
- zino for testing 2.0 and onwards updates, allowing for accurate feedback on performance for 2GB GPUs.
- TheSpaniard, Chri3i and Chanka for all the support you're doing in the discord.
- Every each of my Patreons for supporting me, and with the Special Folks of my discord, for helping with the development.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the Discord. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Changelog

See [Changelog](https://github.com/SovnSkyrim/QWEST/blob/main/Changelog.md).
