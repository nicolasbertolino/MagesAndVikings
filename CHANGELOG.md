# Mages & Vikings — Full Changelog

---

## Version 2.5

>[!IMPORTANT]
>A new game is required!

> Note: The list has been updated from version 1.5.97 to version 1.6.1170. If you have customized the list with [NoDelete], be aware you may have to update some mods on your side.

### Gameplay

**Removed:**
- Leveling Freedom - Configure your XP Curve — Removed in favor of a faster leveling curve, especially in early levels.
- Block While Casting
- NPC Spell Variance — Caused some NPCs to use fists instead of spells (seen on Lucien, Minorne and some dragon priests).
- STB Quick Hotkey Cast — Quick casting is now handled by Wheeler Refined.
- Wade in Water Redux - Swimming Overhaul — Replaced with Loki's Wade In Water. Swimming is no longer affected by the armor you wear.
- Swift Potion NG — In favor of True Flasks NG.
- Smart NPC Potions - Enemies Use Potions and Poisons — In favor of True Flasks NG.
- Potion Combiner for Apothecary — In favor of True Flasks NG.

**Added:**
- True Flasks NG — A complete rethink of the potion system inspired by modern action RPGs. Say goodbye to carrying 200 potions — you now have a set of regenerating flask charges instead, bringing a Souls-like or Cyberpunk-style healing loop to Skyrim.
- For Honor Reforged — A complete rebuild of For Honor in Skyrim with expanded mechanics and skill-based balance that rewards deliberate, thoughtful play. Check the gameplay-guides channel on Discord for the full breakdown.
- Parrying RPG — When two characters swing at each other at the same time and their weapons connect, the attacker recoils and deals no damage.
- Disable Bashing for NPCs — NPCs can no longer use bashing, which cleans up combat.
- Perfectly Valid Wards — Wards now block melee attacks, arrows, and shouts, and can even reflect spells back at casters. All of this is integrated into the Restoration perk tree, so you'll need to invest in it to unlock the full potential.
- Knockback SKSE — Melee hits now push enemies back slightly, keeping them at the right distance during combat and avoiding that awkward clipping-into-each-other feeling.
- Ricochet - Arrow Physics Framework — Arrows and bolts now ricochet realistically off surfaces. A small detail that gives more angles opportunities (looking at you sneak archers).
- Constellations - Additional Player Skills and Firmament — Adds 6 brand new perk trees to the game: Hand-to-hand, Athletics, Sorcery, Horseman, Exploration and Philosophy. All fully integrated into the vanilla skills menu, and they open up some really fun new build possibilities.
- HorsePower - Modernized Horse Riding — Pretty much a complete overhaul of horse riding: new follow-up attacks, directional animations, improved handling, in-place turns, new ragdoll and sprint behaviors. Combine this with the new Horseman perk tree from Firmament and you can go full Mongol horse warrior build.
- AutoHorse — Draw a marker on the map while mounted and your horse will automatically travel there. Activate with Z / RT.
- Lock Bashing — You can now bash locks open with brute force. The higher your health and stamina, the better your chances.
- Argentum - True Weakness To Silver — Undead now take 200% damage from silver weapons and 50% from everything else. Wielding silver weapons actually feels meaningful now.
- Perk Point Potion — A rare elixir found in some boss chests that grants a perk point when consumed. More distribution will come in future updates.
- Simple Werewolf Looting — While in werewolf form, the default interaction with containers is now "Search" rather than "Feed." Press Shift+E if you want to feed from corpses the vanilla way.
- Faster Reanimation - 25 Percent Faster — The reanimation animation is noticeably shorter, making Conjuration feel snappier in combat.
- Sensible Dawnguard Start — You can no longer join the Dawnguard just by reaching level 10. You must first complete Laid to Rest, which makes joining the faction feel more earned.
- Companions Radiant Edit - Only Bandits from Farkas — Farkas now only sends you to bandit hives.
- Slightly increased spawn interval time from world encounters.

### New Content

**Removed:**
- Voidborn - Chakra's Creatures
- Hungers SE
- Bogmort - Mud Monsters of Morthal Swamp
- House of Horrors - Delayed Start — Can now be started as soon as you enter Markarth.

**Added:**
- VIGILANT SE — An absolutely unmissable dark quest mod following the Vigilants of Stendarr. If you enjoy grim, story-driven content this is one of the best quest mods available. Requires level 25 and completion of the vanilla House of Horrors quest in Markarth, then head to Dawnstar's Inn to begin.
- A Friend in Mead - Quest Mod — A charming little quest where you encounter an Argonian courier in Skyrim's taverns with some strange stories to tell about his travels.
- Werewolf Behemoths — Mihail Monsters and Animals. Massive werewolf variants now roam the wilds, not something you want to stumble into unprepared.
- Wendigo Creature Mod — A new predatory creature that stalks the night. Watch yourself after dark.
- Farm Geese — Mihail Monsters and Animals. Lovely geese to bring more life to settlements.
- Hedgehog In Skyrim — Small, harmless, and delightful. Hedgehogs now roam Skyrim's forests.
- Barn Owls — Mihail Monsters and Animals. Barn owls now glide through the night, circling barns, stables, farms and towers in search of rodents. A wonderful atmospheric touch.
- Starfish on Shores — Mihail's Shards of Immersion. Starfish now decorate Skyrim's coasts, lying on sands, clinging to rocks, and resting on the seabed.
- Dwarven Gear Walker — A curious little dwarven automaton you can recruit as a follower. Find him in the Dwarven Storeroom in Mzulft.
- Chitin Bow SE — A great-looking new bow craftable at the forge under Elven smithing.
- House Guard Set by Pulcharmsolis — Distributed to Ogol, the Orc warrior found in Largashbur.
- Arcane Mage Armor by FafnyB — Distributed to some alchemists such as Arcadia in Whiterun.
- Dibella's Grace (HDT-SMP) — A beautiful new outfit distributed to the residents of the Temple of Dibella in Markarth.
- Fuse00 Artificer Armor — Distributed to Sam Guevenne, the Breton conjurer who challenges you to a drinking contest.
- Dark Apprentice (3BA SMP) — A striking new set distributed to Aranea Ienith, the Dunmer worshipper of Azura.

### Fixes

**Added:**
- Fixed animations previously not or only partially working due to the switch to Pandora (Bathing in Skyrim, Immersive Interactions).
- A-Pose Bug Fix - Universal Behavior Runtime — An SKSE plugin that corrects animation and behavior errors at runtime, to put an end to the A-pose freezes.
- Stuck Underwater Visuals and Sounds Fix SKSE — Fixes that annoying bug where underwater effects stay on screen after surfacing.
- Lingering Subtitles Fix — Fixes subtitles that stubbornly refuse to disappear after conversations end.
- Show Player In Menus - Persistent Zoom Fix — Fixes the zoom level resetting to default every time you exit the inventory menu.
- ShowRaceMenu - NG — Fixes stats, attributes, and levels getting messed up when changing race from the character creation menu.
- Delphine Skyhaven Bugfix MQ203 — Fixes Delphine getting stuck when entering Sky Haven Temple for the first time.

### Animations

**Removed:**
- Dynamic Candles - Blow Them Out and Light Again
- SIGMA - 1st Person Animations Series — Temporarily removed due to issues with weapon reach.

