# TW3-PS4-Texture-Patcher
Swaps out original texture data with custom data.

# Notes Before You Get Started
* the way this tool is made means you are limited to swaping data that is equal or lower in size, same goes for resolution and Mip Count.
* Its in its beta phase(orginally it was set-up for my system but i've cleaned it up so it should work on all systems), as such bugs may be apear

# Requirements
* [Offical ModKit](https://www.nexusmods.com/witcher3/mods/3173)
* [Texture Cache Parser](https://forums.cdprojektred.com/index.php?threads/tool-cache-reader.8397190/)
* Extracted Game PC/PS4


# Using The Tool

1: Make sure you have the Official ModKit installed and set-up, along side your game unpacked

2: Download a Mod From the nexus that should work(in this example ill use [this](https://www.nexusmods.com/witcher3/mods/4507/)) and unpack it either using the ModKit or Cache Parser(if you use Cache Parser you will need to recreate tis orginal path structure)

3: Copy it to the same directory as my tool, now copy the texture cache that contains the texture you want to Swap out to the same folder with my tool(in this case the texture i want to swap out is inside content0s texture cache)

4: Drag And Drop the texture Cache onto the executable named "TW3CT-Auto" it will grab all the textures inside the current directory and start swaping them out.. you will need to hit ant key after each texture is finished.

4:If you want to use my tool from a CMD window the arguments is as follows: <"texture.cache" or path to texture cache> <Path To Texture("characters\models" NOT the absolute path(ie, Z:/path/characters/xx)>

# Proof of it working:

![screenshot](https://cdn.discordapp.com/attachments/719858806351200338/816376309356953661/The_Witcher_3__Wild_Hunt_Game_of_the_Year_Edition_20210302143838.jpg)
![screenshot](https://cdn.discordapp.com/attachments/816331695544336446/816547472419717140/The_Witcher_3__Wild_Hunt_Game_of_the_Year_Edition_20210302145143.jpg)
