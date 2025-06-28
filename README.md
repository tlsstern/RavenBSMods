# Minecraft Forge & Modding Guide

This guide provides step-by-step instructions for installing Minecraft Forge and adding mods to enhance your Minecraft experience.

## Table of Contents
1.  Installing Minecraft Forge
    * Requirements
    * Installation Steps
    * Verifying the Installation
2.  Adding Mods to Forge
    * Finding and Downloading Mods
    * Locating Your `mods` Folder
    * Installing the Mods
3.  Tips

---

## 1. Installing Minecraft Forge

Forge is a mod-loading tool that allows you to play Minecraft with custom modifications.

### Requirements
* You need to run the vanilla version of Minecraft you intend to mod **at least once** before installing Forge. For example, if you want to install Forge for Minecraft 1.8.9, you must first launch Minecraft 1.8.9 from the launcher.

### Installation Steps
1.  **Download Forge:** Go to the official [Minecraft Forge download page](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.8.9.html).
2.  **Download Installer:** On the main page, you will see two versions: "Download Latest" and "Download Recommended". It is advised to use the **"Recommended"** version for better stability. Click the **"Installer"** button.
4.  **Run the Installer:** Locate the downloaded `.jar` file and open it. If you cannot open it, you may need to install or update [Java 8](https://www.java.com/download/).
5.  **Install Client:** A Forge installer window will appear. Ensure that **"Install client"** is selected and the file path points to your default `.minecraft` directory. Click **"OK"**.

### Verifying the Installation
1.  Open the **Minecraft Launcher**.
2.  Go to the **"Installations"** tab.
3.  You should see a new installation profile for Forge. If not, create a new one and select the Forge version from the "Version" dropdown menu.

---

## 2. Adding Mods to Forge

Once Forge is installed, you can add mods.

### Downloading Mods

### Download the Mods from the Mods folder in the GitHub Repo
Forge automatically creates a `mods` folder inside your `.minecraft` directory upon its first launch.

* **Windows:** Press `Win + R`, type `%appdata%\.minecraft`, and press Enter.

If you have run Forge at least once, you will see a folder named **`mods`** (If not create one).

### Installing the Mods
1.  Take the mods `.jar` you downloaded.
2.  Drag and drop them directly into the **`mods`** folder.
---

## 3. Tips
* **Rebinding of the GUIs** Clicker RShift to open GUIs and if possible rebind them. Do this until everything has its own button RShift and then ESC should open Raven
* **Configs and Scripts**
  * **Windows:** Press `Win + R`, type `%appdata%\.minecraft\keystrokes`, and press Enter.
  * You can use public configs from Raven BS V2 [Discord server](https://discord.gg/VvjdSCgyEb)
* **AutoGG** Press `Win + R`, type `%appdata%\.minecraft\config`, and press Enter. There locate the Utils config file and change the `AutoGG=GG` to `AutoGG= ` Test with `1st - Lava `
* **ViaForge** As of 27/06/2025 Connect to viaforge version 1.20.1. Viaforge is localte in the Servers tab in the bottom left.