**Added:**
- Race-based movement animations — Previously, movement animations changed based on the armor type worn. They are now race-dependent, which feels far more natural and opens up more interesting character expression.
- Faction and follower movesets — This is a big one. Dozens of new movesets have been distributed to followers and factions. Each follower now has a unique moveset based on their main weapon, making them feel more alive and distinct to fight alongside. Sons of Skyrim (city guards and Stormcloaks) and the Imperial Legion also have their own distinctive fighting styles. Lots more to expand on here in the future.
- Dynamic Dodge Shot - Complete Balance and Integration — Dodge shot is no longer available in heavy armor, instead you'll do a regular dodge. Dodge Shot now also requires 30 stamina; if you're below that, a regular dodge animation kicks in instead.
- TK Dodge RE Addon — Adds in-game settings for all TK Dodge options. Configure your preferred key through the SKSE Menu Framework (press F7 to open it).
- Immersive Weapon Switch — Weapons are now automatically sheathed and unsheathed when switching between them.
- First Person (FP) Inertia and First Person (FP) Camera Settle — Adds satisfying camera and movement inertia to the first person viewmodel. A subtle change that makes movement feel much more grounded.
- UNDERDOG Animations - OAR — Only select animations from this mod were kept.
- New Creature Animation - Werewolf

### Visuals

**Added:**
- Arms of Atmora - Nordic Bronze Weapon Pack — All Ancient Nord Weapons have been replaced with these stunning new models.
- Thalmor Investigator HDT-SMP Armor by Fuse00 — Used as a replacer for vanilla Thalmor robes. The Thalmor finally look as intimidating as they should.
- Phantasm - Ghost Replacer — Replaces non-unique vanilla ghosts with spookier versions.
- Dynamic Bloodpool Framework — A mesh-based, script-free system that generates animated, fluid bloodpools on dead enemies. Gruesome in the best way.
- Frost Atronach SE by 4thUnknown — Completes the trilogy of visually overhauled atronachs.
- DD Lydia Replacer ESL 2.0 — A fierce new look for Whiterun's most iconic housecarl.
- NPC Diversity - Fat People of Skyrim — Only a handful of NPCs from this mod were kept.
- Divergence - Skytone - Standing Stones — Clean new textures for the standing stones.
- TB's HD Photorealistic Whiterun Roads — Better-looking dirt roads for Whiterun with improved performance over the previous option.
- No Grass in Caves — Removes grass in a few caves where it never made sense visually. This should also fix the occasional freeze in Fallowstone Cave caused by Lux.

### UI & Audio

**Added:**
- Wheeler Refined — A stability and feature overhaul for dTry's Wheeler that keeps the original idea and assets while fixing long-standing bugs and CTDs. Expect smoother gamepad use, direct shout (replacing STB Quick Hotkey Cast) and quick spell casting, new indicators, auto scaling and more.
- Tween Menu Overhaul — Adds convenient shortcuts to other menus directly from the tween menu: Order Squad, Skyrim Character Sheet, Bestiary, and Photo Mode.
- Skyrim Character Sheet — A new character overview screen. Will be replaced with Character Menu SE by JPSteel2 in the future once NordenUI support is added.
- Quest Item Icon — Adds a small quest marker next to active quest items in the inventory.
- Lore-Friendly Main Menu Compendium (Wallpapers)
- Less Boring Loading Screens Redux
- The Sound of Skyrim (Reimagined) — A new optional music overhaul that stays close to the vanilla feel while expanding on it beautifully. Enabled by default — give it a listen before switching it off.
- The Received Series by LeoMaximus — Stunning new voice effects for several characters: Mephala, Arch-Curate Vyrthur, Lu'ah Al-Skaven, Peryite, Hircine, Nocturnal, and Augur of Dunlain.

### Miscellaneous

**Removed:**
- Gamepad++

**Added:**
- Auto Audio Switch — Plug your headphones in or out while the game is running and audio switches outputs automatically. Small quality-of-life addition that removes a genuine annoyance.
- New LOD option in MO2 under Customize Your Experience — Choose between Full LODs or Performance LODs depending on your setup.
- Serana Dialogue Expansion — Greatly expands Serana's dialogue. Note that the Romance optional file was not included — you'll need to add it yourself if you want that.
- Chatty NPCs and Followers — Vanilla NPCs now greet each other, check in on one another, and even talk to your vanilla voiced followers. The world feels more alive as a result.
- You Reek - Updated — People will now complain when your hygiene has hit rock bottom. Go bathe.
- Droppable AE Notes — Allows you to drop or store notes and keys from Creation Club content that would otherwise clutter your inventory forever.

And many more fixes and improvements!

---

## Version 2.4

>[!IMPORTANT]
>A new game is required!

### Gameplay

**Removed:**
- TK Dodge Attack — Removed due to bugs (added in the previous update). For Honor dodge system has been reintroduced for third person as a result.
- Reverted all perk tree nerfs back to default values.

**Added:**
- Shadow Opportunist - A Sneak Addon — Turns detection into an advantage by slowing time for everyone but the player upon being detected. Integrated into the Sneak perk tree.
- Pactbinder - An Adamant Addon — Adds new perks and mechanics to make Conjuration more interesting.
- Architect - An Adamant Addon — Adds new perks and mechanics to make Smithing more interesting overall, beyond just crafting and tempering armor and weapons.
- Bloodwright - A Scion Addon — Adds new perks, features, and abilities to make Vampirism more interesting.
- Shortage of Shouts - A Stormcrown Addon — Adds new perks and mechanics to make shout-focused builds more interesting.
- Wade in Water Redux - Swimming Overhaul — Slows down the player when in water based on armor worn.

### New Content

**Removed:**
- Bjorn - Fully Voiced Follower — Removed due to constant background quest processing causing excessive script calls.

**Added:**
- New Follower: Willow of Riften — Custom voiced Bosmer follower.
- Missives - Voice and Quest Expansion — Adds 20 new types of Missives.
- Why I Came to Skyrim - Origin Stories — Provides 40 possible starting quests to give initial purpose to your character. Read the book on the floor of the Skyrim Unbound starting room.
- Sirens — Chakra's Creatures
- Forgotten Vale Guardians — Chakra's Creatures
- Voidborn — Chakra's Creatures
- Swamp Skeletons — Chakra's Creatures
- Drowners — Chakra's Creatures
- Leshens — Chakra's Creatures
- Realistic Eyeglasses SE — Adds several eyeglasses to Skyrim. Fully enchantable, craftable, lootable, and buyable.
- DDV - Skyrim Santa SAM II Himbo — New outfit.

### Visuals

**Added:**
- New ENB Choices: Azurite Horizons ENB, Cabbage ENB, Dawnfire Azurite III ENB, Ebony Weathers and ENB - Reborn, Kauz ENB, PI-CHO ENB
- Riverwood Falls — Waterfall Additions for Riverwood
- Nature's Respite - Hunters Rest Overhaul — Overhauls Hunter's Rest with a brand new shack model and lore-friendly clutter.
- Hovels of Hagravens — A Forsworn Tent and Clutter Replacer
- JK's Blue Palace
- HFs - Wooden Horse — Wooden horse head figurine added as decoration.
- HFs - High Hrothgar Column — Remodel
- HFs - Totem — Adds a wooden Odin totem to some Skyrim interiors.
- Less Visually Obtrusive Cloak Spell Effects
- Chaurus HD
- Netch HD
- Silt Strider HD
- HDT-SMP Vanilla Miraak Robes
- eeekie's Gore Renewed — New look for Gore.

### Miscellaneous

