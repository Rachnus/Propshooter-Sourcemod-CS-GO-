# Propshooter-Sourcemod-CS-GO-
Propshooter v1.1

This plugin allows admins by default to shoot props by typing !ps, !propshooter in chat, or sm_ps, sm_propshooter in console.

## Features:
###Menu + Admin menu (Same menu, depends on access flags)
### When propshooter is activated, bullets do 0 damage
### Change prop model (Models can be added to propshooter_paths.txt, aslong as they have the property "prop_physics")
### Change color/alpha on the prop (Colors can be added to propshooter_colors.txt)
### Remove props (Admins with the flag "b" can remove all props on map)
### Admin menu to change cvars listed down below

## Cvars:
1. propshooter_proplifespan (Default: 3) Sets the amount of seconds the prop will be alive. (0 for unlimited, or until player disconnects or removes the props)
2. propshooter_maxprops (Default: 50) Sets the maximum amount props to be on the map at the same time for each player
3. propshooter_adminonly (Default: 1) 1 for admin only, 0 for anyone


## Players can do (If propshooter_adminonly 0):
1. Shoot props
2. Change prop model
3. Set color/alpha on the prop
4. Delete their own props

## Installation:
1. Place propshooter.smx in addons/sourcemod/plugins
2. Place propshooter_paths.txt in addons/sourcemod/configs 
3. Place propshooter_colors.txt in addons/sourcemod/configs

## Changelog
1. v1.0 - Initial Release.
2. v1.1 - Fixed array out of bounds error in OnTakeDamage (Thanks Pala4)

## Credits
1. Me
2. Pelipoika


