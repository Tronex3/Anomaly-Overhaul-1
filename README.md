# Anomaly-Overhaul-1
Improving the item system and the progression behind it.

**Crafting System**
	- {DONE} Create new craft kits with new improved UI, each kit has 7 max uses:
		- Basic tools (craft basic items and kits, tier 1 upgrade parts etc..)
		- Advanced tools (craft better items, devices and kits, awr simple kits, tier 2 upgrade parts)
		- Export tools (craft important kits, tier 3 upgrade parts)
		- Drug kit (craft all meds and drugs)
		- Ammo kit (craft better ammo using bad and damaged types)
	- {TODO} add items (recipes) that can be found on corpses, using them will unlock new recipes for the craft kits in note section of encyclopedia
	- {TODO} fill the recipes list
	- {ON WORK} Rework the UI of old repair kits

Item management:
======================
[DONE] add the ability to combine multi-use items
[DONE] add the ability to separate multi-use items
[TODO] add the ability to disassemble misc items and create useful parts for crafting
[TODO] add upgrades to binoculars (if its possible)
[DONE] (Swiss Knife) and (Grooming kit) will have 7 max uses, both are used to disassemble misc items, both are cheap
[TODO] canned food will no longer require (Swiss Knife) to open
 
New items:
======================
[DONE] add (Anomaly Maps), new items that can be found on corpses, show the location of known anomaly locations
[DONE] remove the old location discovery
[TODO] add (GPS tracker), using it will show the location of nearby natural/friendly npcs for a brief amount of time, consumes UPD power
[DONE] add (ammo box), sorting it will give the player few random ammo
[DONE] (Personal Notes) will unlock random stash location
[TODO] add more misc items that can be used for crafting
[TODO] (Guitar) and (Harmonica) as usable items

Cooking:
========
[DONE] add special mutant parts (meat,parts,hide) for the new mutants (Lurker, Psysucker)
[TODO] update the cooking UI
[TODO] (Field cooking kit) has 3 max uses, it can be used on campfires for low-tier meat or (charcoal) for high-tier meat, can be found on corpses
[TODO] (Army Kettle) has 7 max uses, it can be used on campfires or (charcoal), cook all kind of meat, can be found on corpses
[TODO] (Multi-fuel stove) has unlimited uses, can cook all meat, requires (Kerosene) exclusively, can be bought only.
[TODO] (Hexagon wood stove) will be removed

Encyclopedia:
=============
[DONE] dynamic encyclopedia, unlock articles on discovery of many things
[ON WORK] update the articles with content (anomaly, artefacts, awr)
[DONE] new category (Notes), store personal notes like crafting recipes, notes from special characters
[DONE] remove (Paper of equipment condition) item, instead the player can see his equipment condition from the Notes category - equipment condition article
[TODO] new category (Tools), contains articles about tools and how to use them in general
[TODO] fill the note list

General:
========
[TODO] rework the death_items_by_communities after finishing all the new items
[DONE] organize item files
[DONE] remove the inventory grid
[DONE] debug spawner will load sections automatically, it uses blacklist instead to prevent specific sections from appearing
[DONE] remove pre-spawned items from the game (items with static location) (if it can't be done outside of the SDK, forget about it for now)
[TODO] Mechanics will ask for money OR vodka for using their vice
[TODO] improve mutant looting UI, add new button "loot all"
[TODO] update old Zone FM scripts

Later:
======
[TODO] fix special npcs look doesn't match the icon
[TODO] improve rain texture
[TODO] add new inventory slots for backpacks,binocular,knife,pistol (require engine edits!! might cancel it if it went behind my reach)