**Removed:**
- Widget Addon - Bathing In Skyrim Renewed — Removed the HUD widget for bathing due to constant multiple script calls.
- Undead FX — Removed due to high number of script calls.

**Added:**
- Pick Up Radius — Loot the same or similar items in a radius upon pickup.
- Feeding Perk Notification — Changes notification messages when you earn a new perk for Vampire Lord or Werewolf.
- Talkative Dragons
- Talkative Seekers — Mihail Monsters and Animals
- JellyFishFP Movement Remake — 1st person animations series
- JellyFishFP TORCH — 1st person animations series
- SIGMA - Magic Animations - 1st Person
- Dynamic Tooltips — Displays context-sensitive/runtime-dependent pop-ups when you hover over items, showing details like quest associations, ownership, or spell book magicka costs. Powered by LoreBox.
- Switched from Nemesis Unlimited Behavior Engine to Pandora Behaviour Engine Plus.

---

## Version 2.31.1

> Safe to update

### Fixes
- Fixed the wheeler not opening properly when reaching the menus via Tab (bug with Typing Mode).

### UI
- Added Spell Classes, which attaches a Druidic label to specific spells. Useful when picking the appropriate trait from Biggie Traits.


## Version 2.31

>[!IMPORTANT]
>A new game is required!

### Fixes
- Fixed Olfina Gray-Mane's invisible face.

### Gameplay

**Added:**
- Candlehearth - An Inn Overhaul — Adds extended inn rentals and safe storage to every inn in Skyrim.
- Journeyman - A Fast Travel Overhaul — A lightweight, highly compatible fast travel overhaul that restricts fast traveling unless you have prepared a travel pack.
- Better Carriage Destinations — Added to balance with Journeyman. Use your map to select carriage destinations and travel anywhere you've already discovered. Carriages have never been more useful!
- Missives - Voice and Quest Expansion — Expands missive board quests with 20 new missive types.
- The Taste of Death - Quest Addon — Extends the vanilla quest "The Taste of Death," allowing you to root out the Cult of Namira and bring them to justice.
- TK Dodge Attack — Inputting an attack while dodging now results in a dodge with a follow-up attack for smoother, more dynamic combat. Side dodges from For Honor in Skyrim have been disabled due to this addition.

### Visuals

**Added:**
- Praedy's Staves AIO - SE — Overhauls Skyrim's staves, giving each staff type and enchantment its own unique appearance.

---

## Version 2.3.1

> Safe to update

### Fixes
- Fixed General Tullius having an invisible face.
- Fixed clipping issues with plants and a tree in Solitude.
- Updated Hotkey Reminder to remove superfluous keys.
- Fixed a crash that occurred when interacting with Fertile Soil.


## Version 2.3

>[!IMPORTANT]
>A new game is required!

### Fixes & Improvements
- Performance has been improved in the entire Rift area, Riften, Solitude, and Whiterun.
- Added Player Panting Loop Fix.

### UI
- Replaced Oathvein UI with Norden UI by the same author.

### Gameplay

**Removed:**
- Simple Follower Sandbox — Removed due to bugs.
- SunHelm Survival and Needs — Replaced with Starfrost - A Survival Overhaul by SimonMagus.

**Added:**
- Skyrim's Got Talent - Adamant Bard Perks Synergy — Integrates the Adamant Bard Perks addon with Skyrim's Got Talent, adding a new Bard branch to the Speech perk tree.
- Holy Templar Magic Shield Re-equips Spell on Despawn
- Nobushi | Spear Moveset for NPCs
- SoulCalibur VI Kilik | Quarterstaff Moveset for NPCs
- Saint Jiub's Bookmarks — Adds visual indicators to the locations of Saint Jiub's Opus pages in the Soul Cairn.
- Infiltration - Quest Expansion
- Caught Red Handed - Quest Expansion
- The Heart of Dibella - Quest Expansion
- College of Winterhold - Quest Expansion and Immersive College NPCs
- Knight of the North - Divine Crusader Reworked — Overhauls the Relics of the Crusader quest from Anniversary Edition.
- Cult of the World Eater - Dragon Priests Buff Alduin
- Defeat the Dragon Cult

### Visuals

**Removed:**
- Grand Solitude — Removed due to incompatibility with JK's Interiors. Replaced with Fortified Ramp to Castle Dour and Spaghetti's Cities - Solitude.

**Added:**
- Ivy's Stendarr's Beacon Overhaul
- Whiterun Temple Bench Replacer
- Whiterun Exterior Small Addon
- Freak's Floral Meadows — Added for all regions except Tundra, which retains the current grass from Nahl Frod.
- Ivarstead Source
- Mammoth Expansion — Mihail Monsters and Animals. Made a replacer for vanilla mammoths.
- Ulfric Stormcloak's War Axe Replacer
- Weapon Animation (Mace of Molag Bal)
- Weapon Animation (The Staff of Magnus)
- Weapon Animation (Volendrung)
- Weapon Animation (Skull of Corruption)
- PELTAPALOOZA - Special Edition
- Skeps of Skyrim - Diverse Beehives — Adds fifteen different skeps (rustic beehives) to farms and villages around Skyrim.

### Miscellaneous

**Added:**
- Cheeky Kids — Makes children run up to NPCs and throw random insults at them, with appropriate responses.
- Home in a Hat - Haven Bag Inspired House by Elianora
- New Outfit: ELLE Knight Winds 3BA - BHUNP
- New Outfit: EMP - Ritual Armor of Boethiah
- New Outfit: Artifacts - The Breton Paladin — Paladin armor set and CC Divine Crusader replacer for Knight of the North.
- New Outfit: Forgotten Princess - CBBE-UUNP SE
- New Creature: Dryads — Mihail Monsters and Animals
- New Creature: Alit (Creature Series pt.4) SE
- New Creature: Shroom Beetles (Creature Series pt.6) SE
- Eivor Animations - AC Valhalla Animations Replacer — New movement animations distributed to Orcs.

---

## Version 2.2

>[!IMPORTANT]
>A new game is required!

### Gameplay

**Removed:**
- Essential Favorites — This mod prevented selling items that were in a stack with a favorited one.
- Individual Shout Cooldown Remake
- Bow Rapid Combo

**Balance & Fixes:**
- Restored vanilla fall damage values (less punishing).
- Nerfed most Adamant perk trees for better balance.
- Adjusted sell values for outfits and lootable items to prevent excessive profits.
- Fixed a bug where normal attacks following a power attack would drain stamina as if they were power attacks.

**Added:**
- Potion Combiner for Apothecary — Adds recipes to cooking stations that allow you to combine two identical potions/poisons into one stronger version.
- House of Horrors - Quest Expansion by JaySerpa — Provides a good-aligned resolution to the quest, perfect for paladin-type characters.
- Bring Meeko To Lod
- Steel Battleaxe Of Fiery Souls - Truly Unique
- Ghostblade - Truly Unique
- Hungers SE by 4thUnknown
- Minotaurs SE by 4thUnknown
- Flesh Colossus SE by 4thUnknown
- Unlocked 1st Person Combat — Allows for free movement while power attacking.
- Madmen Poison Damage Nerf - SkyPatcher — Nerfs poison spells of the Forsworns.
- No Follower Bow Skypatch — Removes the default bow the game gives to followers who don't have one.
- Simple Follower Sandbox
- Followers Don't Draw Weapons - Updated — Followers now only draw their weapons when entering combat, independent of the player's stance.
- SIGMA - 1st Person Animations Series
- Replaced Quick Light with Lights On - Wearable Lanterns for Immersive Equipment Displays.

