# Wanderer's Way
A Community Shaders based Skyrim modlist focused on Exploration, Roleplay, Player Choice and a Dynamic World.
![Description](Resources/ww_title.png)

**Links**: [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/163526) | [Changelog](https://github.com/Kekistann/WanderersWay/blob/main/changelog.md) | [Load Order](https://loadorderlibrary.com/lists/wanderer-s-way-2)


**Requirements**:
- Skyrim version 1.6.1170 (latest Steam update).
- Skyrim AE with all Anniversary Edition content (Paid Creation Content).

## System Requirements
- **OS**: Windows 10 or 11 (no LTSC or modified versions; Linux not supported).
- **Storage**: SSD required.
- **Download Size**: ~x.
- **Install Size**: ~x.

| Component | Minimum (1080p Native 60FPS)  | Recommended (1440p Native 60FPS) |
|-----------|-------------------------------|----------------------------------|
| CPU       | i5-12600k / AMD Ryzen 5 5600X | i5-13600K / AMD Ryzen 5 7600X    |
| GPU       | RTX 3070 / AMD RX 6800 XT     | RTX 4070 / AMD RX 7800 XT        |
| RAM       | 16GB DDR4                     | 32GB DDR4                        |
| Storage   | SATA SSD                      | NVMe SSD                         |

The specs above reflect native performance. I highly recommend enabling Upscaling at a minimum, with Frame Generation or AMD FSR 3.1 enabled if your hardware supports it. Both are provided by Community Shaders and are pre-configured in the list. Together, they can effectively double your framerate with minimal visual impact.


---

## Installation

### Pre-Installation
1. **Install Dependencies**:
   - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
   - [.NET Runtime 8.x.x Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.15-windows-x64-installer).
   - [.NET Runtime 6.0.0 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).
   - If Visual C++ is installed, use the `Repair` option.

2. **Steam Setup**:
   - Disable [auto-updates for Skyrim AE](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
   - Fresh Install Skyrim AE.
   - Run Skyrim AE once through Steam.
   - Once launched, install ALL Creation Club addons. Do not ALT+Tab during this process.
   - If you have issues with the Creation Club plugins missing, I highly recommend a clean install of Skyrim. Uninstall Skyrim through Steam and completely delete the Skyrim Steam folder.

3. **PageFile & Virtual Memory**:
   Larger modlists tend to require more memory. Running out of memory will result in possible crashes or other potential issues. I highly recommend to do this step.

To set up a Pagefile:

   - Press Win Key + R
   - Type sysdm.cpl ,3 and hit ENTER
   - Navigate to Performance and click the box Settings
   - Click the Advanced tab at the top
   - Under Virtual Memory click the box Change
   - Uncheck Automatically Manage if it is checked
   - Select your disk drive, ideally your fastest solid state drive
   - Click Custom Size:
   - In the box next to Initial Size (MB), type 40960
   - In the box next to Maximum Size (MB), type 40960
   - Click Set.
   - Click OK.
   - Click Apply.
   - Click OK.
   - Restart your PC.

### Wabbajack Installation
1. **Install Wabbajack**:
   - Create a folder (e.g., `C:\Wabbajack`) on your drive’s root (not in Program Files, Desktop, etc.).
   - Download [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place it in the folder.
   - Run `Wabbajack.exe` (requires version 4.0.0.0 or later).
  
2. **Install Wanderer's Way**:
   - Open Wabbajack, select Skyrim AE, search Wanderer's Way, and click “Download and Install.”
   - Set Installation Location (e.g., `C:\Wanderer's Way`) and Downloads Location (avoid Program Files, Desktop, etc.).
   - Click Install.
   - Nexus Premium automates downloads; without it, manually click “Slow Download” for each mod.
  
---
## Playing the Game
- Launch Skyrim SE through Mod Organizer 2 (MO2) in the Wanderer's Way folder.
- After character creation, a notification will pop-up stating Wanderer's Way is configuring. Stand still and wait for configuration to complete. Upon completion, you will receive a second notification stating you're good to go.
- Wanderer's Way is pre-configured on Adept difficulty and intended to be played this way. Increasing or decreasing the difficulty slider will heavily alter your experience.
- After character creation and game configuration is finished, follow the quest markers to gear up/choose your background. Once finished, interact with the Shrine of Akatosh to choose your Game Start. Lastly, exit the room and enjoy your time playing Wanderer's Way!

## Uninstalling
- Delete the Wanderer's Way folder.

---

## Troubleshooting
- **Installation Issues**:
  - Missing files? Manually download and place them in the Downloads folder.
  - Game folder not found? Ensure Skyrim SE is installed and follow [Pre-Installation](#pre-installation).
  - Antivirus flagging? Add exceptions or uninstall aggressive third-party AV (e.g., Norton).

- **Post-Installation Issues**:
  - Form 43/DLL errors? Reinstall with “Overwrite Installation” checked in Wabbajack.
