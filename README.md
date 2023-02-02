# OpenGOAL Jak 1 - Random Cell Order BETA

Jak 1 but you're required to pick up the cells in the (random) specified order! Based on the original rules from https://jakspeedruns.com/rco/

## Known Issues
- Some cell pickups aren't blocked when done in incorrect order, and can softlock the game (mostly cells from NPCs e.g. yakows or uncle orbs)

## Settings
Each of these can be toggled on/off in the rco-settings file (in-game menu coming soon)
- FJ: No Early Temple - require top of tower before plant boss and blue switch
- FJ: No Early Plant Boss - require blue switch before plant boss
- No FCS - require end of FC for anything after FC
- No Tree/Stalagmite Hops - require end of MP before MP secret cell
- No LTS - require 72 cells for lavatube and beyond
- NMS Citadel - require blue+red+yellow sage before green sage
- No Citadel Hops - require end of LT before anything citadel
- Snowy: No Fortress Gate Skip - require fortress gate cell before flies and fortress cell
- Snowy: No Double Fortress Gate Skip - require fortress gate cell and neither flies nor fortress cell for flies and fortress cell
- Snowy: No Fortress without Flut Flut - require flutflut before flies and fortress cell
- Light Softlock Prevention: Mayor Orb Cell - require mirrors before mayor orbs if we've encountered any FJ cells 
- Light Softlock Prevention: Geologist Orb Cell - require moles before geologist orbs if we've encountered any Basin cells 
- Light Softlock Prevention: Gambler Orb Cell - require DMG before gambler orbs if we've encountered any Basin cells 
