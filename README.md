# Anomaly Overhaul #1
Improving the item system and the progression behind it.
- [x] means its 70% ~ 100% finished
- [ ] on work, or haven't started yet




### Crafting System
- [x] add new craft kits with new improved UI, each kit has 7 max uses:
   - [x] Basic toolkit *(craft basic items and kits, tier 1 upgrade parts etc..)*
   - [x] Advanced toolkit *(craft better items, devices and kits, awr simple kits, tier 2 upgrade parts)*
   - [x] Export toolkit *(craft important kits, tier 3 upgrade parts)*
   - [x] Drug-making kit *(craft all kind of meds and drugs)*
   - [x] Ammunition kit *(craft better ammo by using bad and damaged types with lead)*
- [x] add items (Recipes) that can be found on corpses, using them will unlock new recipes for the craft kits
- [x] fill the recipes list file
- [x] Rework the UI of old repair kits

### Economy
- [x] added economy option (progression difficulty) in the new game menu with 3 choices (fast,normal,hardcore)
	- [x] the economy option affects: trade and repair prices, loots in general (even the money), discovery chance of stashes
	- [x] (Normal) for vanilla experience
	- [x] (Fast) will make the game easier for those who prefer more forgiving gameplay similar to CoC
	- [x] Not only (Hardcore economy) makes everything harder, but also all taken medkits will have a single use

### Item management
- [x] add the ability to combine multi-use items
- [x] add the ability to separate multi-use items
- [x] add the ability to disassemble misc items and create useful parts for crafting
- [x] add upgrades to binoculars
- [x] (Swiss Knife) and (Grooming kit) will have 7 max uses, both are used to disassemble misc items, both are cheap
- [x] canned food will no longer require (Swiss Knife) to open
 
### New items:
- [x] add (Anomaly Maps), new items that can be found on corpses, show the location of known anomaly locations
- [x] remove the old location discovery
- [x] add (GPS tracker), using it will show the location of nearby natural/friendly npcs for a brief amount of time, consumes UPD power
- [x] add (Ammo Box), sorting it will give the player few random ammo
- [x] (Personal Notes) will unlock random stash location
- [x] add more misc items that can be used for crafting
- [x] (Guitar) and (Harmonica) as usable items

### Cooking:
- [x] add special mutant parts (meat,parts,hide) for the new mutants (Lurker, Psysucker)
- [x] update the cooking UI
- [x] (Field cooking kit) has 3 max uses, it can be used on campfires for low-tier meat or (charcoal) for high-tier meat, can be found on corpses
- [x] (Army Kettle) has 7 max uses, it can be used on campfires or (charcoal), cook all kind of meat, can be found on corpses
- [x] (Multi-fuel stove) has unlimited uses, can cook all meat, requires high-tier fuel, can be bought only.

### Encyclopedia:
- [x] dynamic encyclopedia, unlock articles on discovery of many things
- [x] update the articles with content (anomaly, artefacts, awr)
- [x] new category (Notes), store personal notes like crafting recipes, notes from special characters
- [x] new category (Tools), contains articles about tools and how to use them in general
- [x] fill the note list

### General:
- [x] special map marker for companions
- [x] "Unload all weapons" key has been moved to keybinds tab
- [x] rework the *death_items_by_communities* after finish adding all the new items
- [x] organize item files
- [x] remove the inventory grid
- [x] debug spawner will load sections automatically, it uses blacklist instead to prevent specific sections from appearing
- [x] remove items (Hexagon wood stove) (Multimedia PDA) (Paper of equipment condition) (Artefact Handeling Tool)
- [x] remove unused misc items
- [ ] remove pre-spawned items from the game (items with static location) (if it can't be done outside of the SDK, forget about it for now)
- [x] mechanics will ask for money for using their vice
- [x] fixed weird spawns in few areas (ex: monolith inside Yanov station)
- [x] reduce the weight of lead box
- [x] reduced prices of upgrade parts to half the value
- [ ] fix the wrong values in the new artefact containers
- [x] improved item icons
- [x] improve mutant looting UI, add new button "loot all"
- [x] improve rain texture
- [x] removed (fake news) option, it has no purpose
- [x] TRX: Dynamic News Revamp:
	- [x] fixed a case where news start before completely loading
	- [x] removed stashes news and death by surge reports cause they are static/spammy
- [x] TRX: Sounds Revamp
	- [x] improved footstep sound effects
	- [x] doubled the silence periods between ambient sounds for less spam and better output 
- [x] TRX: Dynamic Faction Relations
	- [x] added new limiters to avoid the chance of getting loved by all factions after killing bandits and monolith, relation changes will be slower but more balanced

### Plans For the Future!
- [ ] fix special npcs look doesn't match the icon
- [ ] add new inventory slots for backpacks, binocular, knife, pistol *(require engine edits!! might cancel it if it went behind my reach)*
- [ ] nerf belt attachments, buff the artefacts
- [ ] add new npcs: freedom barrier guard, bandits barman and more
- [ ] add new quests (preferably dynamic), and fix existing ones like the guide work
- [ ] improve dialog related to requisting extra equipment, loans from traders, buying map routes
