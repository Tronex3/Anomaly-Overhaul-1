# Anomaly Overhaul #1
The main focus of this overhaul is:
- Economy
- Item system
- Balance
- Bug fixes
- Optimization

This is a part of Anomaly 1.4.0 update



###Economy
In an attempt to give the player the ability to choose the difficulty/economy that suits their own preferences, an new option under the name of (progression difficulty) has been added in the new game menu with three choices (stalker, scavenger, survivalist):

- The progression difficulty affects a lot of aspects: Trade, repair and upgrade costs. Loots in general (items, money). Chances of stash discovery. Max uses of medkits. Carry weight. Condition of looted weapons and more. (WIP)
- All progression factors can be controlled in-game through "extra options" menu
- NOTE: These options will be shown only if your save is loaded. Changes done to progression factors will be applied to your current playthrough only.


###Crafting System
Introducing new crafting system. An alternative way to obtain equipment through your playthrough rather than relying completely on traditional trading:

- A set of 5 kits that allow the player to craft all kinds of items:
- Basic toolkit (crafts basic kits and devices, tier-1 upgrade parts)
- Advanced toolkit (crafts better kits and devices, tier-2 upgrade parts)
- Export toolkit (crafts advanced kits and devices, tier-3 upgrade parts)
- Drug-making kit (crafts all kind of meds and drugs) 
- Gunsmithing kit (crafts better ammo out of old and damaged varients)
- Each kit has 7 max uses.
- Added special recipes and guides. Reading them will unlock new craft recipes for the said kits.
- Crafting kits and recipes can be found mainly through stashes and loots.
- Mechanics will ask for full set of basic/advanced/expert tools (7 uses)


###Encyclopedia
- Dynamic encyclopedia. the player can unlock articles on discovery of all sort of things through their playthrough (factions, levels, important items, artefacts, anomalies etc..)
- New special category (Notes). Stores personal notes such as crafting recipes, notes and letters from other stalkers (WIP)
- Ironman states can be seen in a special note in the encyclopedia


###Item management
- Added the ability to combine multi-use items (reduce overall weight)
- Added the ability to separate multi-use items (selling parts instead of full set)
- Added the ability to disassemble the majority of available items, the player will obtain basic materials that can be reused for crafting or repairing purposes.
- (Swiss Knife) and (Grooming kit) have 7 max uses, both can be used to disassemble small items or in crafting other items. (Multitool) has unlimited uses as usual.
- Added new upgrades tree for binoculars.
- Added (Anomaly maps). New documants that can be found on corpses. Show the location of known anomaly fields (WIP)
- Added (Military GPS module). Shows the location of nearby natural/friendly npcs for a brief amount of time upon use. Consumes a considerable amount of UPD power
- (Guitar) and (Harmonica) are usable items
- (Geiger counter) will cosume power upon use.
- (Personal Notes) will unlock random stash location.
- Added special mutant parts (meat, parts, hide) for the new mutants (Lurker, Psysucker)
- (Field cooking kit) has 3 max uses, it can be used on campfires for low-tier meat or (Charcoal) for high-tier meat. 
- (Army Kettle) has 7 max uses, it can be used on campfires or (charcoal). Cooks all kind of meat.
- (Multi-fuel stove) has unlimited uses. Can cook all meat. Requires high-tier fuel
- Added new set of misc items and basic materials, useful for crafting.


###Artefacts
The arefacts have been reworked from the ground in order to bring their usefulness back and sperate them in types and tiers (WIP):

- Artefacts now have less tiny / more meaningful values.
- Restored health and carry weight boosting artefacts.
- Fixed broken values of some containers
- Fixed the included ZoneExpanded artefacts mod (for real tho... nothing is right about this one)
- Nerfed mechanical belt attachments (they no longer outclass high-tier artefacts)
- Reduced LLMC (artefact container) weight from (3.6 kg) to (2 kg)
- Artefacts of electric nature can be used to recharge the UPD. Copper coil is required. The artefact used in the process will become an inactive variant.
- Removed (Artefact Handeling Tool), simply drag and drop artefacts on containers to put them in.
 

