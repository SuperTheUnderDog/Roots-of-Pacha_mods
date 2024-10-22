# Longer Days
Version: 0.1.0

## Description
Allows you to set a custom day length (anywhere from 1 minute to 24 hours).<br />
Despite the name, yes, you can make the days even shorter.<br />
At this point, multiplayer is not supported but can be worked around (see [notes](#notes))

All settings are in the config file. (Automatically created in the config folder after running the game once with this mod, named `supertheunderdog.bie_plugin.rop.longerdays.cfg`)

Compatible with game version: 1.2.0 (3) - 1.2.0 (5)

## How to Install
This mod is a [BepInEx](https://docs.bepinex.dev/index.html) plugin. Once you have BepInEx installed for Roots of Pacha, simply put this mod's dll in the plugins folder (`game folder > BepInEx > plugins`).
If you do not have BepInEx installed, you can follow [this guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html).
<sup>Developed for BepInEx version 5.4.23.1</sup>

## Config options
| Category | Setting name | Default Value | Description
| :-: | :-: | :-: | :-
| Custom Day Length | | | 
| | Enabled | false | When enabled, the day length setting here will override the game setting
| | Length | 900 | The length to set a day to, in seconds. Valid range: 60 - 86400 (1 minute - 24 hours)

## Known Bugs
| Bug | Description | When it happens | Status | Workarounds
| - | - | - | - | -

## Data collected and/or transmitted over the internet
This mod does not collect data.<br />
*A future update may add data transmition to make the mod work/auto-disable over multiplayer

## Notes
- There is currently no change to the settings displayed in-game. (If you're a modder and more familiar with editing the UI, feel free to reach out to me over Discord! Find me in the official Roots of Pacha server)
- Multiplayer is not supported at the moment. When playing multiplayer, it is recommended to turn off this mod (enabled = false in the config). However, it *should* work fine if all players have this mod installed and using the same config settings.
