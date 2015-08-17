---
layout: page
title: The game
permalink: /thegame/
---
Block Attack - Rise of the Blocks is a puzzle/blockfall game inspired by Nintendo's Tetris Attack for the Super Nintendo. The game is pretty action packed for a puzzle game :-)
The game is programmed by me (Poul Sander) and is released under the GPL license version 2.

From version 1.1.0 the game play has been changed. This should also make it easier to implement an AI (almost ready)
Current version is 1.4.2

Features:

  * Based on the classic "Tetris Attack" for the SNES
  * 5 single player modes: Endless, Time Trial, Puzzle Mode, Stage Clear and Vs. Mode
  * 2 two player options: Time Trial and Vs. Mode
  * Puzzle mode has 30+ puzzles
  * Players can use a custom key setup
  * Handicap in (local)multi player
  * High scores are saved
  * Joypad support
  * Music and sound effects
  * Animations
  * Puzzle level editor (written in Java)
  * Select puzzle file from a list in the game
  * Runs under Linux and Windows + more
  * Save/Play Replay function
  * Network play, you must know the IP address of the server (uses enet)
  * Deb-package for debian exists in '[unstable](http://packages.debian.org/unstable/games/blockattack)', packages for other systems can be found around the Internet

Coming features:

  * Better AI
  * Save/play replay in Network games
  * Better network play
  * More puzzles (always needed)
  * Maybe more packages for Linux

Notes:

  * Network play might break compatibility for non-Windows and non-Linux systems (it will use enet, I don't know the exact compatibility with other operating systems). Systems that uses big endian processors (like PowerPC) will most likely be incompatible with systems that uses low endian processors (like Celeron, Pentium and Athlon).
  * The object "ReadKeyboard" is useless, but I didn't know it when I programmed the game.
  * The game was once called "Block Attack - Raise of the blocks". The title didn't make any sense...

Known bugs in version 1.4.2:

  * The way the board is saved and transfered over network means that some information is lost.

System requirements:

  * Screen resolution: 1024x768 (cannot be changed, but it can run in a window)
  * Keyboard
  * Mouse
  * OS: Windows or Linux (SDL, SDL_Mixer and SDL_image req under Linux)
  * Processor: Decent (tested on 733 MHz)
  * Memory: 64 MB (I think)
  * Harddrive space: ~15 MB
  * A network is required for network play

The game is using the [SDL libary](http://www.libsdl.org/), [SDL_Mixer](http://www.libsdl.org/projects/SDL_mixer), [SDL_image](http://www.libsdl.org/projects/SDL_image/), [SFont](http://www.linux-games.com/sfont/) (included) and [enet](http://enet.cubik.org/) (also included)

Tested on: Windows 7 and Ubuntu 15.04 (64 bit)

Source is included