### Visuals

**Removed:**
- Riverwood Has Walls — Replaced with ItzIvy's and MissileMann modules.
- Chob's Women of Whiterun Hold

**Added:**
- A Makeover for Serana
- Women of Skyrim Refined
- Illustrious Whiterun SE
- Riton's Medieval Solitude
- ElSopa - HearthFires Oven Redone
- Kanjs - Sigil Stone Animated
- Children of the North Wind - Ruins of the Ancient Nords
- Drain Magic VFX Edit
- Iconic's Remastered Paragon Gems
- Farm Diversity - Feeding Troughs — Base Object Swapper or Model Swapper

### UI

**Removed:**
- Skyrim Souls RE

**Added:**
- moreHUD SE
- Compare Equipment NG — Displays side-by-side item cards.
- Convenient Reading UI - SE
- Smart Talk (Dialogue Menu Enhancer)
- Favorites Menu Effects Description
- Real Skyrim Loading Screen Replacer
- Shout Menu - Unrelenting Force Main Menu Background Replacer

### New Content

**Removed:**
- Kaidan — Great voice acting but poor mic quality. Hopefully the voicelines will be re-recorded in the future.
- Spear of Skyrim - 1h Conversion

**Added:**
- Medieval Markets by JJerem — Overhauls city markets in Skyrim, making them look and feel more lived-in.
- Grand Solitude - The Walls of High King Erling — A complete overhaul of Skyrim's capital city, Solitude.
- RedBag's Shor's Stone
- FuzzBeed's Creepy Caverns - Cave Locations Overhaul
- Pride of Cuhlecain - A Weynon Stones Overhaul
- Shalidor's Insights - Winterhold Spire Resculpted
- Across the Border - Diverse Border Gates
- Double Life - Anise's Cabin Overhaul
- Kyne's Breath - A Froki's Shack Overhaul
- Man's Best Friend - A Meeko's Shack Overhaul
- Unfortunate End - A Riverside Shack Overhaul
- Yggdrasil Music and SoundFX Overhaul SE — Dark Nordic soundtrack. Optional, enabled by default.
- YY Animation Replacer - Mystic Knight (OAR version) — For Shield + Spell animations.
- Dragonstar Armor SE
- Twilight Princess Armor Mashup
- Simply Realistic Armor and Weapons (Custom NordwarUA Edition) — For the Glass Armor and Shield replacers.

---

## Version 2.1.3

> Safe to update

- Integrated the Bestiary into the Main Menu following the removal of Tween Menu Overhaul.
- Fine-tuned/fixed some controller behaviors.


## Version 2.1.2

> Safe to update

- Replaced NPC Infinite Block Fix - SkyPatcher with NPC Block Loop Fix.
- Updated controller mapping for a more intuitive setup.


## Version 2.1.1

> Safe to update

- Fixed a crash when reaching Falkreath caused by an incorrect mesh.
- Activating a campfire from Camping Supplies now offers the option to ponder, which opens a new perk tree with survival bonuses for camping enthusiasts.
- Removed Lore Friendly Embershard.
- Added Embershard by snozz2004.
- Standing idle near a fire source for 3 seconds will trigger a warming hands animation. Press LB to exit the animation.


## Version 2.1

>[!IMPORTANT]
>A new game is required!

### Gameplay

**Removed:**
- Valhalla Combat — Previously used only for the stamina feature. Normal attacks no longer regenerate stamina.
- Soul Resurrection — Removed due to settings not persisting between games.

**Added:**
- Blade and Blunt - A Combat Overhaul
- Bow Rapid Combo V3 - Archer Combat Overhaul — Optional third-person-only gameplay for archery, disabled by default. Enable it under the Optionals separator.

### Visuals

**Added:**
- Storm Atronach SE
- Hagraven - New Models and Textures
- Ave's Amulets Replacers
- Ivy's Roads of Whiterun - Base Object Swapper — Replaces Whiterun Plains District roads with dirt textures.

### Fixes
- Modern Brawl Bug Fix — Should fix the For Honor bug that caused bystander NPCs to aggro when using Power Attacks.

### Animations
- SIGMA - Sword Animations - 1st Person

### Content

**Added:**
- Tales of Skyrim - Berserkyr — Discover the north's most fearsome warriors: the berserkers. Encounter new enemies, armors, and quests, and receive the power to transform into a werebear.
- Gore - A Companion Mod — A fully voiced, lore-friendly standalone follower.
- Fuse00 - Rogue Armor — Added to Vampires leveled list.
- Fuse00 - Shadow Armor — Added to Vampires leveled list.
- Fuse00 Scout HDT-SMP Armor — Distributed to Riften NPCs.
- Rogue Nord Armor — Distributed to Athis of the Companions.

### UI
- Follower Stats — See what a follower is good at before hiring them.
- Skull of Corruption Dream Counter — Adds a HUD widget displaying how many "dreams" you have stored in the Skull of Corruption.

### Miscellaneous
- Pets of Skyrim - Equipment Extension — Adds the ability to equip collars and packs on other pets from the vanilla game.

---

## Version 2.0

>[!IMPORTANT]
>A new game is required!

### Gameplay

**Removed:**
- Sneak Tools — Removed due to conflicts with Vampire Feeding Tweaks.
- Simple MCO Weaponart Casting — Destruction spells cast through this mod don't benefit from perks (damage and cost values remain static).
- Skybane The Logic of Death Resistance Overhaul — Instead, custom resistances have been implemented at the plugin level with intuitive adjustments only: Frostbite Spiders are now resistant to frost and poison but weak to fire; all frost variant animals (Frost Wolves, Frost Bears, Frost Trolls) are resistant to frost and weak to fire; Dwemer Automatons conduct shock and are 25% weak to shock spells; Mudcrabs share this shock weakness due to their humid nature.
- Skyblivion Lockpick Menu — Replaced with the vanilla lockpicking system.

**Replaced:**
- Alternate Start - Live Another Life has been replaced with Skyrim Unbound Reborn.

**Added:**
- Biggie Traits and Biggie Traits - Refitted — Provides trait choices at the beginning of the game for a smoother roleplay experience and to enable new playstyles.
- Soul Resurrection - Injury and Alternative Death System and Soul Restoration - A Soul Resurrection Add-On — Upon dying, the player will revive in the same spot, but with injuries and a loss of experience. The injuries can be treated with the Soul Restoration power at the cost of Soul Gems.
- STB Quick Hotkey Cast — Allows you to use powers and shouts by single-pressing assigned hotkeys (1–8).
- Individual Shout Cooldown Remake — Enables individual cooldowns for each power and shout ability. Paired with STB Quick Hotkey Cast, this allows for fast and dynamic use of shouts.
- Winter Wonderland Magic, Abyssal Wind Magic, and Frostbitten Dreams Magic by Kittytail.
- Runemaster Magic by Kittytail — Each rune has been carefully balanced for use with melee and ranged weapons with a magicka cost, enhancing combat dynamically without requiring you to switch to spells.
- For Honor in Skyrim I Lawbringer
- Thieves Guild Requirements SE — Adds skill and radiant quest requirements that must be met to advance the Thieves Guild questline (see FAQ on Discord).

**Changed:**
- Target lock switching now uses the mouse wheel (previously done by moving the mouse around) for better control. This can be adjusted in the True Directional Movement MCM under the Target Lock submenu.
- Controller Setup — New controller configuration implemented for a more intuitive experience. See the changes in the #controller channel on Discord.

