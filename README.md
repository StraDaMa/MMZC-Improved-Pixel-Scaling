# MMZC Improved Pixel Scaling

This repo hosts the **MMZC Improved Pixel Scaling** mod for **Mega Man Zero/ZX Legacy Collection**, plus its issue tracker and releases.

[![Release](https://img.shields.io/github/v/release/StraDaMa/MMZC-Improved-Pixel-Scaling)](https://github.com/StraDaMa/MMZC-Improved-Pixel-Scaling/releases/latest)


## About
In **Mega Man Zero/ZX Legacy Collection** all Screen Layouts for **Mega Man Zero 1-4** do not scale with perfectly squared pixels, no matter which Screen Layout is used in the settings. This includes Screen Layout "Type 2", which is the max integer scaled size that will fit in your current PC screen resolution. This mod improves the scaling overall, but when an integer scale is used, it will render with perfectly squared pixels. In addition, this mod also adjusts Screen Layout "Type 3" to use an integer scale when your PC screen resolution is an integer multiple of 1920x1080. This makes it the equivalent to the "Small" Screen Layout from **Mega Man Battle Network Legacy Collection Vol 1 and 2**.

## Features
 - Outputs perfectly squared pixels when an integer scaled size is used, such as when using Screen Layout "Type 2".
 - Adjusts the scaling for Screen Layout "Type 3" to output an integer scaled size when an integer multiple of 1920x1080 PC screen resolution is used.

## Example
# Full Screen Preview
  <img src="https://i.imgur.com/tK4SKW1.gif"></img>
# Zoomed in Preview
  <img src="https://i.imgur.com/I8Yveoq.gif" alt="Close Up Preview"/>

## Installing
1. Install **MZZXLC Mod Loader**  
   Download and install [**MZZXLC Mod Loader** from the latest releases page](https://github.com/StraDaMa/MZZXLC-Mod-Loader/releases/latest)
1. **Locate game folder**  
  In Steam, right-click **Mega Man Zero/ZX Legacy Collection** → *Manage* → *Browse Local Files*.  
   If there’s no `mods` folder, create one.
1. **Copy the mod**  
  Download the latest  [**MMZC Improved Pixel Scaling** release](https://github.com/StraDaMa/MMZC-Improved-Pixel-Scaling/releases/latest), unzip, and place the `MMZC Improved Pixel Scaling` folder into your `mods` directory.

## Usage & Verification
1. Launch the game after installing **MZZXLC Mod Loader**.
1. Check the box next to **MMZC Improved Pixel Scaling**.
1. When the game window opens, if `show_console` is set to `true` in the `modloader.toml`, the console window should show:
```txt
Loading Mod DLL: mods\MMZC Improved Pixel Scaling\MMZC Improved Pixel Scaling.dll
```