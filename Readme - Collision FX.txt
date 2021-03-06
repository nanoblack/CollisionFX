-------------------------------------------------------------
 Collision FX
 Author:    pizzaoverhead
 Version:   2.1
 Released:  2014-12-18
 KSP:       v0.90

 Thread:    http://forum.kerbalspaceprogram.com/threads/101496
 Licence:   GNU v2, http://www.gnu.org/licenses/gpl-2.0.html
 Source:    https://github.com/pizzaoverhead/CollisionFX
-------------------------------------------------------------

Collision FX adds sound, light and particle effects when colliding or scraping your craft. Check the forum thread for updates:
http://forum.kerbalspaceprogram.com/threads/101496

This plugin makes use of ialdabaoth and Sarbian's Module Manager to avoid needing part.cfg edits. Check here for new versions:
http://forum.kerbalspaceprogram.com/threads/55219


Installation
------------
Extract the zip to the root KSP folder, merging with the GameData folder.
Download and install the latest version of ModuleManager:
http://forum.kerbalspaceprogram.com/threads/55219


Uninstallation
--------------
Delete the CollisionFX folder inside GameData.


Configuration options
---------------------
volume - How loud the sound effects should be played. 1 is normal volume, 0.5 is half volume.
scrapeSparks - Whether the part should create sparks and a metallic scraping sound when sliding across the ground. Disable for wheels.
collisionSound - The sound file to play when the part bumps into something.
scrapeSound - The sound file to play when the part scrapes against something. This sound should be loopable.


Audio credits
-------------
GroundSkid.wav - Modified from "Rockslide.wav" by juskiddink, available here: https://www.freesound.org/people/juskiddink/sounds/77931/ and "md1trk4.AIF" by alienistcog, available here: https://www.freesound.org/people/alienistcog/sounds/123473/
TyreSqueal.wav - Modified from "Chrysler LHS tire squeal 01 (04-25-2009).wav" by audible-edge, available here: https://www.freesound.org/people/audible-edge/sounds/71736/
Bang1.ogg - 

Version history
---------------
2.1 (2014-12-18)
- Rebuilt for KSP 0.90.
- Modified collision detection.
- Added Gaalidas' fix for Kerbal Foundries parts.

2.0 (2014-12-08)
- Fixed wheel, repulsor and track parts from Modular Multiwheels and Kerbal Foundries showing sparks.
- Improved collision detection.
- Fixed stuck lights and sounds.

1.2 (2014-12-02)
- Disabled effects for EVA kerbals and Kerbal Foundries wheels and tracks.

1.1 (2014-11-29)
- Fixed issues with wheels producing sparks in some cases.
- Disabled effects for Firespitter wheels as they have their own effects.

1.0 (2014-11-29)
- Initial release.