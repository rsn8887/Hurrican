# Hurrican port for Switch

This is my Switch port of Hurrican, a freeware jump and shoot game created by Poke53280 that is based on the Turrican game series. Blast your way through nine action-packed levels filled with different enemies and powerups.

Everything needed to play is already included in the archive.

Port by @rsn8887.

Visit my Patreon:
https://www.patreon.com/rsn8887

![](/Hurrican/switchdata/screenshots/Hurrican_Switch_1.jpg)
![](/Hurrican/switchdata/screenshots/Hurrican_Switch_2.jpg)
![](/Hurrican/switchdata/screenshots/Hurrican_Switch_3.jpg)
![](/Hurrican/switchdata/screenshots/Hurrican_Switch_4.jpg)
![](/Hurrican/switchdata/screenshots/Hurrican_Switch_5.jpg)

# Thanks

Thanks to Poke53280 team for making such a great game, releasing the source, and making it freeware. 

Thanks to the other developers such as DKS and Pickle for extending the Hurrican source and adding SDL/OpenGL-ES support and more.

Thanks to ScHlAuChi for telling me about this.

Thanks to devkitPro for making Switch homebrew possible.

Thanks to my Patreon supporters: Jesse Harlin, Mored4u, RadicalR.

# Installation

- Download (see `assets` below), and unzip `Hurrican_switch.zip` and copy the contents over to the `/switch/` folder on your sd card, so that you have a folder `/switch/Hurrican` with many folders and files inside.

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

 - Don't try to remap buttons in the controls menu, it asks for a button press, but doesn't react to Joycon input. The only way out is to force quit the game with the home button. If you mess up preferences, just delete `/switch/Hurrican/hurrican.cfg`

# Building

```
git clone https://github.com/rsn8887/hurrican
cd hurrican/Hurrican/src
make clean
make Hurrican_switch.zip -j12
```
the zip file is created in the Hurrican folder, not in src.

# Changelog
v1.03

- Fixed crashes in tutorial and later

v1.02

- Re-compiled with 12.0.0 support

v1.01

- Re-compiled with 9.0.0 support

v1.00

- First release on Switch
