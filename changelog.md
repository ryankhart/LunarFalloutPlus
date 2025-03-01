# Changelog

# 2.0.4 - Collect 'em All

Important Additions to note include a bunch of collectibles, Dialogue Sneak Peek, Power Armor to the People

Profile specific INIs have been removed. If you were using them before, you NEED to run bethini to setup your system inis. I've pre-moddified the medium and high bethini presets included with the lists bethini install with my recommended tweaks for the list (see the updated readme for more details).

- Added
    * Dialogue Sneak Peak
    * New Bobbleheads
    * Ketaro's Magazines
    * Unbogus Lunchboxes
    * More Toys
    * Tales from the Commonwealth - Facegen data
    * Power Armor to the People
    * Lore Based Power Armor Changes to the People
    * Consistent Power Armor Overhaul
    * Minutemen Paint Jobs
    * Gunner Outfit Pack (Just the PA Paint jobs)
    * More Valid Locations for Radiant Quests
    * Shortcut to Curie (Alternate version)
- Updated
    * Radium
    * Buffout4
    * Creative Perks Plus (Gumshoe 02 now grats 25% of ER, and 10% of Rad Resist to Armor)
    * Fallout 4 HD Overhaul
    * Wattz Laser Unofficial Update
- Removed
    * Scrappable Power Armor Pieces (redundant with Power Armor to the People)
    * Leaf Blower Junk Jet
