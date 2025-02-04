[![Support Server](https://img.shields.io/discord/862736286774198322.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/K44VsQsKnx)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?style=for-the-badge)](https://www.paypal.me/joe91de)
![Image](https://img.shields.io/github/downloads/Joe91/fun-bots/total?style=for-the-badge)
![Image](https://img.shields.io/github/stars/Joe91/fun-bots?style=for-the-badge)

## Welcome to the changelogs for release **V2.5.0**
This is the changelog for the version V2.5.0. Don't forget to [join us on Discord](https://discord.funbots.dev)

## Changelog

### New features
* Bot-Command-Key now configurable in Registry.lua
* Max tries to find a valid path (Rush) now in Registry.lua
* Separated Weapon-Lists per Team
* Cleanup of code
* Improved soldier aiming in larger distances
* Option to use advanced aiming algorithms for every bot
* Improved spawning in SQDM (#209)
* more comments in the registry
* Skill now applied in both directions
* Improved aiming in vehicles on larger distances
* Allow empty-Bot-Tokens
* Improve language-scripts
* Chinese translation updated by FanShiFu
* bots exit vehicles on low HP #116
* bots in vehicles shoot back if hit
* Option for bots to not use air-vehicles
* Add option for random team-switch(#213)
* Bots can now spawn at squad-vehicles of bots or players (#115)
* Option to use Bot-Names added (#152)
* Bots use better seat in vehicle if one available (#148)
* improved path-finding when exiting vehicles
* Support for some stationary launchers (Kornet and TOW2)

### Bug fixes
* Several Bugfixes thanks to Bree_Arnold (#207)
* Bugfix saving Weapon-Modifications
* Reload Rockets if empty
* some tweaks to improve performance on tracing (possible since a fix of a memoryleak by VU)
* fixed Bot-Team-Detection
* rework of some language-stings
* Bugifx on vehicle-exit
* Workaround for Missing-Kit-Bug by Lesley (Careful with this option! Might cause crashes)
* fixed option with comm-permissions
* fixed bots on vehicles behaving strange
* fixed seat-swap in some choppers
* bugfix bot-behaviour when toggling attack-mode
* bugfix bot do friendly fire after revive
* bugfix revive if already dead
* fix some invalid weapon-attachments
* workaround for crash with CustomSoldierData --> this causes some errors from time to time, but much less crashes
* remove some warnings

### New maps
* Vehicles for Rush Theran Highway by BOB
* Vehicles for Rush Sharqi Peninsula with vehicles by BOB
* TDM paths for SP_Villa
* TDM paths for SP_Valley
* TDM paths for SP_Jet
* TDM paths for COOP_002
* TDM paths for COOP_006

### Updated maps
* Lots and lots of Updated maps by MeisterPeitsche (exit-command of vehicles)

### Documentation update
