![](https://raw.githubusercontent.com/nicolasbertolino/Mages-Vikings/refs/heads/main/banner.jpg)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/136238">Nexus Page</a> |
  Installation |
  <a href="https://loadorderlibrary.com/lists/mages-vikings">Load Order Library</a> |
  <a href="https://discord.gg/Newa3dj5pZ">Join at Discord</a> |
  <a href="https://www.twitch.tv/seeyoulhater_">Watch on Twitch</a> |
  <a href="https://ko-fi.com/seeyoulhater">Support on Ko-fi</a> ]
</p>


# Mages & Vikings
**Mages & Vikings** is a comprehensive Skyrim modlist designed to breathe new life into the game. Featuring **thousands of carefully curated mods**, this list enhances and modernizes every aspect of Skyrim—from the user interface and audio to graphics and gameplay mechanics. 

For a complete breakdown of the mods included, visit the [Load Order Library](https://loadorderlibrary.com/lists/mages-vikings).

Join the [Discord Community](https://discord.gg/Newa3dj5pZ) to connect with other players, get support, and share your adventures.

---

## Requirements

### Game Version
**Mages & Vikings** requires the **Skyrim Anniversary Edition** with all Creation Club content. The modlist is built for the **1.5.97 version** of the game, utilizing the _Best of Both Worlds_ patcher to integrate the additional content from version **1.6.1170**.

### System Requirements
This modlist is optimized for performance without sacrificing visual quality. While most textures are 2K (and 1K where appropriate), **Mages & Vikings** prioritizes stunning visuals with dense forests, realistic grass, and full ENB effects. 

To fully enjoy this experience, the following hardware is recommended:
- **GPU**: RTX 4070 or higher
- **RAM**: 32GB
- **CPU**: A modern, high-performance processor

>[!TIP]
>Also recommended is [Lossless Scaling](https://store.steampowered.com/app/993090/Lossless_Scaling/), which employs machine learning for scaling and frame generation, offering a smoother experience.


## Installation

### Pre-installation  

Before starting, ensure the following:  

- You are running an **up-to-date version of Windows**. Download and install the following dependencies:  
    - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
    - [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer)  
    - [.NET Runtime 8.X.X Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

>[!WARNING]
>If you already have Visual C++ installed, ensure you run the installer again and select the `Repair` option to update to the latest redistributables. **Do NOT skip this step, or Mod Organizer 2 and the game may fail to launch.**

- You own a **legal, non-pirated version** of the game updated to **1.6.1170** (the latest version).  

Follow these steps:
1. **Disable Automatic Updates for Skyrim:**
   - In Steam, right-click on *Skyrim SE*, select **Properties**, navigate to **Updates**, and set it to *Only update this game when I launch it*.
2. **Set the Game Language to English:**
   - In Steam, right-click on *Skyrim SE*, select **Properties**. Under **General**, set the **Language** to *English*.
3. **Run Skyrim Once:**
   - Launch the game to allow it to perform its initial graphics check. The settings will be replaced during installation, so there's no need to configure them now.
4. **Download Add-ons:**
   - Start the game, reach the main menu, and allow it to download the Creation Club content included with the Anniversary Edition.

---

### Installation

1. **Install Wabbajack:**
   - Download and install [Wabbajack](https://www.wabbajack.org/).

2. **Download the Mages & Vikings Wabbajack File:**
   - Obtain the `Mages & Vikings.wabbajack` file from the [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/136238).

3. **Follow the Wabbajack Installation Procedure:**
   - Refer to the section [_The Core Procedure for Using a Downloaded .wabbajack File_](https://wiki.wabbajack.org/user_documentation/Installing%20a%20Modlist.html) in the Wabbajack Documentation.

---

### If Installation Fails  

If your installation fails, follow these steps:  

1. **Double-check Requirements**  
   - Ensure you’ve met all the listed requirements and completed the pre-installation process correctly.  

2. **Address Missing Manual Downloads**  
   - A common reason for failure is **Missing Manual Downloads**, where Wabbajack could not download certain files automatically.  
     - You can run Wabbajack again to retry the download.  
     - Alternatively, manually download the missing files. Place these files in the same directory as your other downloads (by default, this is `[Your Installation]\downloads`) before restarting Wabbajack.  

      Files that tend to fail to download include:  
      - [High Poly Head v1.4 (SE)](https://drive.google.com/file/d/15_0njBUjHKidNnJPmLXEygzGVWsA3Zbq/edit)
      - [Fuse00's Armors](https://www.patreon.com/collection/129990?view=expanded)
      - [Bethini Pie](https://www.nexusmods.com/site/mods/631?tab=files&file_id=3097)
      - [[Dint999] HairPack02 SSE 1.11](https://drive.google.com/file/d/1YpZYTgllS08MRaqm4AxD7cIfc1wxT24g/view)

3. **_Operation did not complete successfully because the file contains a virus or potentially unwanted software._**  
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

4. **Seek Help for Other Issues**  
   - If none of the above resolves your problem, refer to the official [Wabbajack Discord](https://discord.gg/wabbajack) for guidance and troubleshooting.  

---

### Post-installation

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
- Choose between **Mouse & Keyboard** or **Controller** setups.
- Choose to enable the [Wheeler Management System](https://www.nexusmods.com/skyrimspecialedition/mods/97345) or Spell Hotbar 2.
- And more.

---

### You're Ready!
Click the **Run** button in the top-right corner of Mod Organizer 2 to launch Skyrim and begin your adventure with **Mages & Vikings**!

