# Hurrican port for Switch

This is my Switch port of Hurrican, a freeware jump and shoot game created by Poke53280 that is based on the Turrican game series. Blast your way through nine action-packed levels filled with different enemies and powerups.

You can learn the basic controls of the game by playing the tutorial level. Just use the left stick to select "start game" and choose "play tutorial" in the main menu.

Everything needed to play is already included in the archive.

Port by @rsn8887.

Visit my Patreon:
https://www.patreon.com/rsn8887

![](https://i.postimg.cc/TPH3VW8t/IMG-2411.jpg)
![](https://i.postimg.cc/50fz6zVj/Open-RCT2-cc.jpg)
![](https://i.postimg.cc/vmFfwj2r/Open-RCT2-bb.jpg)

# Thanks

Thanks to Poke53280/Eiswuxe for making such a great game, releasing the source, and making it freeware. 

Thanks to the other developers such as DKS/Pickle for extending the Hurrican source and adding SDL/OpenGL-ES support and more.

Thanks to ScHlAuChi for telling me about this.

Thanks to devkitPro for making Switch homebrew possible.

Thanks to my supporters on Patreon: Andyways, CountDuckula, Jason Crawford, Greg Gibson, Jesse Harlin, Özgür Karter, Matthew Machnee, Milenko, and RadicalR.

# Installation

- Download (see `assets` below), and unzip hurrican_switch.zip and copy the contents over to the `/switch/` folder on your sd card, so that you have a folder `/switch/hurrican` with many folders and files inside.

# Controls

 - Left analog stick = walk/duck/aim (hold up/down to look)
 - Dpad = walk/duck/aim (hold up/down to look)
 - Y = shoot
 - B = jump
 - X = hold for lightning beam (control angle with stick/dpad left/right)
 - A = powerline
 - R = grenade
 - L = cycle weapon type 
 - ZR = smart bomb

# Current Limitations

 - Don't try to remap buttons in the controls menu, it asks for a button press, but doesn't react to Joycon input.

# Building

```
git clone https://github.com/rsn8887/hurrican
cd hurrican/Hurrican/src
make clean
make hurrican_switch.zip -j12
```

# Changelog

v1.00

- First release on Switch