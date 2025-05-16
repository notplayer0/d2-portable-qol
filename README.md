### Note
**I _highly_ recommend playing [Project Diablo 2](https://www.projectdiablo2.com/) instead, whether you're a returning player or going to play the game for the first time.**

**It very much keeps the vanilla feel but makes more builds viable and adds an actual endgame. Not to mention huge QoL features such as _controller support_, WASD support, quick cast, /players setting on the menu and much more. Season 11 just launched, but it is perfectly playable offline as well.**

The original idea for this modpack and the structure of this README came from [whipowill's modpack](https://github.com/whipowill/d2-plugy-qol/). It has a different configuration and other recommended mods. I didn't fork it since I started from scratch (And I don't want to deal with Git).

# Diablo II Portable + Essential QoL Mods

This is an Essentials/Quality of Life modpack for Diablo II that fixes display issues on newer computers, adds widescreen and high FPS (60+), brings ladder-only features (Runewords, Ubers, Diablo Clone) to singleplayer, fixes 3D sound, fixes bugs, increases stash size to what Resurrected uses and more.
It also makes Diablo II completely portable.

## Install

### Windows

- Purchase keys from [Blizzard](https://us.shop.battle.net/en-us/family/diablo-ii).
- Install [Diablo II](https://drive.google.com/file/d/14IQrvP_B9rBn6-yi6w5W-PbFquYMv0x6/view) - ``v1.12`` - This is just to get the game files. Choose an installation path you won't actually be using for the game.
- Install [Patch](http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_113d.exe) - ``v1.13d``
- Download this [zip file](https://github.com/notplayer0/d2-portable-qol/archive/master.zip) of the modpack and extract it.
- Move the Diablo II folder to wherever you want. Since it is portable it can be on any USB drive as well.
- Copy and paste all files from your Diablo II installation into the ``App`` folder inside the Diablo II modpack folder, but **DO NOT REPLACE FILES**, choose to skip them.
- Launch the game by running DiabloIIPortable.exe.
- You can uninstall or delete the Diablo II installed earlier if you'd like. 

## Recommended Controls and Tips for New Players

There's no way to set default controls to all characters so here's a mini guide in case you've never played the game.

I recommend changing these controls (again, you need to do it for each new character you make)

- Skill 1,2,3,4,5,6,7,8 - Q,W,E,R,A,S,D,F
- Swap Weapons - X
- Toggle Run/Walk - Shift
- Stand Still - Ctrl
- Show Items - Spacebar

Keep in mind you can toggle the minimap with Tab, change its position with V.

And also that you can assign skills to the skill buttons above by clicking the attack icon near the health and mana orbs, hovering over a skill, and pressing the button you want to assign it to.
The one on the left is for left click, and the one on the right is for right click.

## Mods included

- [D2GL](https://github.com/bayaraa/d2gl/releases/tag/v1.0.4) - fixes display issues on newer computers, HD text, unlocks framerate (v1.3.3).
- [SGD2FreeRes](https://github.com/mir-diablo-ii-tools/SlashGaming-Diablo-II-Free-Resolution) - adds widescreen resolutions
- [d2fps](https://github.com/Jarcho/d2-rs) - makes the game look correct at high FPS
- [PlugY](http://plugy.free.fr/en/index.html) - adds infinite stash, shared stash, infinite respec, all runewords (v14.03).
- [BaseMod](https://www.moddb.com/mods/basemod) - configurable settings, bug fixes, and much much more (v1.13.9).
- [FontFix](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont) - makes 5s look like 5s instead of 6s.
- [DSOAL](https://https://github.com/kcat/dsoal) - enables 3D sound option in sound settings.

## Settings used

- Contrast and Gamma set to match how the game looks in Direct3D mode. See note at the bottom.

- PlugY for Runewords, Ubers, Diablo Clone, keep cow portal after Cow King has been killed, keep Nihlathak portal open, move Cain's position to near Harrogath's waypoint, and finally, 10x10 stash with one personal (per-character) stash tab and 3 shared tabs (exact same as Resurrected). PlugY also regularly makes backups of your characters.

- SGD2FreeRes set to 960x540. This results in perfect integer-scaled widescreen, and makes the game's font much more legible. Don't edit unless you know what you're doing.

- d2gl set to the Nearest Neighbor upscale filter.

  HD Cursor and HD Text are enabled.

  Press CTRL + O while in game to open d2gl's menu if you want to change any of the above.

- d2fps set to limit FPS to 140. You can set it to higher on the d2fps.ini file. If you have a lower FPS (like 60) you can also change it to that, but it really shouldn't make a difference unless you're on a very weak computer.

- BaseMod for EthSocketFix, AutoPickup, spawning missing Super Uniques, BypassFPS

- 3D Sound and Environmental Effects enabled thanks to DSOAL.

- Respecs and skill/stat point unassignment are left disabled (same as Vanilla).

Feel free to edit ``PlugY.ini`` and ``BaseMod.ini`` to your liking.

## Note about Contrast and Gamma settings.

This actually drove me crazy for a bit. During my testing of different glide wrappers and running the game without any, sometimes the game would set the contrast to maximum, sometimes to minimum. And on Resurrected, the contrast is set to max by default.

I tried to find how the game is "intended" to look, but found nothing, and clearly the default settings are messed up depending on god knows what. While researching this I used one of [MrLlamaSC](https://www.youtube.com/mrllamasc)'s videos for reference. It seems he doesn't use a glide wrapper, at least in the video I watched, and regardless I do think that how the game looks in D3D mode is the best looking one.
Certainly better than what the game looks at what someone would guess is the default look - using a glide wrapper, contrast and gamma at 50%. It doesn't look the best.

So I matched the game's settings while using a glide wrapper to look identical to what it looks in D3D mode.

## External Links

- [Project Diablo 2](https://projectdiablo2.com/) - The best mod for Diablo II while still keeping the vanilla feel. Makes more builds viable, adds an actual endgame. If you're a returning player or even playing for the first time, this is what I would recommend.
- [Diablo II Reddit](https://www.reddit.com/r/diablo2/) - Online forum for all the D2 fans.
- [The Arreat Summit](https://classic.battle.net/diablo2exp/) - Official guide to playing the game.
- [Tankazon's Rune Wizard](https://fabd.github.io/diablo2/runewizard/index.html) - See what runewords you can make.
- [Tomb of Knowledge](https://www.d2tomb.com/) - Fan website w/ helpful information about the game.
- [D2 Planner](https://d2planner.github.io/skills/) - Plan your skill allocations.
- [SlashDiablo](https://slashdiablo.net/) - Vanilla-like private server. Only changes a few things. If you're looking for a vanilla ladder experience again, this is where you should go.

## Credits

- D2GL by __Bayaraa__
- SGD2FreeRes by __Mir Drualga__
- d2fps by __Jarcho__
- PlugY by __Yohann Nicolas__
- BaseMod __devurandom__
- FontFix  by __SnakeByteStudios__
- DSOAL by __kcat__
- PortableApps Launcher by __[PortableApps](https://portableapps.com/)__
