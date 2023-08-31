# Ammo Text
### Adds a text hud element on Low Ammo and Reload.
#### Image previews can be found below the Settings section.

<hr>

# Contact
In case of any crashes and/or questions ping me (S2ymi#6601) on the Official Northstar Discord in the #modding-chat channel

<hr>

# Changelog:

## v1.0.4:

Bugfixes:
- Magazine% no longer is forced at 30, now uses number in settings
- Text displays when dead/during replay/etc. less often, still buggy
- Reload text no longer uses static color
- When 1 or fewer bullets remain in gun, low ammo text uses exactly second color, color gradient shifted to match

New Features:
- When about to reload but not yet reloading, low ammo text uses reloading text color/alpha
- On anti-titan weapons, when completely out of ammo, displays configurable 'Out Of Ammo' text
- Added flashing text option, with separate toggles for 'Low Ammo' and 'Reloading', and separate option for percentage of magazine remaining to flash low ammo text

## v1.0.3:

- Made compatible with NS merged ModSettings

## v1.0.2:

- Added ModSettings 2.0.0+ compatibility

## v1.0.1:

- Fixed a crash

<hr>

# Settings:
## Main
- Position
   - `x y z`
   - The `z` value is irrelevant, it doesn't do anything
   - `0 0` is the top left corner
   - `1 1` is the bottom right corner
- Font size
   - Value used in previews is the default value
- Pilot Weapons
   - Toggle the display for pilot weapons
- Titan Weapons
   - Toggle the display for titan weapons
- ADS Fade Toggle
   - Gradually changes the Alpha the more you ADS
- ADS Alpha
   - Alpha value for use on `ADS Fade Toggle`
 
## Low Ammo
- Low Ammo Text
- Out Of Ammo Text
- Alpha
   - Range 0-1
   - Also used on ADS if `ADS Fade Toggle` is switched off
- Magazine %
   - Percent of the magazine after which the Low Ammo text is displayed
   - Don't set it to 0
- Static Colour
   - RGB colour format
   - Range 0-1
   - Used if the next setting is set to `On`
- Static Colour Switch
   - Toggles between static colour and changing
   - If set to `Off`, the colour will change from `First Colour` to `Second Colour` as ammo gets used up
- First Colour
   - Same format as `Static Colour`
- Second Colour
   - Same format as `Static Colour`
- Flashing Magaine %
   - Percent of the magazine after which the Low Ammo text flashes
   - Don't set it to 0
- Flashing Switch
   - Toggles between flashing text and no flashing text
-RGB Cycle
   - Overrides previous colour settings and makes stuff RGB
   - :D
## Reloading
- Text
- Alpha
   - Range 0-1
- Colour
   - RGB colour format
   - Range 0-1
- Flashing Switch
   - Toggles between flashing text and no flashing text
- RGB Cycle
   - Overrides previous colour setting and makes stuff RGB
   - :D

<hr>

# Preview:
![image](https://cdn.discordapp.com/attachments/974722927704539166/994937830159687710/unknown.png)
 
![image](https://cdn.discordapp.com/attachments/974722927704539166/994938081792774214/unknown.png)
 
![image](https://cdn.discordapp.com/attachments/974722927704539166/994938204354519090/unknown.png)

<hr>
 