### Visuals

**Replaced:**
- Cabbage ENB with Amon ENB.
- Less Mythical Giants Replacer with vanilla giants.

**Added:**
- Nahl Frod - A Cathedralist Grass Overhaul
- Vanaheimr - Farmhouses — Complex Material and PBR
- Nordic Farmfield Stonewalls
- Tomato's Riften and Ratway
- Skyking Signs
- Skyking Soul Gems
- Dawnbreaker Redone
- Unique staves replacers by Avebrave
- DD - Jewelry Replacer by Vergi
- Salmon Replacer — Mihail Monsters and Animals and Hanging Dead Salmons Replacer — Mihail's Shards of Immersion

### UI & Audio
- Oathvein UI — A work-in-progress UI mod not yet available on Nexus. Please note this is a WIP and may have shortcomings, especially in the 21:9 version.
- Compare Equipment NG
- Dialogue History
- Hun Lovaas - Skyrim Fan-Made Combat Music
- Babbling Brooks - A Water Audio Overhaul

### Miscellaneous

**Removed:**
- Immersive Laundry

**Added:**
- Fuse00 Hairstyles from Patreon
- Viking Armor Expansion
- Steel Plate Armors
- DD - FVO Cloth CBBE 3BA SMP
- DD - Einar Idun Wardrobe CBBE SMP
- Northern Knight - Armor Mashup SMP
- Nord Steelheart Armor (re-added)
- JellyFishFP DAGGER — 1st person animations series
- JellyFishFP CROSSBOW — 1st person animations series

And many more fixes and improvements! Hope you have a blast!

---

## Version 1.9

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Removed Immersive Weapon Switch — Didn't like that you don't get any confirmation when swapping weapons in paused menus (nothing happens visually, which looks like a bug).
- Removed Spell Hotbar 2 — Ultimately better to cast spells manually: you get better targeting for conjure spells and ground-based spells like walls of fire, it respects charge time constraints, and it's easier to choose between single and dual casting.
- Added STB Quick Hotkey Cast — Handles quick casting of shouts and powers perfectly while working with the more intuitive vanilla favorites system.
- Added Simple MCO Weaponart Casting — Lets you use MCO's weaponart feature to cast fire-and-forget destruction spells and offensive restoration spells. Once you know certain spells (like Firebolt or Icy Spear), you can craft Sigil orbs at the forge, then cast their corresponding spells using power dual attack (Alt+M5 for keyboard/mouse, LB+LT for gamepad).
- Re-added Skybane - The Logic of Death — Implements weaknesses and resistances system similar to Know Your Enemy.
- Replaced Chocolate Poise with POISE - Stagger Overhaul SKSE — A nearly complete overhaul of the vanilla stagger system, replacing it with something inspired by traditional fighting games.
- Added Storm Calling Magic 2 — A spell pack by Kittytail.
- Added 360 Ward — A 360° degree full sphere ward replacer.

### Fixes
- Fixed a faulty Silent Horizons 2 - Shader Core installation.

### Visuals
- Removed NOTWL animation meshes, which were causing stuttering and poor performance.
- Added Nordic Runestones — Places ancient Nordic runestones throughout Skyrim's landscape.

### Miscellaneous
- Added Northern Roadwatch Garb — A Khajiit-themed light armor set by Pulcharmsolis.

Plus a few other tweaks and improvements for smoother performance and gameplay.

---

## Version 1.83

>[!IMPORTANT]
>A new game is required!

- Removed Dragonborn Reskin - SkyUI Inventory Category and Favorites Icons due to sluggish inventory menu performance.
- Removed Dynamic Impact - Slash Effects X pending further testing with Sanguine Symphony compatibility.
- Removed Scrolling Speed NG due to inconsistent functionality and implementation bugs.
- Reintroduced Oblivion mode of Spell Hotbar for mouse and keyboard.

---

## Version 1.82

>[!IMPORTANT]
>A new game is required!

- Temporarily removed QuickLootIE due to causing HUD disappearance issues.
- Swapped Brown to Green Tundra.
- Added Dynamic Impact - Slash Effects X.
- Added Ancient Blood Magic II by Kittytail.

---

## Version 1.81

>[!IMPORTANT]
>A new game is required!

- Removed Starfrost - A Survival Overhaul.
- Added SunHelm Survival and Needs.

---

## Version 1.8

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Removed Skybane - The Logic of Death
- Removed Blade and Blunt - A Combat Overhaul
- Removed Journeyman - A Fast Travel Overhaul
- Reintroduced Chocolate Poise combat system.
- Added Obscure Magic by Kittytail.

### Visuals
- Added HFs - Silent Sentinels.

### Miscellaneous
- Reverted Better Third Person Selection (BTPS) to older version to temporarily fix random HUD disappearance issues. Please report if you still encounter this problem.
- Removed Animated Ships due to frequent crash reports.
- Added DD - Tara Dress by Vergi.
- Added Dragon Random Stagger Animation.
- Added Floating Subtitles by powerofthree.
- Added Dragonborn Reskin - Casting Bar, a visual overhaul for the Casting Bar mod.

Plus several bug fixes and improvements! This update focuses primarily on refining the experience to ensure a smooth and enjoyable gameplay experience.

---

## Version 1.7

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Added Scrolling Speed NG — Enables precise movement speed control (on foot and mounted) using mouse wheel while moving with directional keys. Standing still retains normal zoom functionality. Vanilla walk/run toggle has been removed.
- Nerfed Adamant Two-Handed perks for better balance.
- Nerfed archery movesets and removed rapid shot abilities.
- Added Holmgang - ADXP I MCO Moveset for NPCs — Introduces Assassin's Creed Valhalla-inspired combat animations for NPCs.
- Added Blade and Blunt - A Combat Overhaul — Implements slower-paced combat with intensive resource management and injury mechanics that require rest to heal.
- Added Stormcrown - A Shout Overhaul — Complete rework of Skyrim's shout system with balanced existing shouts, new shouts, and enhanced Dragonborn progression.
- Added Journeyman - A Fast Travel Overhaul — Lightweight system that restricts fast travel unless player has prepared a travel pack.
- Added Starfrost - A Survival Overhaul — Streamlined survival mechanics with minimal tedium.
- Removed SunHelm survival mod.
- Added Customizable Companions Questline Progression Requirements — Increases required radiant quests for Companions advancement.
- Added Equipment Durability System NG — Weapons and armor degrade through use, spawn with random tempering, includes equipment health widgets.
- Added Dawnguard Patrols — Introduces nightly Dawnguard patrols with potential vampire ambush encounters.
- Added Skybane - The Logic of Death — Implements weaknesses and resistances system similar to Know Your Enemy.

### Visuals
- Added Saadia - WeelBones' Overhaul — Visual redesign for Saadia the Redguard.
- Added Fool of Hearts - A Cicero Visual Replacer — Standalone ESL visual overhaul for Cicero.
- Added SMP Wind NG — Enhanced weather-dependent wind physics.
- Added ALT - Barrels
- Added Vergi_wood plate and Vergis open bar
- Added ElSopa - Misc Ruins Redone
- Added HFs - Chests
- Added Freak's Floral Veil - A Cathedral Grass Overhaul
- Added HDT-SMP Creation Backpacks
- Added Missives - The Witcher Board HD

