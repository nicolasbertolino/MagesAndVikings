![](https://raw.githubusercontent.com/nicolasbertolino/Mages-Vikings/refs/heads/main/banner.jpg)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/136238">Nexus Page</a> |
  Installation |
  <a href="https://gist.github.com/nicolasbertolino/a303a48fcc5f22a0c0e37822a7b786e9">Changelog</a> |
  <a href="https://loadorderlibrary.com/lists/mages-vikings">Load Order Library</a> |
  <a href="https://discord.gg/Newa3dj5pZ">Join at Discord</a> |
  <a href="https://www.youtube.com/@SEEYOULHATER">Watch on YouTube</a> |
  <a href="https://ko-fi.com/seeyoulhater">Support on Ko-fi</a> ]
</p>


# Mages & Vikings
**Mages & Vikings** is a comprehensive Skyrim modlist designed to breathe new life into the game. Featuring **thousands of carefully curated mods**, this list enhances and modernizes every aspect of Skyrim – from the user interface and audio to graphics and gameplay mechanics. 

For a complete breakdown of the mods included, visit the [Load Order Library](https://loadorderlibrary.com/lists/mages-vikings).

Join our [Discord Community](https://discord.gg/Newa3dj5pZ) to connect with other players, get support, and share your adventures.

---

### Contents
- [System Requirements](#system-requirements)
- [Pre-installation](#pre-installation)
- [Installation](#installation)
    - [Starting the installation](#starting-the-installation)
    - [If Installation Fails](#if-installation-fails)
- [Post-installation](#post-installation)

### System Requirements
While this modlist is optimized as much as possible, **Mages & Vikings** prioritizes stunning visuals with dense forests, realistic grass, and full ENB effects. To fully enjoy this experience, the following hardware is recommended:
- **GPU**: RTX 4070 or higher
- **RAM**: 32GB
- **CPU**: A modern, high-performance processor
- **Storage**: The required disk space is shown in the Wabbajack UI

>[!TIP]
>You can choose separate locations for the modlist installation and the downloads folder – helpful if one of your drives is low on space. Note that after installation, downloads can be safely deleted, but will need to be re-downloaded if you update the list later.

---

# Pre-installation  

Before starting, ensure the following:  
- You own a legal, non-pirated version of the game with **all Creation Club content** updated to **1.7.104** (the latest version).
- You are running an **up-to-date version of Windows**. Download and install the following dependencies:  
    - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
    - [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer)  
    - [.NET Desktop Runtime 8.X.X x64](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

>[!WARNING]
>If you already have Visual C++ installed, ensure you run the installer again and select the `Repair` option to update to the latest redistributables. **Do NOT skip this step, or Mod Organizer 2 and the game may fail to launch.**

Then follow these steps:
1. **Disable the Steam Overlay and set the Game Language to English:**
   - In Steam, right-click on *Skyrim SE*, select **Properties** and under **General**, toggle "Enable the Steam Overlay while in-game" to *off*.
   - Still under **General**, set the **Language** to *English*.
2. **Run Skyrim Once:**
   - Launch the game to allow it to perform its initial graphics check. The settings will be replaced during installation, so there's no need to configure them now.
3. **Download Add-ons:**
   - Start the game, reach the main menu, and allow it to download the Creation Club content included with the Anniversary Edition.

---

# Installation

>[!IMPORTANT]
>The installation **sometimes fails on the first try**. This is normal, please refer to the **If Installation Fails section** below to solve the issues and proceed with the installation.

### Starting the installation

1. **Install Wabbajack:**
   - Download and install [Wabbajack](https://www.wabbajack.org/).
2. **Follow the Wabbajack Installation Procedure:**
   - Refer to the section [_Installing a Modlist_](https://wiki.wabbajack.org/user_documentation/Installing%20a%20Modlist.html) in the Wabbajack Documentation.

---

### If Installation Fails  

- **Unable to download Curios files**  
If you're experiencing issues downloading `Data_ccbgssse037-curios`, please refer to the relevant section in the [Wabbajack Troubleshooting FAQ](https://wiki.wabbajack.org/user_documentation/Troubleshooting%20FAQ.html#unable-to-download-curios-files).

- **_Operation did not complete successfully because the file contains a virus or potentially unwanted software._**  
If you encounter this error, it may be due to Windows Defender flagging the modlist installation. To resolve this, set up an exception for the modlist folder in Windows Defender:  
   1. Press the **Windows Key**.  
   2. Type "Windows Defender" in the search bar and select **Windows Security**.  
   3. Click on **Virus & threat protection** in the left pane.  
   4. Select **Manage settings** under "Virus & threat protection settings".  
   5. Scroll down to **Exclusions** and click **Add or remove exclusions**.  
   6. When prompted by Windows, click **Yes** to allow administrator access.  
   7. Click **Add an exclusion** and choose **Folder**.  
   8. Navigate to the installation folder for the modlist and click **Select Folder**.  
   9. Resume the installation.  

- **Double-check Requirements**  
Ensure you’ve met all the listed requirements and completed the pre-installation process correctly.

- **Seek Help for Other Issues**  
If none of the above resolves your problem, refer to the official [Wabbajack Discord](https://discord.gg/wabbajack) for guidance and troubleshooting.  

---

# Post-installation

#### Launch Mod Organizer 2
1. Navigate to the installation location you selected earlier and launch `ModOrganizer.exe`.
2. On first launch, you may be prompted to **increase your pagefile size**. This is a requirement from the [PageFile Manager](https://www.nexusmods.com/skyrimspecialedition/mods/128254) mod, which ensures smooth gameplay by expanding virtual memory.
   - Click **Yes** to confirm and restart your PC to apply changes.

   > If no prompt appears, you can proceed to the next step.

#### Set Up CPU Affinity
To optimize performance, use the [Set CPU Affinity](https://www.nexusmods.com/skyrimspecialedition/mods/94636) tool:
1. In Mod Organizer 2, click the **Tools** menu in the upper bar.
2. Select **Set CPU Affinity** and press **OK**.

#### Customize Your Experience
At the bottom of the load order, you'll find a colored separator labeled `[Select Options] Customize your experience`. Here, you can select options to tailor your gameplay:
- Choose to enable widescreen support.
- Choose between **Mouse & Keyboard** or **Controller** setups.
- And more.

---

### You're Ready!
Click the **Run** button in the top-right corner of Mod Organizer 2 to launch Skyrim and begin your adventure with **Mages & Vikings**!

