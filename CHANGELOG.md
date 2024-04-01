# Version 0.5.0:

- Further modified Drop Ship visual
- Made Spore Dragon stop slightly further away (Diversity based fixes)

---
# Version 0.4.2:

- Fixed issue with level technically not generating an explicit dungeon and instead defaulting to factory or any capable modded interior
- Factory will now spawn as the primary interior with a weight of 200 (67% chance) and mansion will spawn with a weight of 100 (33% chance)
- Baked occlusion culling onto all mushrooms aside from Chanteregallia (and the ones attached to it), Glowagaric, Bacillipads, and Mantleshelf
- Tweaked Spore Dragon audio values to be more audible and mysterious
- Increased stopping distance of Spore Dragon so that it doesn't just soft lock you with Diversity

---
# Version 0.4.1:

- Fixed issue with Navmesh not detecting level props after moving them in hierarchy
- Made Spore Dragon stop a set distance away to help not break things with Diversity
- Added glow post processing effect to Spore Dragon in set radius

---
# Version 0.4.0:

- Added PathfindingLagFix as a dependency for edge cases with outside enemies
- Tweaked a couple of AI nodes that were slightly out of place
- Added a few tactically placed mushrooms to break up linear pathways and line of sight
- Added some ambient sounds that are weird but off-putting - should catch people off guard (the mushrooms are in your head get them out)
- Made the Drop Ship into a giant mushroom and moved around some components to fit
- Fixed minor issue with custom Drop Ship music
- The Spore Dragon now roams the these lands (another experimental subspecies to test out)
- Accidentally released under "v0.3.5" before quickly changing version number

---
# Version 0.3.4:

- Fixed entrance triggers having shifted out of place

---
# Version 0.3.3:

- Placed down a solid 200 enemy AI nodes around the moon to enhance enemy behavior
- Tweaked enemy spawn rates a tiny bit
- Made the Gnome a bit less loud
- Increased local fog height so that it's more consistent throughout the map
- Made the sky more space-like

---
# Version 0.3.2:

- Changed Drop Ship music (see README or mod page for source)
- Tweaked Drop Ship visuals (will be overhauled more later)
- Reduced dirtiness of Sungus, Moonshroom, Bloodamanita, Bacillipad, Glowagaric, and Mantleshelf
- Moved Gnome to more remote reaches of the map and reverted the last volume change (I was wrong)
- Further improved README format

---
# Version 0.3.1:

- Swapped from volumetric clouds to cloud layer for performance
- Changed cloud and sky colors again so that the Chanteregallias can stick out
- Increased Gnome volume radius by one (found the sweet spot)

---
# Version 0.3.0:

- Reworked sky, sun, fog, and lighting elements into a physics based lighting system with reworked settings
- Fog should be more balanced now towards the intended tone
- The sun takes a different path across the sky and no longer clips into terrain when setting
- Changed sky, clouds, and sun color
- Retextured and adjusted UVs for every fungi so that they all look dirtier and more in line with base game
- Replaced the entrances with custom models
- Minor terrain tweaks
- Small visual tweaks to Nightcap, Bloodamanita, and Bacillipad
- Minor tweaks to water visuals
- Further reduced Gnome effect radius

---
# Version 0.2.2:

- Fixed ship area trigger being offset
- Tweaked sun and fog colors
- Reduced local fog a bit
- Improved the grace period for spawns at the beginning of the day
- Made minor tweaks to landscape
- Tweaked AI spawn/navigation nodes a tiny bit
- Made the Gnome volume more effective but smaller
- Polished up the README

---
# Version 0.2.1:

- Reduced the local fog
- Made entrance off mesh links one-way so that enemies can get down from entrances but cannot go up to them
- Tweaked scale of effect volume attached to Gnome across the river

---
# Version 0.2.0:

- Added emissive textures to Glowagarics, Bacillipads, Chanteregallia, Stranglemolds, and Moonshrooms
- Tweaked the light emitted by Glowagarics and added a bloom volume that applies to a short range around it
- Increased variance in all mushroom sizes and added slight random skews to Sungi, Moonshrooms, Nightcaps, and Stranglemolds
- Made lighting overall much darker and shifted it to a light cyan for a more gloomy, mysterious feel
- Made the local fog thicker
- Decreased the amount of enemy spawns during the first quarter of the day
- Made Stranglemold footstep noises in line with other mushrooms
- Tweaked terrain and added rock and dry grass textures that apply to steep and flat regions of the terrain respectively
- Added off mesh links from the entrances so that enemies like Masked can roam the map
- Slightly offset the teleporter point from the entrances to help with the above links
- Tweaked main entrance scan node
- Added a Gnome across the river to get initial testing and feedback on

---
# Version 0.1.0:

Initial Release