### Miscellaneous
- Added Scribers - Chakra's Creatures — New enemy spawns in Apocrypha realm.
- Added Kaidan 2 — Companion mod.
- Replaced Lights On with Quick Light SE — Removed inventory lantern requirement for lighting.
- Added Wish Magic by Kittytail — New magic system.
- Added JK's Tel Mithryn — Location overhaul.
- Temporarily removed QuickLoot due to conflicts with latest BTPS versions causing HUD disappearance issues.

And many bug fixes and improvements!

---

## Version 1.6

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Leveling up no longer requires sleeping.
- Refined the combat experience with various tweaks and settings adjustments.
- Added TK Dodge fat roll, which triggers when the player is over-encumbered.

### Visuals
- Added Dawnfire ENB as a new ENB choice. Cabbage ENB is still available under the optional mods.
- Switched back to Freak's Floral Fields. The latest update brings grass to tundra dirt cliffs.
- Switched to Vanaheimr - Landscapes, which fits incredibly well with the new grass.
- Added Riverwood Falls — Adds two waterfalls near Riverwood.
- Added Nordic Jewelry Reforged — A reimagining of the Nordic Jewelry Creation Club mod.
- Added Luxury Lava - High Quality Lava Replacer.
- Added Diverse Chicken Coops - Base Object Swapper.

### Miscellaneous
- Added GABE'S - SMOOTHCAM — New SmoothCam preset that brings the camera closer to the player. The original SmoothCam preset is still available in the SmoothCam MCM.
- Added Viper Armor by FafnyB — Distributed to Jenassa.
- Added Various Book Tags — Adds tags for books in the UI, indicating when they're for quests, skills (specifying which skill), and more.

And various bug fixes and improvements!

---

## Version 1.52.2

> Safe to update

- Fixed bow's rapid shots (secondary attack) not firing anything.


## Version 1.52.1

> Safe to update

- Fixes Durak teleporting.
- Fixes invisible Paraglider.


## Version 1.52

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Re-added the block key functionality.
- Added Boozy Obnoxious and Opulent Bards — Introduces a host of new perks to the Speech tree for enhanced bard roleplay.
- Replaced Skyrim's Paraglider - ZERO with Skyrim's Paraglider - ONE — Allows inventory swapping between the standard paraglider, magic broom, levitation gem, or dark elf lantern.

### Visuals
- Added Light Magic VFX Edit by Kittytail.
- Added Kanjs - Nordic Puzzle Door Animated — Remeshed Nordic puzzles with emissive animations and particle effects.
- Added Chakra's Creatures - Mythical Giants Replacer — Replaces all vanilla Giants with mythical variants.
- Refined the custom grass mashup for the Rift, the Reach, and the Marsh.

### Miscellaneous
- Added RaceMenu Undress — Provides an "Undress" slider that toggles equipped items in RaceMenu (found under Body).
- Added Grievous Rose (3BA SMP) — New outfit distributed to Serana.
- Added The Noble Bones - a Breton Armour Mod — New armor obtainable through a small, spooky dungeon quest.

### Audio
- Added Talkative Draugr — Introduces voiced lines in Dovahzul to draugr.
- Added Voice of Dawn — Adds voicelines to the unique sword Dawnbreaker.

---

## Version 1.51

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Re-added the usual dodge key (sprint tapping) and removed For Honor's built-in dodge mechanisms.
- Added Simple TKDodge Sidestep for the dodge animation.
- Replaced Bow Charge Plus with Bow Rapid Combo V3 - Archer Combat Overhaul.
- Removed Hand Placed Enemies - Light (Populated Spawns and Dungeons).

### Visuals
- Added a custom-made grass mashup — a mix of Folkvangr with Cathedral 3D flowers.

---

## Version 1.5

>[!IMPORTANT]
>A new game is required!

### Miscellaneous
- Removed the distribution to NPCs of Woodland Wizard Robes due to broken meshes. The set is now simply available at the forge for players to craft.
- Removed Olenveld quest mod — Too ambitious in scope and would have benefited from being significantly smaller and more polished.
- Removed Seasons of Skyrim.
- Added Pronouns — Allows players to specify their character's gender pronouns irrespective of their physical characteristics. This mod must be enabled under the optional separator in MO2.
- New follower: Thogra gra-Mugur - Orc Follower and Quest — Can be found by the roadside near Nightgate Inn, heading towards Windhelm.
- Note: Steam Overlay should be disabled for Skyrim (right-click game > Properties > toggle Steam Overlay off) to prevent conflicts with ENB Frame Gen mod.

### Gameplay
- Added For Honor in Skyrim — New combat system where dodge and parry are no longer active keys to press but instead rely on movements. Moving sideways and attacking will trigger a dodge, while moving backwards and attacking will trigger a parry.
- Removed Valhalla Combat and Chocolate Poise.
- Added Pilgrim - A Religion Overhaul — Adds dozens of new deities with powerful shrine effects to the game. Praying at a shrine for the first time grants a Lesser Power called Prayer. This power allows players to meditate in order to receive a blessing from the last shrine they prayed at.
- Added Artificer - An Artifact Overhaul — Designed to distribute Thaumaturgy and Mysticism enchantments throughout the game while ensuring that non-crafting characters can find powerful weapons and armor through questing.
- Added Hand to Hand - An Adamant Addon — Merges Lockpicking and Pickpocketing into a single skill and adds a new perk tree for Hand to Hand combat.
- Added Stress and Fear - A Dynamic Sanity System — Getting hit in combat increases stress. If enough stress accumulates, it will reduce stamina and magicka. Stress can be reduced by drinking alcohol, eating a warm meal, sleeping in a safe space, petting a dog, playing music, fishing, etc.

### Visuals
- Added Riverwood Has Walls - A Full Overhaul.
- Added Pigs — Mihail Monsters and Animals.
- Added STB Active Effects.

---

## Version 1.4

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Added Unlimited Hostile Encounters — While traveling through Skyrim, hostile encounters will now dynamically spawn based on the region and time of day. For example, traveling at night may lead to encounters with zombies, skeletons, werewolves, and vampires.
- Added Dynamic Scaling Level Attribute — Enemy stats such as health and physical or magical damage will now scale more closely to the player's level.
- Added Break Staves and Learn Spells — While in your inventory, highlighting a staff and pressing B will allow you to break the staff and learn the spell it casts.
- Added Inquisitor Remake I Warlock — Introduces new animations for magic-casting NPCs to enhance the visual feel of spellcasters.
- Added Sanguine Symphony — Overhauls combat visuals with adaptive blood splatters, high-resolution wound textures, detailed decals, and immersive custom sound design.
- Added Four Seasons - Faster Seasons of Skyrim — Seasons now last 30 in-game days instead of 90, creating a more dynamic seasonal cycle.

### Visuals
- Added Vanaheimr Mountains and Freak's Floral Meadows — Enhances mountains and grass appearance with expected performance improvements.
- Added Nature of the Wild Lands - Animations Addon — Provides realistic tree animations for improved immersion.
- Added Woodland Wizard Robes by Pulcharmsolis — Distributed to enemy conjurers to diversify their appearance.

Includes multiple other improvements and fixes. Have fun!

---

## Version 1.3

>[!IMPORTANT]
>A new game is required!