###General
- Added new (Exta Options) menu, press F1 in the main menu to access it.
- Removed the inventory grid
- Added special map marker for companions
- Added map markers for deployed sleepbags and tents
- Updated UI of repair kits
- Small nerf for controllers and poltergiests psy-aura (aimed for balancing in close areas)
- Lurkers number per squad is limited to 2 
- Canned food will no longer require (Swiss Knife) to open
- Reworked death_by_community. Slightly reduced the possibility of finding smoke.
- Reduced costs of (AWR) requirements
- All outfits have at least a single available slot for artefacts, this has been done for more accessibility to artefact system
- Careless player will lose reputation when their companions die
- Reduced the damage caused by thermal sources to outfits (%25~%50 less damage for the majority of outfits)
- Mechanics will ask for money (1000 RU) instead of vodka for using their vice
- Adjusted (buy_item_condition_factor) for some traders: military/mercs/duty traders will buy weapons above average condition, sid/bandits/flea market traders will accept a wide range of conditions
- Removed (Paper of equipment condition). Equipment condition can be seen from the notes section.
- Remove items (Hexagon wood stove) (Multimedia PDA). Other items/features serve better rules.
- Reduced prices of upgrade parts to half the value (price exploiting reasons)
- Improved many item icons
- Added new button to mutant loot UI (Loot all parts)
- Adjusted gulag job: stalkers will gather around campfires again
- Improved the rain texture
- TRX Dynamic News Revamp: Fixed a case where news start before completely loading
- TRX Dynamic News Revamp: Removed stashes news and death by surge reports cause they are static/spammy
- TRX Sounds Revamp: improved footstep sound effects
- TRX Sounds Revamp: Doubled the silence periods between ambient sounds for less spam and better output 
- TRX Dynamic Faction Relations: added new limiters to avoid the chance of getting loved by all factions after slaughtering bandits and monolith, relation changes should be slower but more balanced now.
- TRX Zone FM: Improved the main script for better optimization.
- TRX Zone FM: Added radio options menu (accissible through "extra options menu") 
- TRX Zone FM: Added the ability to make new music playlists.


###Technical:
Bug fixes, optimization, cleaning:

- Removed the old location discovery (badly written script)
- Fixed an issue with few buggy options that can't be turned off
- Fixed a case where autosaving is still working while other hardcore save modes are active.
- Debug spawner will load sections automatically, it uses blacklist instead to prevent specific sections from appearing
- Fixed weird spawns in few areas (ex: monolith spawning inside Yanov station)
- Fixed a problem with starting new game in Car Park (cordon)
- Fixed UMP-45 using nato silencer
- Restored old psy sound effects for areas such as (sarcofag) and (brain scorcher) for less ear ripping
- Removed (fake news) option. It serves no actual purpose
- Removed (robbery on sleep) option. broken/incomplete
- Removed (artefact degradation) temporarily, it will be restored once the feature gets fully-implemented in the engine.
- Restored (Show Tracers) option
- (Unload all weapons) key has been moved to keybinds tab
- Economy related options has been removed. Alternatively, all economy aspects are controllable through a single config file (configs\plugins\economy_difficulty.ltx)
- Moved (Open all routes) option to the new game menu, its under the name of (Accessible Zone)
- Reworked CoC Treasure Manager (Stashes) as the following:
- The manager no longer relies on blacklists. A whitelist is used instead to spawn specified items. This has been done as a final fix to the massive amount of sections and bugged items coming from stashes.
- Added the ability to blacklist specific items from being included in stashes for specific progression difficulties. This can be used to prevent selected items from appearing in stashes in harder difficulties. Controllable through (coc_treasure_manager.ltx) config file.
- Fixed a case where psi-storms are lagging the game
- Optimized checks for neaby campfires/sleepbags/tents for much less scanning
- Optimized toggle supprasor script by removing actor_on_update callback, the script relies on a timer instead. No need to run checks all time
- All instances of alife():object have been replaced with alife_object from _G to avoid silent errors.
- Big optimization to (simulation_objects.script) and connected files, big improvement to alife objects/smarts handeling.
- Removed (configs/weather) files, old files with no purpose
- Updated (xr_logic.parse_condlist) and (xr_logic.pick_section_from_condlist) with lighter/optimized script
- Fixed broken condition lists in many smart terrains
- Fixed a crash upon visiting the Generators
- Optimized (outfit drops) script, it no longer use actor_on_update for continuous checks
- Many script that use vector():set(x,y,z), in which are constant, were replaced with the new vector constants (VEC_ZERO, VEC_X, VEC_Y, VEC_Z) from _G
- Adjusted duplicated "Second Layer of Armor" and "Carbon Fiber" upgrade name
- Potential memory leak fix with UI menus. Anytime constructor called for UI element (ie. local ctrl = CUIWindow()) it should set ctrl:AutoDelete(true)
- Fixed few sounds with missing ogg comments
- Improved table insertions in important scripts
- Removed unused scripts
- Reworked and improved item management scripts for more optimization.
- Sorted hunderds of messy config files.