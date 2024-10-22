# Attunement Ring Color
Version: 1.0.0

## Description
Allows you to set custom colors for the rings in the attunement minigame. You can use this to add some nice colors, make the game more accessible, or make the rings invisible entirely and use only sound cues!

Compatible with game version: 1.2.0 (3) - 1.2.0 (5)

## How to Install
This mod is a [BepInEx](https://docs.bepinex.dev/index.html) plugin. Once you have BepInEx installed for Roots of Pacha, simply put this mod's dll in the plugins folder (`game folder > BepInEx > plugins`).
If you do not have BepInEx installed, you can follow [this guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html).
<sup>Developed for BepInEx version 5.4.23.1</sup>

This mod works client-side (meaning it only affects the person who has it installed, and does not require the host to have the mod)

## Config options
file name: `supertheunderdog.bie_plugin.rop.attuneringcolor.cfg`
| Category | Setting name | Default Value | Description
| :-: | :-: | :-: | :-
| Colors | | | 
| | Active | FFFFFFFF | The active attunement ring's color. RGBA format.
| | Upcoming | FFFFFF40 | The upcoming attunement rings color (on screen but not active). RGBA format.

RGBA format means the colour is represented as 2 characters for the Red value, 2 for Green, 2 for Blue, and 2 for the Alpha channel, in this order. The range is 00-FF for each of those values.<br />
Basically, if you're not sure what this means, you can use a color picker and grab the 'hex value' (without the leading \# some pickers have), and then add FF for the alpha channel.

## Known Bugs
| Bug | Description | When it happens | Status | Workarounds
| - | - | - | - | -

## Example
### The default look:
<!--img src="./example%20images/default%20attunement.png" alt="default settings" title="Default Look" width="280"-->
![default settings](./example%20images/default%20attunement.png?raw=true "Default Look") <!-- -->

### Using the mod:
![modded blue](./example%20images/attunement%20blues.png?raw=true "Blue Rings")
![modded aqua and purple](./example%20images/attunement%20aqua%20and%20purple.png?raw=true "Aqua and Purple Rings")
<br/> Note: these examples use 2 different config settings. The colours for pets and farm animals when using the mod are consistent (meaning the same set of colours would be used for both)