- Backpacks have been adjusted so that all additional backpacks added by mods now properly display custom items (such as instruments, quest items like the Dragonstone, etc.) without clipping.
- Added Mortal Vitality - A Player Health Regen Overhaul — Natural health regeneration is now completely disabled. Players must rely on potions, food, perks, enchantments, or racial bonuses (tip: Orcs have 50% increased health regeneration).
- Removed the follower baby Dragon and Celestine.
- Two new unarmed movesets **added: Vampire Claws and Warbeast — These automatically trigger when unarmed and in vampire or werewolf form, respectively.**
- Added TS - Simply More Vanilla Creature Encounters — Increases the variety of wildlife encounters in the wild.
- Added Quest Perk Rewards — Allows you to earn permanent buffs by completing specific quests.
- Removed SkyClimb (now obsolete) and updated SkyParkour to version 2 — Players can now climb and vault over objects more fluidly.
- New quest: Olenveld — A large and challenging quest. Recommended to be around level 15–20 and well-stocked with potions and food before starting.
- Removed Teach Followers Spells Through Spell Tomes.
- New follower: Melana the War Maiden — A fully custom-voiced, evolving companion. Found at Bannermist Tower.
- Updated HUD: TrueHUD bars now display numbers for better clarity.
- New outfit: ELLE - Mageali.

Plus many other fixes and improvements throughout the modlist.

---

## Version 1.2

>[!IMPORTANT]
>A new game is required!

**Added:**
- Baby Dragon - A Pet Follower
- SIRENROOT - Deluge of Deceit
- Exalted Enemies
- JK's Raven Rock
- Edmond's Nature Series - DEER

Many bug fixes and improvements!

---

## Version 1.1.2

> Safe to update

- Fixed not being able to allocate skill points when leveling up.
- Fixed wrong LAlt dodge key in the optional config.


## Version 1.1

>[!IMPORTANT]
>A new game is required!

### Miscellaneous
- New follower: Celestine
- New quest: Siege at Icemoth

### Gameplay
- Cult of the World Eater - Dragon Priests Buff Alduin and Defeat the Dragon Cult
- Draugr Horse Mount — Mihail Monsters and Animals
- Deadlier Poison Skypatcher
- Staff Enhanced Magicka
- Spell Absorption Rework - A Non-Chance Based System
- NPC Soul Gem Recharge

### Animations
- Removed Malignis Animations - Conditions
- Added Crouch Sliding

### UI/HUD
- Switched to Untarnished
- Tween Menu Overhaul
- Can toggle HUD with U key

### Armor/Weapon
- HDT-SMP Vanilla Armors

---

## Version 1.0.3

> Safe to update

- Removed SoulsyHUD which caused HUD inconsistencies depending on user setup.
- Added Sacrificio - Mage Replacer for Illia Aranea Eola (for Aranea).
- Added Sleipnir Beds - An Upper Class Bed Replacer.


## Version 1.0.2

- Fixed more downloads.


## Version 1.0.1

- Fixed some downloads.


## Version 1.0

### Fixes
- Added Sprint Stuttering Fix
- Added Weapon Switch Animation Fix
- Added Contextual Crosshair - Crosshair and Detection Meter Fix

### Gameplay
- Added Spell Hotbar 2
- Added Elemental Mastery Magic by Kittytail
- Added Desecration by Darenii
- Removed Headhunter - Bounties Redone (incompatibilities with other mods)
- Added Simple Fall Damage Tweaks
- Buffed Giants' HP by 500 points
- Replaced Dirt and Blood - Dynamic Visual Effects with Bathing in Skyrim - Renewed
- Removed Hogwarts in Skyrim
- Removed Bow Rapid Combo V3 - Archer Combat Overhaul
- Added Bow Charge Plus
- Removed Vanguard - Bash Behaviours Updated
- Added Camping Plus Plus
- Added Phantom Horse and Phantom Horse Quest Integration

### Animations
- Added Exit Sneak On Sprint
- Added Smooth Moveset (CPR)
- Added Immersive Weapon Switch - SKSE Plugin

### Visuals
- Removed TAA Sharpen (made obsolete by DLAA)
- Removed Leafeater's Whiterun Tree Overhaul SE
- Removed Skyrim 3D Windmill
- Removed Bosmer NPCs have antlers
- Removed Ryn's Lumber Mills and added The Great Village of Mixwater Mill
- Removed Spaghetti's Shor's Stone and added The Great Village of Shor's Stone
- Removed Skyrim 3D Rocks
- Replaced A Makeover for Serana with Another Serana - High Poly Replacer - Skypatched
- Added The Lioness - Lulu's Mjoll
- Added Rustic Repose - A Common Bed Replacer
- Added Skyking Alchemy Ingredients
- Added Some Shrooms - High Poly Mushrooms
- Replaced Diverse Witcher Missives Boards with Missives - Unique Missive Boards
- Added Ghorbash the Iron Hand Refined
- Added Noteworthy Trees Uniquefied
- Added Praedy's Ores and Ingots - SE
- Added Wicked Wayward Pass - FuzzBeeds Minor Locations
- Added Corrupted Cradlestone Tower - FuzzBeed's Forsworn Camps
- Added SavrenX Elder Scroll
- Added ENB Terrain Blending Fix
- Replaced Cathedral - 3D Mountain Flowers with Reimagined Mountain Flowers
- Removed Strange Runes and added Strange Wards
- Replaced Rally's Thrones with Thrones Expanded
- Replaced Boreal Whiterun with Riton Witerun II
- Added Shores of Skyrim - Base Object Swapper
- Added HFs - Farmer's Comfort (BOS) - Table Remodel
- Replaced Ryn's Lund's Hut with WiZkiD Lund's Hut
- Replaced Freak's Floral Fields with Wildlands Renewal - Grass and Groundcover Improvement
- Added Amon's Talos Statue Replacer
- Added JK's Riften Outskirts, Solitude Outskirts, Windhelm Outskirts
- Replaced SD's Farmhouse Fences SE with MPirata - Fences That Fit
- Added HFs - Aretino Family Heirloom - Remodel
- Added New Female Giant Dressed
- Added Supernatural Sovngarde Portal - Glowing Portal Effects
- Added Ivy - Gates of Riverwood / Ivy - Faendal Home Overhaul / Ivy - Ivarstead Well Addon / Ivy - Riverwood Small Bridge Replacer
- Added Docks of Riverwood
- Added Solitude and Temple Frescoes 2019
- Added Praedy's Sky AIO - SE
- Added HFs - Apple Pie - Remodel

### Armors & Weapons
- Added Fuse00's Sasrir Armor
- Added Squire's Plate
- Added Bocksten Cloak - HDT-SMP
- Added Midnight Huntress Armor (3BA SMP)
- Added Cold Foreigner Outfit (3BA HIMBO)
- Added Sugaruya Katana SE
- Added Runecarver's Edge
- Added Usable Skyrim Bandages
- Added DD - Vergi Fashion CBBE 3BA SMP
- Added DD - Legend Iron Armor CBBE 3BA
- Added Aesthetic Facial Piercing
- Added Common Clothing Expansion
- Added Fluted Armor SE
- Added Rover Armor
- Added Lavatera Armor
- Added Thorn Princess
- Added Cosplay Pack
- Added West Wind Combat Series - Misfit Mage Restitched
- Added Project Minoan - Weapons
- Added Gryphonknight Regalia - Breton Noble Armor
- Added DD - Vergi Jewelry II 3BA FSMP HDT
- Added ELLE - Apothecary
- Added Everedge Sword - SE by Xtudo
- Added Traveler's Armor Pack - Visually Upgradeable Outfit
- Added Fluffy Nordic Fur Armor
- Added FB - Templar Assassin Armor
- Added FB - Master Thief Armor
- Added Nord Steelheart Armor

### Quests
- Removed The Tools of Kagrenac

