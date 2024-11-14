# aDF for WoW 1.12
aDF adds a small HUD that standardizes critical info about your target's defences, including Armor, ~~Resists~~, and specific debuffs. This HUD should be useful to all DPS and Tank players who would play differently depending on the state of their enemy's defenses and vulnerabilities.

![image](https://github.com/Zebouski/aDF/assets/11151284/d4f9b479-4498-4ec7-88c8-501f9cf759b5)

The version for 1.12 exists on the `master` branch while a version with changes specific to TurtleWoW exists on the `masterturtle` branch.

## Features
* The HUD displays your current PVE target's armor and debuffs.
* As enemy and friendly players' armor values are not exposed to the API by vmangos servers, the armor reading will not work in PVP. 
* Hold Shift and left click to drag and move the HUD.
* Right click the armor reading to share the value with others, or right click a debuff to announce if its up or not. 
* Type `/adf options` to configure which debuffs are shown for you, and which chat channel announcements are made in.

## Known issues

See https://github.com/Zebouski/aDF/issues. Pull requests are welcome

## Credits

Currently developed and maintained by Zaas-TurtleWoW

Some code merged in by Github @Goffauxs

Originally developed by Atreyyo-Vanillagaming.org
