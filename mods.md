---
layout: page
title: Mods
order: 50
permalink: /mods/
---
# Introduction
Since version 2.7.0 the game have supported mods.
The mods uses the same principle as games like Quake where files from later loaded mods overwrites files from mods loaded early.
Mods are simply zip files. They can only overwrite data. No gameplay changes are possible.

# Using mods

## Enabling mods
At the moment it is possible to start mod in two ways. Command line argument or mod file.

### Command line
```
./blockattack --mod MODNAME
```
Mods loaded from command line are loaded last. They take priority over the mod file.

### Mod file
It is possible using a "mod_list.txt"-file in config directory.
Windows: '%APPDATA%/blockattack/mod_list.txt'
Linux: '$HOME/.local/share/blockattack/mod_list.txt'

The file is a csv-file without header and a line for each mod.
```
1.3.0.bricks,1
```
The fist column is the modname, the second column is "1" if enabled.

# Developing mods

# Sample mod
The standalone version and the Windows version comes with a sample mod called "1.3.0.bricks". It contains the bricks used before the 1.4.X release.
The mod is actually a zip file with a ".data" extension.
The sample mod also shows how a modinfo file could look like: "modinfo/1.3.0.bricks.json"

# 

# Comments

{% include disqus.html %}