- Misc
    * Custom INIs now ship with the modlist as BethINI medium and high presets (if someone wants a low I can do that too, and seriously, don't bother trying to run this list on ultra)
    * Reorganized nexus downloads for a handful of my patch mods, no major content changes though
    * Repacked Power Armor Frame Retexture into the base game BSAs
    * A few outfits changed from underarmor to full outfits, added legendary effects to quest reward clothing
    * Power Armor Repair requirements have changed
        1. Raider - Armorer 2
        2. T45 - Armorer 2 + Science 1
        3. T60 - Armorer 2 + science 2
        4. T51 - Armorer 3 + science 1
        5. X01 - Armorer 4 + Science 2 + Nuclear Physicist 1

# 2.0.3

After the DCRE update, if you experience the looping song issue, run the following console commands
stopquest DiamondCityRadio
startquest DiamonCityRadio

- Added
    * Railroad Redone Improved
    * I'm talking to you
    * Fallout Incursion Theme Main Menu Music Replacer
    * Lush Main Menu Replacer
    * Radium - A Music Mod
    * A Forest - Tree Trim
    * Wattz 3000 Sound and Reverb Update
- Updated
    * Diamond City Radio Extended
    * FallUI Item Sorter
    * Creative Perks Plus (Added Fortune Finder chance for legendary items in safes)
    * Simple Power Armor Damage Threshold (Removed massive buff for armor piercing weapons against PA)
    * Creative Perks
    * Creative Perks Plus
    * 4estGimp's Complex Item Sorter Enhancements
    * SS2 Ruined Homes and Gardens
- Removed
    * Optimization Patches Collection
    * Baseball Bat Grips
    * Restore PA Frames (no longer necessary since the removal of Some Assembly Required)
- Misc
    * Repacked ~30 texture mods into the base game BA2s
    * Swapped NONE low verion for NONE Standard. This should give a decent buff to non-armor builds.
    * Added weavable clothing to the legendary spawns list
    * Moved "Normal" damage plugin into optional folder, to use Lunar survival damage levels. Default damage for the list in survival mode will be increased very slightly as a result.
    * Patched added interiors for Clarity fog values
    * Fixed Raider PA recipes
    * Fixed pump shotgun reciever damage calculation
    * Fixed Gunmetal Raider Armor installation
    * Buffed Raider Power Armor health slightly

    ## Patreon Dev Profile
        * Dialogue Sneak Peak
        * New Bobbleheads
        * Ketaro's Magazines
        * Unbogus Lunchboxes
        * More Toys

# 2.0.2.1
- Added
- Updated
    * Diamond City Radio Extended
    * FallUI Inventory
- Misc
    * Fixed Drumlin Diner precombine conflict
    * Fixed sorting for Greaser Outfit

# 2.0.2
- Added
    * FallUI Icon Library
    * FallUI Item Sorter
    * FallUI Confirm
    * See Region Names On Saves
- Updated
    * Sim Settlements 2
    * Complex Item Sorter
    * 4estGimp - M8r98a4f2's Complex Item Sorter Enhancements
    * Random Valuables Redux
    * FallUI Map
    * FallUI HUD
    * FallUI Inventory
    * Faction Distribution Framework
    * Lunar NONE patch pack
- Removed
- Misc
    * Fixed damage settings plugins not working
    * Fixed pump-action shotgun crafting
    * Added Optional plugin to enable PipboyFX in customization section
    * unpacked UNPC Main File (reported issues with one of the meshes)

# 2.0.1.1 Hotfix

This is a hotfix try and address the recuring infinite loading screen issue some users have been having. I believe the root cause was related to vsync settings and windowed mode for users, possibly interacting with GSync/FreeSync settings. It also includes a hotfix for Workshop Framework that was preventing some SS2 quests from progressing.

This also includes a swap to using the standard system game INI files, instead of profile ones. It's caused confusion in the past, and makes it harder to optimise your settings and update the list, and may have contributed to the ILS issues. See the (readme)[https://github.com/WhiskyTangoFawks/LunarFalloutPlus#readme] for settings recommendations.

- Added
    * Bethini
- Updated
    * Workshop Framework
- Misc
    * Disabled profile specific Game INI files
    * Revert HighFPSPhysics mod settings back to default

# 2.0.1 
- Added
    * Fallout 4 HD Overhaul Cubemap Fix Loose Files
    * Non generic vats sound effects
- Updated
    * Complex Item Sorter
    * 4estGimp - M8r98a4f2's Complex Item Sorter Enhancements
    * Diamond City Radio Extended
    * Creative Perks Plus
    * Random Valuables Redux
    * FallUI Map
    * FallUI HUD
    * FallUI Inventory
    * Workshop Framework
    * Sim Settlements 2
    * SS2 Chapter 2
- Removed
    * More Uniques (incompatibility with LFO)
- Misc
    * Tweaked companion affinity to be slower in both directions
    * Elianora's Armor Compendium - tweaked enchantments on full-body clothing
    * Added High FPS Override settings for testing for people with the infinite loading screen issue

# 2.0.0 Stop complaining this list needs more weapons
This update is a major overhaul of weapons, Power Armor, and their distribution. A new game is strongly recommended (due to the scale of the changes to weapon and power armor distribution, and the removal of VUWR-R).

To update an existing game (Not recommended, but it is possible possible) make a clean save (go into an interior cell, update, set game to non-survival, wait 3 days, turn the game back to survival). This should reset all cells, and allow you to find the new weapons in the world. Due to the removal of VUWR, and the addition of Unique Uniques, unique weapons will be missing their mods, however unique uniques should detect this, and add the missing mods.

Recommended - Go download the Cross Break Action Laser Skins from [Neiro's Gumroad](https://niero.gumroad.com/l/fhdhdh)

Warning - This update includes the final update from the Fallout 4 HD Overhaul mod, which means about 40gb of downloads are required.

This update adds a LOT of new BSAs. If you find yourself CTDing when starting or loading a game, it's because you've hit the limit, and need to repack and combine some of them to get beneath the limit. The creation club content is particularly problematic here, because of how many archives it has. I'll be experimenting with repacking the texture mods into the main game archives, however that will require more time and testing before it's ready.

- Added
    * Combat Zone Restored Restored
    * Ultimate Hacking
    * Creative Perks Plus - Ultimate Hacking
    * Random Valuables Redux
    * Scrappable Skeletons
    * Settlement Attack Spawns Outside the Settlement
    * Keep Radiants in the Commonwealth
    * Power Armor Frame Retextured (4k)
    * Power Armor Map Fix
    * Better Goodneighbor Fixed ESP
    * BCR - Lever Action Rifle
    * The Makeshift SMG
    * The Pipe Shotgun Collection Redux
    * Pump Action Shotgun Rifle
    * Pipe Assault Rifle
    * Cross Break Action Laser
    * 4estgimp's Cross Weapon INNR
    * Institute Pulse Carbine
    * The Zap Gun
    * Tinkerer's Raygun
    * Wattz Laser Gun
    * Wattz Laser Gun Unofficial Update
    * PJAR - Makeshift Pistol
    * McMillan CS5
    * Makeshift Nailgun
    * Salvaged Sentrybot Weapon - Microgun 3.0
    * The Skewer Launcher
    * Handmade Antimaterial Rifle
    * Faction Distribution Framework - CRAP Rusty Weapons
    * C.R.A.P. Service Rifle Patch
    * Punk Crowbar
    * Mad Can - Fury Beans
    * Slaughtering Buzz Axe
    * Concrete Sledgehammer
    * Pickaxe
    * Wastelander's Melee Weapons
    * The Fireaxe
    * Bowie Knifes
    * The Frying Pan
    * The Bull Dozier
    * The Boxcutter
    * Butcher's Knife
    * Furby's MCAM retextures
    * Unique Uniques
    * More Uniques
    * Recruit Arlen Glass as Settler
    * Recruit Darla as Settler
    * Recruit Katelyn Alden as Settler
    * Recruit Phyllis Daily as Settler
    * SS2 Addon Unlock Vanilla Recruitable Vendors
    * Recruit Random Encounter Settlers and Farmers
    * Recruit the Amnesiac Gunner
    * Random Inner City
    * Atom Cats Drag Race Start Fix
- Updated
    * Fallout HD Overhaul
    * Lunar Fallout Overhaul
    * Workshop Framework
    * Sim Settlements 2
    * SS2 Chapter 2
    * Railroad Redone
    * Wetness Shader Fix
    * Faction Distribution Framework
    * Backpacks of the Commonwealth
    * Simple Power Armor Damage Threshold
    * Creative Perks Plus
    * Unique NPCs Creatures Standalone Version
    * Subversion - The Institute-Railroad Alliance Alternate Ending
    * Nuka World Plus
- Removed
    * The Hunting Shotgun
    * Makeshift Shogun and Grenade Launcher
    * Bullpup Bozar
    * Better Settlement Defense (Usage is too opaque to the player)
    * Take your cores (it's a nice mod but unnessary)
    * Auto-hack
    * Some Assembly Required
    * Explorer fast travel (Optional file - It needs bugfixing, but I don't have time to maintain it properly)
    * Beastmaster (And CPP Integration - it's buggy, and I don't have the skills to properly rebuild the mod)
    * Exotic Workshop Creatures
    * Sun Alignment Tweaks (causes weirdness with shadow and time settings)
    * VUWR
    * VUWR-R
    * Random Valuables
- Misc
    * Lots of Lunar and Faction Distribution Framework patches
    * Nerfed Codsworth's Flamethrower
    * Fixed Orphans of the Commonwealth Child Settler WSFW integration
    * Fixed Buffout and Jet not curing weakness and lethargy
    * Fixed a couple naked npc bugs
    * Adjusted shadow settings (lower resolution close up to prevent pop-in)
    * Reduced grass density (Should result in better performance)
    * Enabled dynamic papyrus budget management in HighPhysicsFPSFix, set default budget to 2.4
    * Moved Start Me Up to Optional files
    * Perk - Spray and Pray now grants chance for additional ammo, and automatic weapons are no longer a separate proficiency (Hopefully this should make automatic weapons more viable with Lunar ammo scarcity).
   
# 1.1.4
- Added
    * EVB With Dismemberment
    * Settler and Companion Dialogue Overhaul
    * SCDO Lite by Mycenia
- Updated
    * Lunar Fallout Overhaul 101
    * Jolly Item Sounds
    * Faction Distribution Framework
- Removed
    * Dismemberable EVB
    * Icebreaker Settler Dialogue Overhaul
    * Flash(JoeR) - Molerat Disease Fix (redundant with LFOv101)
- Misc
    * Patched Orphans of the Commonwealth clothing and hairstyles into vanilla children
    * Added missing textures from Orphans of the Commonwealth
    * Reworked distribution for Makeshift Shotgun, Hunting Shotgun, Service Rifle, and Bullpup Bozier
    * Fixed Disease item cure descriptions

# 1.1.3 
This update is safe safe if you haven't started the Nuka-World Quest or visited Nuka-World. If you have, I recommend either not updating, or manually rolling back Nuka-World Plus to version 0.995.

This update removes the M2019, and the 10mm SMG. Make sure to unequip any you are carrying before updating. Both guns are below the quality of what I'd like in the list, and swapping to the split LFO patch game me the chance to remove these. I won't be replacing them directly, but have plans for a few more weapons additions.

This update includes changes to aid items and disease curing. Each disease is now cured by one chem/drug, antibiotics now only cures infection.

- Added
    * SS2C2 - 3DNPC Patch
    * Sim Settlements 2 Chapter 2 - Tales From the Commonwealth - Warehouse Door Patch
    * Classic Vault Scientist Outfit Replacer
    * Creative Perks Plus - Sneaky Kills - Mr Sandman Executions
    * Boston FPS - PRP Edition
    * D.E.C.A.Y.
    * Decay Redux
    * Burnt Magazines and Comics Retextured
- Updated
    * Nuka-world Plus
    * Creative Perks Plus (includes a few moved perks)
        - Changes to Addiction and addiction related perks, Animal Friend, Dressed for the Apocalypse, and Action Boy/Girl - see mod changelog for details
    * Faction Distribution Framework
    * Backpacks of the Commonwealth
    * SS2 Scrappers
    * UNPC Creatures and Monsters Standalone (fix for Yangtze first mate invisibility)
    * SavrenX Better Robots and HD Liberty Prime (Turret Decal Fix)
    * Lunar Survival Chems and Meds
    * Better Goodneighbor Previsibines
- Removed
    * M2019 PKD Detective Special - That Gun
    * 10mm SMG
    * Boston FPS Fix - Hotfix for UF4P
    * Terrifier Ghouls
    * Real Name Settlers (Soft conflict with LFO)
    * ANiceOakTree's Diverse Children
- Misc
    * Tweaked Makeshift Shotgun balance
    * Increased crafting reqs for T45 lining
    * Fixed a naked raider bug in Greaserats Garb patching
    * Switched LFO Weapon pack for Split Patch version
    * Removed conflicting weapon textures from LookAtMe-Institute Editions
    * Fixed radio sorting
    * Tweaked dynaperf minimum shadow draw distance setting, enabled framerate capping at 60fps
    * Redid Creation Club Paint Skins Profile
        - Enclave and Reily's Ranger skins are no longer required.
        - FDF now has integration plugins broken down by faction, so partial support is available for people who don't own all the textures (paint unlocks and sorting plugin still require full set)
        - Tweaked distribution

# 1.1.2
- Added
    * LookAtMeInstitute-HildaHughes Patch, courtesy of Sarruma
    * Makeshift Shotgun (w/ custom patching)
- Updated
    * Creative Perks Plus (Re-add the 5th rank of Weapons perks)
    * Fallout 4 AI Overhaul
    * SS2
    * SS2 Chapter 2
    * Workshop Framework
- Removed
- Misc 
    * Fixed Armored Jumpsuit and Field Medic Outfit templates
    * Reduced anodyne/stimulant/antimicrobial duration to 3 hours (real life time, not in-game time)
    * Fixed Anodyne sorting
    * Tweaked Antibiotics value
    * Disabled quest sorting (apparent conflict with SS2)

# 1.1.1 The Big Cleanup, Part 2
Finishing up the large scale balance changes started in 1.1.0

- Added
    * SS2 Clothing Injection
    * VUWR Remastered
    * Subversion
    * SS2 Tiny Living
    * Ownership Fixes
    * Nobodies Leaders
    * True Legendary Enemies
    * SS2 City Plan Contest Winners (disabled by default)
    * Damage Threshold Fixes (F4SE plugin to correct a bug in the engine with flat subtraction from damage calculation)
    * Lore Friendly Survival Chems
    * See Through Scopes MCM Settings
    * Green Goo - Lava
    * Protectron HD
    * SavrenX Robots
- Updated
    * SS2
    * SS2 Chapter 2
    * Workshop Framework
    * Faction Distribution Framework
    * Settlers Go Shopping
- Removed
    * Main Quest Choices Extended
    * Unowned Trash
    * Captains Weapons Paints Pack (corrupted patch I couldn't easily fix)
    * ZXC Microadditions (issues with unreachable areas in the optimization patch)
    * Sleepless Nights
    * Green Goo - Green
- Misc
    * More balance tweaks to Elianora's Armors
    * More balance tweaks to Greaserat Garb
    * Rebalanced SS2 armors
    * Removed leftover edits from Backpacks of the Commonwealth levelled lists
    * Minor nerf to Dogmeat's Damage and ability to tear off enemy limbs
    * Minor Patch cleanup and renaming
    * LBPAC Patching and Balance tweaks for Raider Power Armor Chop Shop
    * Added 6.5% Damage Threshold to Power Armor
    * Survival chems now cure the disease, and the resistance lasts 24 hours
    * Cleaned up cooking patch, split into seperate patches
    * Removed undocumented tea
    * Repacked loose textures into the stock game folder BA2s
    * Disabled category roll up in the FallUI
    * Moved Move Workshop Markes to Difficulty and Customization section, disabled by default
    * Added Custom HUD (Based on Vanilla HUD, with a few changes to deal with conflicting widgets)
    * Increased min shadow draw distance in DynaPerf.ini slightly
    * Increased min level for SPECIAL training perks

# 1.1.0
- Added
    * Synthkind Redefined
    * Convienent Bridges (removed unnessary precombines and regenerated)
    * BS Defence - This Settlement Does Not Need Your Help
    * Move Workshop Markers by SKK
    * Fallout4 AI Overhaul
    * No Lockpick Activate
    * Restore Power Armor Frames (Custom rewrite to integrate with LBPAC/CreativePerksPlus)
    * Luxor's Summer (just the ground textures, with tweaked saturation)
    * Beast Whisperer (Completely custom rebuild with Perk integration)
    * No Quest Autostart - NukaWorld, FarHarbour, Vault-tec, BoSFireSupport, Automatron
    * No Agro Impact Landing
    * Start Me Up (Basic Version)
- Updated
    * Hunting Shotgun Lunar Fallout Overhaul Patch
    * SS2
    * SS2 Chapter 2
    * Workshop Framework
    * Creative Perks - Locky Bastard Replacer (harder lockpicking)
    * Super Mutant Redux - No AWKCR and Scaling Fixes
    * Survival Configuration Menu
    * Creative Perks Plus (Nerf to gumshoe rank 2)
    * Resized 10mm Pistol Reworked
    * ANiceOakTree's Diverse Children (Changed to NoSettlers version)
    * Orphans of the Commonwealth (Changed to WSFW Version)
    * Standalone UNPCs (And patches)
    * Lunar Fallout Overhaul
    * Lunar Fallout Overhaul Hardcore Patch
    * ENB binary
- Removed
    * Valentine Reborn
    * Merged Child Mods With Extras
    * Child Outfits
    * CSMs SS2 Leaders
    * Automatron Randomized Bots (functionality replaced in LFO v100)
    * Respawnable Legendary Bosses (balancing this was too much of a pain, it needs proper reduxxing)
    * Respawnable Legendary Bosses Rebalanced 
    * Plutonium Creatures
    * SKK Fast Start (Too many reports of script problems, swapping to Start Me Up Basic)
- Misc
    * Moved Luxors HD Textures out of stock game folder, and into a mod (hopefully this will stop them repacking every update, and fix the cubemap bug)
    * Preston won't ask you to take the castle before level 20
    * Rebalanced and redistributed Elianora's Armors (Requires new game to see improved distribution)
    * Rebalanced and redistributed Greaserats Garb
    * Rebalanced Cross Brotherhood Recon
    * Rebalanced Cross Courser Strigidae
    * Rebalanced Cross Institute Expeditionary Suit
    * Rebalanced Atom's Glory
    * Added a warning message when using the Concord T45. Removed player only trigger on destruction.
    * Rebalanced power armor repair requirements (and added frame scavenging) to better follow Lunar Fallout Overhaul's intended balance.
    * Reverted Power Armor condition based nerf (condition no longer negatively affects DR)
    * Tweaked Cait's appearance
    * Flamers and molotovs no longer make deathclaws and super mutants run in fear
    * Added a Temporary Fix section, with mods only for temporarily working around a CTD
    * Cleaned up patch naming
    * Reduced starting Special points back to default

# 1.0.7 
- Added
    * Hunting Shotgun
    * Hunting Shotgun Lunar Fallout Overhaul Patch (including Moonracer's Edits)
    * Bullet Count Reloaded Hunting Shotgun Patch
- Updated
    * Creative Perks Plus (And Patches)
    * Flicker Fixer
- Removed
    * Lunar Fallout See Through Scopes Compatibility Patch (outdated)
    * 10mmHD (Conflict with Gunmetal Weapons)
    * Cryolator HD
    * Broadsider HD
    * Gauss Rifle HD
- Misc
    * Patched new version of See Through Scopes
    * UNPC - Nerfed chicken egg value, and Fried Egg and Cram Healing
    * Water Weight increased
    * Supreme Behemouth outside V81 moved to Cambridge Crater
    * Removed texture mods replaced with SavrenX Weapons HD (mod was already in the list, those textures were just pruned out)
    * Removed tactical attachments for syringer
    * Empty syringes will now be more common
    * Dr Mouse - legendary effect now gives 15% increased duration to syringes
    * Syringer faction paintjobs now require faction membership to craft

# 1.0.6 Death to the Long Save Bug
The big new thing this patch is the SS2 update, which solves the long save bug.

- Added
    * MM Brotherhood
    * MM Shelter
    * Chem Redux
    * Diamond City Radio Extended
- Updated
    * Lunar Fallout Overhaul
    * SS2
    * SS2 Chapter 2
    * Fresh Facials
    * LFO Fresh Facials Patch
    * Settlers Go Shopping
    * See through Scopes (Hold breath is now melee)
- Removed
    * D.E.C.A.Y.
    * More where that came from (Diamond City Radio)
- Misc
    * Tweaked minigun to suck less at longer ranges
    * Applied height/weight randomization to new faces in fresh facials

# 1.0.5 
- Added
- Updated
- Removed
    * Beast Whisperer
    * Car Physics Death Bug Fix (redundant with LFO changes)
- Misc
    

# 1.0.4 Hotfix
- Added
- Updated
    * SS2
    * SS2 Chapter 2
- Removed
- Misc
    * Fixed chem crafting healing freeze

# 1.0.3 - Provisioners and Power Armor
This update brings big changes to Survival Fast Travel, and to power armor.
_This update is save-safe as long as you are not using a city plan from Rise of the Commonwealth, if you are it is recommended to switch to a different plan before updating, as they have been removed due to being buggy._

- Survival fast travel has been removed from the explorer perk, and added to the Local Leader perk (the 2nd rank now allows you to fast travel by talking with your provisioners). The fast travel version of the explorer perk is still available in the optional section, if you've already taken explorer 2, 3 or 4 I recommend enabling.
- Power Armor health now matters, damaged power armor will protect you significantly less than power armor in full repair, keep an eye on it's condition with the new stats widget.
- If you want to randomize the bobblehead locations in your existing save, go stand on the entrance to Vault 111.
- Stats for various clothing with railroad weave have been changed, so they have lower stats, but spawn with an undercoat. Unfortunatly, this means if you already have them, you will just get the lower stats.

- Added
    * GKX Random Valuable Replacer (Custom version that only does bobbleheads)
    * Cambridge Ghouls Horde
    * Scrappable power armor pieces
    * Individual NPC Face Remake (Preston)
    * Journey Survival Fast Travel (w/ Creative Perks Plus integration patch)
    * Caravan AI Tweaks
    * Def Widgets Core
    * PA Stats widget
- Updated
    * ENB Helper
    * UNPC Creatures and Monsters Standalone
    * Creative Perks Plus (and patches)
    * Lunar Fallout Overhaul
- Removed
    * Rise of the Commonwealth (apparently it is a known crash risk)
    * Unique Gun Parts - Combat Rifle (incompatible with See Thru Scopes)
    * Thinner Assault Rifle
    * Tougher Cars Durable Vehicles (redundant with new LFO changes)
    * Vault 81 - GOAT Sequence Patch
- Misc
    * Backpacks of the Commonwealth
        - Cleaned mod, Removed startup quest and levelled list edits, removed added location. All backpacks are now only hand placed found in world.
    * Starting equipment for SKKFastStart patched to better match LunarFalloutOverhaul
    * Fixed atom cats outfits, they should now wear pants correctly
    * Tweaked Greaserat Garb injection, they should show up more often now as compared to Elianora's stuff
    * Tweaked distribution of Elianora's Armors slightly
    * Fixed precombines in Harbourmaster hotel lobby
    * Added naming to undercoats, tweaked distribution, reworked clothing balance for clothes with undercoats
    * Removed caps from synths
    * Tweaked Preston Garvey's morphs and starting outfit (his colonial duster now starts in his inventory)
    * Removed 4 textures from 2287
    * Replaced a few more low res textures from A Forest
    * Integrated Moonracer's rebuild of Fresh Facials for better LFO compatibility
    * Wearing a helmet now cancels headshot damage bonus
    * Power armor now has an armor and energy resist penalty based on how damaged it is
    * Danse's power armor has been nerfed to bring him better in line with other companions
    
# 1.0.2
- Added
    * Dynamic Performance Tuner
    * Doc Drumlin
    * Institute Floor Fix
    * SavrenX Dogmeat 4k
    * Water Enhancement Textures
    * Smoke and Fire Enhanced Textures
    * MM Journals
    * SavrenX Weapons HD (Melee +  Institute Lasers)
    * Dismemberable EVB
    * Indubitable Ivy
    * RoNin1971's UHD Landscape Enhancement - Plants
    * Handmade Unique Eyes
    * Handmade Unique Eyes Ghouls
    * Power Armor HUD (by Gopher)
- Updated
    * Sim Settlements 2
    * Sim Settlements 2 Chapter 2
    * TrueSight ENB
    * Creative Perks Plus
    * Creative Perks Plus - Lunar Patch
    * Creative Perks Plus - Beastmaster replacer
    * Creative Perks Plus - Locky Bastard (adds popup message on lock break)
    * Inside Jobs
    * Private Profile Redirector
- Removed
    * Crows and Creatures Collection
    * Burly Bunkers
    * Spiffy's Military Vehicles Retextures
    * FO4 Rain
    * Alternative magazine covers and more
    * Burnt Magazines and Comics Retexture
    * Eyewear and mask retexture
    * The Eyes of Beauty
    * Ghastly Ghoul Eye Textures
    * Smaller Institute Weapons (Conflict with 3dScopes)
    * Lootable Vault Crates
    * Institute Weapons Redone
- Misc
    * Added QoL-NerfCodsworthFlamer optional plugin
    * Regenerated Navmesh for Immersive Drumlin Diner
    * Repacked Bottle Labels Overhaul with dirtier texture selection
    * Renamed SMR Balance plugins for easier understanding
    * Fungal forest 2K swapped for 4K, repacked textures
    * Redder Rocket 2k swapped for 4k
    * True Caves 2k swapped for 4k
    * Gritty Subway Stations 2k swapped for 4k
    * A Forest repacked textures (removed low res textures and conflicts)
    * Cleaned up ELi's Armor Compendium levelled list injection
    * Bugfix to Lining distribution (please report deathclaw skin lining spwaning before level 80)
    * Repacked DECAY
    * Removed exterior edits from DCVendorClutter (I loved the clutter, but it was destroying performance in the market)
    * Nerfed reward from Preston for museum quest
    * disabled fast travel option on scavver map
    * Fixed medic perk description
    * Tweaked Legendary Bosses - moved bear slightly farther, made roachzilla bigger

# 1.0.1 Hotfix
- Added
- Updated
- Removed
- Misc
    * Fixed load order
    * Resolved conflicts between WX Facepaints and Eyes of Beauty
    
## 1.0.0
- Added
    * A LOT of textures that were previously downloaded with the BiRaitBec repack, are now downloaded separately.
    * 10mm SMG (part of LF weapons patch pack)
    * M2019 PKD Detective Special - That Gun (part of LF weapons patch pack)
    * FDF - Combar armor decals
    * Immersive Supermutant Orders
    * Lunar Fallout Hardcore (Optional)
    * Hollywood Lasers (Applied to institute lasers only)
    * No more cash register sound when XP gain
    * Fresh Facials (custom height/weight distribution added)
    * Plutonium Creatures (only used as a resource to only apply skins to Legendary Respawnable Bosses)
    * Gun Smoke
    * Unique Gun Parts - Combat Rifle
    * Icebreaker - Settlements - Settler Dialogue Overhaul
- Updated
    * Sim Settlements 2
    * Sim Settlements 2 Chapter 2
    * Workshop Framework
    * Lunar Fallout Overhaul
    * Lunar Fallout Weapon Patch Pack
    * Faction Distribution Framework
    * Mod Organizer
- Removed
    * BiRaitBec's Texture Repack (Added a massive amount of redundant textures)
    * Less Annoying Water Rain Ripples (redundant with true nights)
    * Rowan's Request - Technical Documents
    * Settler and Companion Dialogue Overhaul
    * Discord Rich Presence (cool, but unnessary bloat)
    * Combined Combat XP (removed cash register sound completely instead)
    * 3rd person camera tweaks
    * Campsite - Simple Wasteland Camping (the list isn't supposed to be a survival simulator)
    * Quick reflexes
    * Abandoned Hub (This bypasses the need for SS2 Caravan Plot fast travel, and I want to focus the list on the SS2 gameplay more)
- Misc
    * Legendary Respawnable Bosses - Moved Ancient Commonwealth Bear, Roachzilla, and Frenzied Radstag spawns out of quest related areas
    * Repacked and optimised loose textures for a bunch of mods
    * Disabled custom shotgun edits (reduntant with the new tweaks in LFO)
    * Compatibility patching for new version of Lunar Fallout Overhaul
    * Improved compatibility patching for clarity
    * Moved RailRoad Redone to the precombine section, to resolve conflict with clarity
    * Re-reduxed Diamond City Outskirts (custom version that contains only the exterior edits)

## 0.4.0
- Added
    * No More Glowing Mouths
    * Realistic Ragdoll Force
    * Quick Reflexes (including custom script tweaks)
    * Melee Bangs
    * Pistol Bangs
    * Smaller Institute Weapons
    * Baseball Bat Grips
    * Better Third Rail - PATCH Pre-Vis and Navmesh
    * Cola Cars Overboss Fix
    
- Updated
    * Scrappers SS2 Addon
    * Sim Settlements 2
    * Sim Settlements 2 Chapter 2
    * Workshop Framework
    * Reunions - Sister Edition
- Removed
    * Better LOD
    * Better Goodneighbor Fix
    * Better Third Rail (superceded by it's patch)
    * Far Harbor - Cliffs Edge Hotel Wall Rest Ring Lower Fixed
- Misc
    * Regenerated LODs with improved conflict resolution (fix for Diamond City LOD building problems)
    * Optimised and packed: Kirs Freckles, Appealing Moles, Immersive Mouth and Teeth, WX Face Paints and Dirt, Hair Tones Redux, The Eyes of Beauty, Ghastly
    * Adjusted load order for Tales from the Commonwealth Visual Fixes

## 0.3.4
- Added
    * True Sight ENB
    * ENB Helper for Fallout 4
    * FO4 Rain
    * Faster Getup
    * Combined Combat XP
    * No Power Armor Battery Pathing
- Updated
    * Abandoned Hub - Underground Railroad ReRedux
    * Creative Perks Plus
    * Creative Perks Plus - Lunar Fallout Patch
    * Sim Settlements 2
    * Sim Settlements 2 Chapter 2
    * CSM's Vanilla Leaders
- Removed
    * Visceral ENB
    * Active Effects on HUD
    * Companion Craftable Weapon Grips
- Misc
    * Created balance patch for Respawnable Legendary Bosses
    * Cleanup of settings holotape crafting
    * Removed crafting of childrens clothing
    * Tweaked shotgun range & damage penalties (should feel MUCH better, enemies with shotguns need to be feared now)
    * Reduced rate of loot in vault crates
    * Repacked textures (again) to (hopefully) reduce/resolve brown face issues.

## 0.3.3
- Added
    * Rocket-Axe - SuperSledge Standalone mod
    * Reunions (Sister Edition)
    * Hilda Hughes An Institute Story
- Updated
    * Sim Settlements 2
    * Sim Settlements 2 Chapter 2
    * Workshop Framework 
    * Abandoned Hub - Underground Railroad ReRedux
    * Settlers Go Shopping
    * Discord Rich Presence
- Removed
- Misc
    * Fixed jet variants in IAF - Lunar Patch
    * Tweaked minutemen radiant quest location selection

## 0.3.2
- Added
    * Sim Settlements Chapter 2
- Updated
    * Jolly Item Sounds
    * Workshop Framework
    * Sim Settlements 2
    * Sim Settlements Extended
- Removed
- Misc
    * Fixed LunarPlus - 3dNPC Ghost record
    * Reran sorting script

## 0.3.1
- Added
    * Components Redone Copper Fix
    * Recruit Kat and Gus
- Updated
    * 10mm Pistol Resize Update
    * 4estGimp Complex Item Sorter Enhancements
    * Laser Weapons 1st person Reposition
    * F04Edit
    * Greaserats Garb
    * Creative Perks Plus
    * Super Mutant Balance Options (experimental- feedback needed)
- Removed
- Misc
    * Repacked and Optimised textures for stock game folder
    * Repacked and Optimised textures for Super Mutant Redux
    * Repacked and Optimised textures for Eli's Armor Compendium
    * Fixed creation of [NODELETE] folders
    * Cleaned up CC content in non-cc profile

## 0.3.0
- Added
    * 10mm Pistol Resize Update
    * Optimization Patches Collection
    * Luxor's HD Textures
    * Captain's Weapons Paint Pack
    * FDF Captain's Weapon Paint Pack Distribution (Curtesy of CaptainLaserBeam)
    * Doors not Walls
    * River Fix
    * Conduit Connection Fix
    * Vault-Tec Lights Mesh Fix
    * Nuka World Novatron Assaultron Torso Fix
    * Flickering Roof Mesh Fix
    * Nuka-World Fixes the East Entrance to Nuka-Town USA near Fizztop
    * Far Harbor - Cliffs Edge Hotel Wall Rest Ring Lower Fixed
    * Vault 81 - GOAT Sequence Patch
    * Fixed Alpha Maps
    * Less Annoying Rain Ripples
    * Assaultron Left Hand Hydraulic Frame Arm Mesh Bug Fix
    * Nukaworld Bottle Scenery Fix
    * Vertibird Jump
    * Fallout Priority
    * Remember Lockpicking Angle - Updated
    * Subsurface Scattering for Supermutants
    * Companion Active Wait
    * Sleepless Nights
    * Jump Grunt
- Updated
    * Discord Rich Presence
    * Jolly Item Sounds
    * Ruined Homes and Gardens
    * High FPS Physics
    * xSE Plugin Preloader
- Removed
    * Start Me Up - Full
    * Phyop Light
- Misc
    * Implemented Stock Game Folder system
    * Regenerated sorting patch
    * Repacked textures based on Luxor, instead of Phyop
    * Added HighFPSPhysics Custom .ini file for users with high FPS/Free-g-sync monitors
    * Regenerated FO4 LodGen
    * Added empty [NODELETE] folders for Creation Club Skins, and for Cross Skins

# 0.2.3
- Added
- Updated
    * 4estGimp Complex Item Sorter Enhancements
    * Recruit Charlie and Clinton as Settlers
    * ENBSeries
- Removed
- Misc
    * Fixed gunmetal raider armor paints installaation
    * Regenerated sorting patch

## 0.2.2
- Added
    * Discord Rich Presence
- Updated
    * Creative Perks Plus
    * Recruit Virgil as a Settler
    * Survival Configuration Menu
    * Atom's Glory
    * Complex Vendors
- Removed
    * Dak's Combat Rifle remesh (to allow for skin support)
- Misc
    * Restored weaponTypeRifle to double barrelled shotgun (should allow for correct holstering position)
    * Reverted armor changes to SKK Scaver Faction
    * Updated Item Sorter Script, and reran sorter


## 0.2.1
- Added
- Updated
- Removed
- Misc
    * Fixed Jet in IAf-Lunar patch
    * Rolled back High FPS Physics due to issue with starting new games - investigation required



## 0.2.0 (Not save-update safe, due to Mercenary Pack removal)

If you want to update from 0.1.2, you can just add [NODELTETE] to the Mercenary Pack and Injected Mercenary pack mods, to prevent wabbajack from deleting them.

- Added
    * Fixed Protectron Textures
    * No More Glowing Watercoolers
    * Decayed Army Fatigues Fix
    * Eye Normal Map Fix Fallout 4 Edition
    * Jamaica Plain Navmesh Fix
    * Take your cores
    * Holotime HUD Widget
    * Recruit Miranda as Settler From Acadia
    * Recruit Virgil as Settler
    * Recruit Shelly Tiller as Settler
    * Balance patch for Inside Jobs
- Updated
    * Lunar Fallout Overhaul
    * Unique Creatures Standalone Scaling Tweaks
    * Greaserats Garb (and patch)
    * High FPS Physics Fix
    * Jolly Item Sounds
    * Settlers Go Shopping
- Removed
    * The Mercenary Pack (changes the gunner asthetic from vanilla too much, I've decided to revert)
    * Mercenary Pack Injected 
- Misc
    * Split "Settlers" mods out from "Settlements" section
    * Split "SS2 Plans" mods out from "Settlements" section
    * Updated Complex Sorter patch

## v0.1.3
- Updated
    * Updated Lunar Fallout Overhaul
    * Updated Recruit Charlie as Settler
    * Patched Settler Dialogue Overhaul (Credit to MasterHamper)
- Added
    * Balance patch for 3dNPCs (Credit to MasterHamper)
-Fixed
    * Lunar -Mercenary patch to not spawn naked gunners

### v0.1.2
- Added
    * Added wabbajack_include tag file to complex sorter cache, so the sorter can be rerun on installs
    * Added Recruit Clinton and Charlie as Settlers
    * Added Recruit Cora - lvl 4 Merchant from Nukaworld
    * Added Recruit Jule from Arcadia
    * Added Recruit Thirsty and the Rad Poisoned Settler
    * Added Recruit Mac As A Settler
    * Added patch OnlyBlueVaultSuits.esp to prevent colored vault suits from spawning by default - disable 
- Updated
    * Updated Jolly Item Sounds
    * Updated Wasteland Ventures
- Removed
    * Removed Pra's Random Addons 2 (is seems to cause instability at startup with the scripts)
    * Removed A Far Harbour Story (unintentional inclusion)
- Misc
    * Moved some patches to nexus downloads (instead of in-lining them into the wabbajack file)
    * Conflict resolution improvements for SKK Red Rocket Factions (still has non-critical navmesh conflicts with 3DNPCs)
    * Moved survival damage variables from LunarFalloutPlus to the optional damage plugins for people who want the vanilla values to allow Clothing Coloured Variety's suit colours to spawn


### v0.1.1
- updated ENB, replaced subtle enb with visceral
- added npc mods present in merge to the slideshow
- removed unused mods from compile to prevent "unable to download" errors
- Added [NODELETE] to the repacked textures to prevent rehashing and rebuilding during updates

### v0.1.0 Initial pre-release