### HUD/UI
- Added Show Follower Carry Weight
- Added Desktop Splash Screen
- Replaced Interesting Casting Bar with Edge UI Like - Casting Bar Patch
- Added Highlight Quest Markers
- Added DwP Reskin - STB Widgets (for Edge UI)
- Added Description Framework

### Audio
- Removed Relaxed Bards
- Added Magical Potion Sounds
- Added Depths of Apocrypha - Lurker VSFX Rework
- Added Enigma Series - Book of the Wild - RE
- Added Glacia - Ice Wraiths SFX Rework

### Miscellaneous
- Added Diverse and Lootable Firewood - Base Object Swapper
- Added Shouts of Stallholders
- Added Ivy - Riverwood Timber Rest - Player Home
- Added Sweeping Organizes Stuff - Use Broom to Clean Mess
- Added CC Myrwatch - Tweaks and Enhancements
- Added Civil War Checkpoints - Whiterun
- Added Wash That Blood Off 2
- Added Put Out The Fires - Dynamic Fire Control System
- Added Swooderman's Personal Argonian Preset
- Added Miggyluv's Presets - Jacqueline (Breton)
- Added Seasons of Skyrim

---

## Version 0.94

> This update is theoretically safe to install mid-game, but stability cannot be guaranteed 100%. If you're in the middle of a playthrough, it might be safer to hold off until you're ready. Proceed with caution!

### Gameplay
- Added Horses Unlimited Stamina.

### Visuals
- Fixed a seam outside Ivarstead.
- Removed Unique Markarth Doors - Security Overhaul SKSE - Base Object Swapper.
- Added HFs - Archery Target Remodel - Diverse BOS.
- Added Chob's Women of Whiterun Hold.
- Added Mihail's Rooster Proportions.
- Added Smaller Mihail's Sewer Rats.
- Added Golden Dwemer Pipeworks Redone.
- Added Falmer Huts Animated.

### Armors & Weapons
- Added Obi's Gladiator Armor.

### Quests
- Added The Tools of Kagrenac.

### HUD/UI
- Fixed Casting Bars that were incorrectly scaled.
- Added HD Local Map.
- Added Local Map Upgrade (note: some transparency issues exist and will be addressed in a future fix by the mod author).
- Added Ethereal Skill Menu Overhaul.
- Replaced Alduin's Wall Main Menu Replacer with Mathieu's Souls-Like Minimalist Main Menu.

---

## Version 0.93.1

> Safe to update

- Fixed missing outfit parts for Nazeem and Saffir.


## Version 0.93

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Added Ice Turmoil by Mihail (Monsters and Animals).

### Visuals
- Added Freak's Floral Solstheim.
- Added Colorful Giant Mushrooms (variant designs for Blackreach).
- Added Detailed Landscapes - Gleamblossoms and Caveworms in Falmer Hives (BOS).
- Added Lush Dragonsreach Pools.
- Added eeekie's Illia (character visual overhaul).
- Replaced Bjorn Refined with A Makeover for Bjorn.
- Added Nord War Horn 2K-8K by iimlenny.

### Armors & Weapons
- Removed Sarta - Leather Wrapped Sword.
- Added Ciri Concept Art Armor (new outfit for Njada Stonearm).

### HUD/UI
- Added The Dragonborn's Bestiary.

---

## Version 0.92

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Removed Storm Calling Magic 2 and Air Dash.
- Added Dirt and Blood - Dynamic Visual Effects by JaySerpa.
- Added Alchemical Appraisal Services — Alchemists can now identify ingredient effects for a fee.
- Added Temper and Recharge Services — Blacksmiths can temper your gear, and court wizards can recharge enchanted items.
- Added Sanctified Steel - SkyPatcher — Steel weapons deal extra damage to undead.
- Added Better Grabbing.
- Added New Creature Animation - Dwarven Centurion.
- Added Be One With The Sword by GiraPomba.

### Visuals
- Removed Northern Fortifications - Riverwood and added Ivy - Riverwood Smelter Addon.
- Replaced Complex Parallax Texture for Northern Roads with R - Rocky Mossy Complex Parallax for Northern Roads (MuddyBrown version).
- Added HD Remastered Fort Dawnguard - Complex Parallax.
- Added Rudy HQ - ENB Complex Material for Silverware.
- Added Lovely Lady - 3BA (3BBB) CBBE Bodyslide Preset and rebuilt female armors/outfits.
- Added Ancient Sword of Runes by Bukikaesus as a Gauldur Blackblade replacer.
- Added HAG - Occult Orphan Rock by JJerem (location overhaul).
- Fixed a significant number of water seams.

### Armour
- Added Dragon Shell Armor HDT-SMP
- Added Wanderer Armor HDT-SMP
- Added Eclipse Mage Outfit HDT-SMP

### HUD/UI
- Replaced vanilla player bars (EdgeUI reskin) with TrueHUD.
- Removed Party Combat Parameters.
- Replaced A Matter of Time and Widget Mod with STB Widget.
- Added Modex - A Mod Explorer Menu (AddItemMenu).
- Several tweaks and enhancements.

### Audio
- Removed Ragnarok - Viking Battle Music (combat tracks volume was too low).
- Added Yggdrasil Music and SoundFX Overhaul.
- Added Music Replacer Reverter — Keeps vanilla music alongside any soundtrack replacer.
- Added Khaleesi's Parry SFX for Valhalla — Softer timed block sounds.
- Added Crackling Fire by Clofas.

### Miscellaneous
- Removed Dark Knight Heavy Padded Armor Set (replaced with Lifesworn Vestiges Armor as the Dawnguard Armor replacer).
- Removed Kala's Eyes (regular, beast, and vampire).
- Removed some Fuse Hairstyles (issues with downloads and performance).
- Added [Dint999] HairPack02 SSE 1.11.
- Tweaked existing character presets and added new ones.
- Added Naked Comments Overhaul.
- Added Sewer Rats — Mihail Monsters and Animals.
- Added Hollowjack Alghoul Familiar by Mihail (Monsters and Animals).

---

## Version 0.91

>[!IMPORTANT]
>A new game is required!

### Gameplay
- Removed Scheduling of Sleep — Superseded by Modern Wait Menu features.
- Removed College of Winterhold entry fee.
- Removed Immersive Hunting Animations.
- Removed Immortal-Essential Followers due to incompatibility with the Boethiah's Calling quest and inconsistency with modded followers.
- Fixed quarterstaff animations not triggering.
- Tweaked Valhalla Combat values — Successful hits now restore 5% stamina.
- Added NPC Spell Variance — NPCs now cast a wider variety of spells.
- Added Belethor's Sister (Quest Mod).
- Added Missives.
- Added Simple Hunting Overhaul.
- Added Hunter's Dream (Quest Mod).

### Visuals
- Removed Wigfrid's Erdtrees.
- Enhanced Volkihar Keep interior with improved clutter and outfits.
- Added KS Hairdos - HDT SMP and refined some RaceMenu presets.
- Added Stretched Snow Fix.
- Added Orc Exiles - Rift Watchtower.
- Added Riton Imperial Forts.
- Added Ivy - Whiterun Well Overhaul.
- Made several NPC visual tweaks.

### Miscellaneous
- Added Lifesworn Vestiges - Champion of Arkay armor.
- Made small tweaks and improvements across the modlist.

---

## Version 0.9.1

- Fixed the ENBSeries download link.
- Removed the Eldritch Blast mod as it was causing installation issues.
- Refined ENB settings.

## Version 0.9

- Initial release.
