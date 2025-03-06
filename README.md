<h1>
  <a href="#--------------------hedge-mod-manager">
    <img width="48" align="left" src="/Source/HedgeModManager.UI/Assets/Graphics/logo.png" />
  </a>
  Hedge Mod Manager 8 Beta
  <a href="https://github.com/hedge-dev/HedgeModManager/actions/workflows/build-project.yml">
    <img src="https://github.com/hedge-dev/HedgeModManager/actions/workflows/build-project.yml/badge.svg" />
  </a>
</h1>

A mod manager for Hedgehog Engine games on PC.

# Table of Contents
- [Current Supported Games](#current-supported-games)
- [Installation](#installation)
  - [Windows](#windows)
  - [Linux/Steam Deck](#linuxsteam-deck)
- [Building](#building)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Bug/Issue Reporting](#bugissue-reporting)
- [Contribute](#contribute)

### Current Supported Games
|                                                                                                                   | Game                       | Store |
| ----------------------------------------------------------------------------------------------------------------- | -------------------------- | ----- |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicGenerations.png" />     | Sonic Generations (2011)   | [Steam](https://store.steampowered.com/app/71340) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicLostWorld.png" />       | Sonic Lost World           | [Steam](https://store.steampowered.com/app/329440) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicForces.png" />          | Sonic Forces               | [Steam](https://store.steampowered.com/app/637100) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/PuyoPuyoTetris2.png" />      | Puyo Puyo Tetris 2         | [Steam](https://store.steampowered.com/app/1259790) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/Tokyo2020.png" />            | Olympic Games Tokyo 2020   | [Steam](https://store.steampowered.com/app/981890) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicColorsUltimate.png" />  | Sonic Colours: Ultimate    | [Steam](https://store.steampowered.com/app/2055290), [Epic Games](https://www.epicgames.com/store/p/sonic-colors-ultimate) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicOrigins.png" />         | Sonic Origins              | [Steam](https://store.steampowered.com/app/1794960), [Epic Games](https://store.epicgames.com/en-US/p/sonic-origins) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicFrontiers.png" />       | Sonic Frontiers            | [Steam](https://store.steampowered.com/app/1237320), [Epic Games](https://store.epicgames.com/en-US/p/sonic-frontiers) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/ShadowGenerations.png" />    | Shadow Generations         | [Steam](https://store.steampowered.com/app/2513280), [Epic Games](https://store.epicgames.com/en-US/p/sonic-x-shadow-generations) |
| <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/UnleashedRecompiled.png" />  | Unleashed Recompiled       | [GitHub](https://github.com/hedge-dev/UnleashedRecomp) |
<!-- | <img width="48" align="center" src="/Source/HedgeModManager.UI/Assets/Graphics/Icons/SonicGenerations2024.png" /> | Sonic Generations (2024)   | [Steam](https://store.steampowered.com/app/2513280), [Epic Games](https://store.epicgames.com/en-US/p/sonic-x-shadow-generations) | -->

### Installation
#### Windows
Download the Windows binary from the [releases page](https://github.com/hedge-dev/HedgeModManager/releases) and store it anywhere. Avoid using multiple copies such as placing a copy of Hedge Mod Manager in every game folder.
> [!IMPORTANT]
> .NET 8 Runtime or newer is required to run Hedge Mod Manager. This can be downloaded [here](https://dotnet.microsoft.com/en-us/download/dotnet/9.0).
>
> Make sure you are downloading the **Installer** of **.NET Runtime**. For most systems the **x64** **Installer** is the correct option. 

> [!NOTE]
> Currently Hedge Mod Manager does not support Epic Games Launcher. Until this feature gets implemented you will need to use [Heroic Games Launcher](https://heroicgameslauncher.com/) for playing games from Epic Games. 

#### Linux/Steam Deck
Download the Flatpak bundle (file ending with .flatpak) from the [releases page](https://github.com/hedge-dev/HedgeModManager/releases), then open the bundle file using your Flatpak compatible package manager like Discover for KDE/Steam Deck. For CLI installs use the `flatpak --user install` command.
> [!IMPORTANT]
> Currently Hedge Mod Manager only supports specific types of Steam and Heroic installations. This should not be an issue if you are using SteamOS.
> 
> For Steam, a Steam install with a link at `~/.steam` or `~/.local/share/Steam`.
> 
> For Heroic, it must be a flatpak install within the home directory. 

> [!NOTE]
> Currently Hedge Mod Manager is not officially available to be downloaded from any package managers.

### Building
[Check out the building instructions here](/docs/BUILDING.md).

### Frequently Asked Questions
- Where can I install mods?

  You can drag and drop the mod archive into Hedge Mod Manager's window and it will scan and install the mods for you. If the mods are found on GameBanana, you can click the 1-Click button to open the installer within Hedge Mod Manager.

- I need tech support, where do I post it?

  You can try posting it in Issues, just follow [Bug/Issue Reporting](#bugissue-reporting). 

- I got an error/crash popup, what should I do?

  Press "Save Log File" and save the file, then report the issue with the log file attached as written in [Bug/Issue Reporting](#bugissue-reporting) applies for crashes aswell.

  Avoid trying to report the same issue multiple times.

  Also write down all steps you've taken to try resolve the issue. If an issue arises on it's own, avoid deleting files unless been told as this could still be an issue with Hedge Mod Manager.

### Bug/Issue Reporting
Please make sure all issues contain all the information in a concise form for both the title and body.

Make sure to explain in as much detail as you can on what you have done that caused the issue and if you are able to reproduce the same error/crash. If reproducable, explain in steps what you did. Please also use common sense.

### Contribute
Feel free to submit pull requests, or suggest improvements.
