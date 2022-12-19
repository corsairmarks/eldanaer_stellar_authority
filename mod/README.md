# Overview

Do you like to play or fight empires with a backstory? Or maybe you want to have a pre-made empire to bring to your next role-play game? Then this mod is for you! I enjoyed coming up with a backstory for this empire, and I thought that I'd publish it for others to enjoy as well.

Oh, and this mod is also for you if you want a new Colossus weapon - the Necrophagic Spore Diffuser! This weapon can become available for fungoid necrophage empires to research _after_ they have completed the Colossus project. It is based on the Nanobot Diffuser (and reuses the same graphical effects).

The weapon effects are slightly different: all biological Pops are converted to the main necrophage species of the firing empire (normally the Eldanær but the weapon can be researched by any fungoid necrophage) and robot Pops are "conquered" by the necrophaged Pops, which causes devastation based on the percentage of robot Pops that were present. Because the weapon cannot forcibly convert robot Pops, it can only be fired on hostile planets that have more than half of the Pops eligible to be necrophaged (or are already the appropriate necrophage species). Similar to the Divine Enforcer, it can be used on your own planets to instantly convert any biological Pops into your necrophage fungoids (this does not cause devastation or unhappiness in robotic Pops - they are already in your empire).

# Details

The Eldanær Stellar Authority is a fanatic authoritarian, xenophobic empire ruled by a rigid and complex bureaucratic hierarchy. It has a custom imperial authority, the Bureaucratic Autocracy, which is the same as a regular imperial authority but the rulers do not use dynastic titles. The Eldanær are fungoid necrophages with a plantoid prepatent species, the K'foori. The Eldanær have a pre-scripted home system (Ræl) with named planets and the Lush modifier on their homeworld (Dærun), orbiting a ringed gas giant with an extensive moon system - it is also available for custom empires to select.

This mod also includes a custom primitive species of lithoids (the Zdremites) that will replace one of the randomly generated primitives for the Eldanær Stellar Authority's necrophage origin - as long as the number of guaranteed habitable worlds is 1 or higher. The Zdremites are guaranteed to spawn on a high gravity world and dangerous wildlife with lithoid monoliths that can always be cleared into extra Zdremite Pops, but have fewer Pops to start with. Their High-G Evolution origin is available for you to play (although it is underwhelming as a stand-alone origin).

Below are the full details about the portraits, traits, flags, and other game details used by this mod. They are provided here in case you would like the play as the Eldanær Stellar Authority but don't want any of the custom scripting.

## Empire Design

* **Name:** Eldanær Stellar Authority (adj. Eldanæran)
* **Ship Prefix:** ESA
* **Homeworld Class:** Tropical
* **Homeworld:** Dærun
* **Star Name:** Ræn
* **City Design:** Necroid
* **Origin:** Necrophage
* **Authority:** Imperial
* **Ethics:** Fanatic Authoritarian, Xenophobe
* **Civics:** Byzantine Bureaucracy, Police State
* **Flag:** Blocky 2 (diamond with notch and circle), double hemispheres, dark green and black
* **Ship Design:** Fungoid
* **Ruler Name:** Hmaalurd Sooq
* **Ruler Appearance:** color 4, clothing 1 (numbers are the ones shown in-game)
* **Room:** Peaceful Traders (room 14)
* **Ruler Title:** Autarch
* **Heir Title:** Coadjutant

**Gameplay Notes:** The Eldanær consider themselves to have culturally transcended their biological drive to necrophage others indiscriminately. Generally, avoid using the Necrophage Purge type unless you develop a particularly hated enemy. They prefer to establish trading partners and maintain commercial pacts, but keep their partners at arm's length. Although "protecting" the secret of their origin fuels their paranoid xenophobia, they don't implicitly hate other species. Open Borders are preferred.

The Stellar Authority is a complex and impenetrable bureaucracy with many overlapping (and sometimes contradictory) layers, so Stratified Economy is preferred for any free Pops. Because the Eldanær consider themselves civilized, they tend to grant Residency to any species in their empire that originated in another space-faring empire and came peacefully (although they generally avoid migration treaties) as well as synthetics. On the other hand, they consider themselves superior to less technologically-advanced societies and view it as no contradiction to conquer and enslave primitive species or uplifted species. The slavery type should fit the species traits - living standards can vary, but giving the K'foori and Zdremites Social Welfare or Decent Conditions is preferred.

When selecting a third civic, consider Corvée System to support their many-tiered, authoritarian society, or Merchant Guilds (and the Mercantile diplomatic stance) to lean into their trade ambitions.

Ascending along the biological path (Engineered Evolution, Evolutionary Mastery) is preferred because Synthetic Evolution disables the necrophage mechanics. They prefer to swap Enduring for Venerable and acquiring Robust as traits - this leans hard into their role-play as incredibly long-lived. Thrifty is a good choice to replace Traditional if you lean into Merchant Guilds.

Finally, try to build a Deep Space Black Site in a starbase in every system with inhabited planets, habitats, etc. The ESA is a rigid, authoritarian state after all. I was originally inspired to create some sort of totalitarian empire based on the species image from the Living State technology (unlocks Deep Space Black Site), which is why the Eldanær have the same portrait.

## Species Design

The species bios included here are not visible in-game other than the main empire-level description available on the empire selection screen. This is because the game cannot load localised text for `species_bio` in either prescripted races or the `create_species` effect, and also does not support escaped newline characters `\n`. This is reported as a bug [here](https://forum.paradoxplaza.com/forum/threads/stellaris-v3-0-2-91c1-species_bio-for-prescripted-countries-or-for-the-create_species-effect-does-not-resolve-localisation-text-and-instead-show.1471611/).

### Eldanær

* **Name:** Eldanær (pl. Eldanær, adj. Eldanæran)
* **Class:** Fungoid (portrait `fun7`)
* **Namelist:** Fungoid 2 (mod uses an edited version of this list)
* **Traits:**
    * Necrophage
    * Traditional
    * Charismatic
    * Enduring
    * Slow Breeders
    * Decadent

> The Eldanær are a polished, dignified species that actively cultivates an air of genial sophistication with outsiders. Their long lifespans (individuals commonly live for centuries) coupled with a slow reproductive process led their society to form a rigid hierarchy that manages socio-political position, economics, and succession.
>
> Their outward image belies a horrifying secret: the Elanær can only reproduce by slowly germinating spores inside still-living K'foori - the plantoid species that evolved sapience long before them on their shared, lush homeworld. This is actively denied by the Stellar Authority, but whispers of the practice and the ubiquitous presence of servile and short-lived K'foori lend little credibility to the assertion. Even more disturbing rumors have begun to surface: the Eldanær may be experimenting using other species as hosts.

### K'foor

* **Name:** K'foor (pl. K'foori, adj. K'foorian)
* **Class:** Plantoid (portrait `pla7`)
* **Namelist:** Plantoid 4
* **Traits:**
    * Ingenious
    * Budding
    * Strong
    * Unruly
    * Fleeting

> K'foori are the original sapients to evolve on Dærun (a secret carefully guarded by the Stellar Authority). The lush planet provided for all of their needs so they did not advance technologically much beyond peaceful communities of hunter-gatherers. However, the jungles were an ideal breeding ground for many types of fungus. At some point, the genetic ancestors of the Eldanær began as a parasitic nuisance to the K'foori.
>
> K'foor primitive medicine was enough to defend against easily-detectable surface infestations, but had no concepts of internal medicine. Over centuries the Eldanær precursors evolved to survive long periods of dormancy within prospective hosts and to germinate slowly, invisibly, and inevitably. The fungus coopted and replaced a K'foor from the inside-out, which jump-started its own evolution to sapience and then dominance. Despite tight information control by the Stellar Authority, even the most servile modern K'foor seems to harbor a deep sadness for what was lost.

### Zdremite

* **Name:** Zdremite (pl. Zdremites, adj. Zdremitan)
* **Class:** Lithoid (portrait `lith8`)
* **Namelist:** Lithoid 3
* **Traits:**
    * Lithoid
    * Very Strong
    * Resilient
    * Slow Learners
    * Sedentary

> The multiverse has seen fit to tie the fate of the Zdremites to that of the Eldanær. These slow-and-steady lithoids are native to a particularly high-gravity planet covered in dense vegetation. Zdemite society invariably develops into small independent enclaves carved out of the dangerous jungles of Zdrel, governed primarily by military organizations that maintain a tenuous status quo peace over the livable land. While individuals are often slow to develop new skills and innovations, their long lifespan and generational knowledge bends towards technological solutions to create more livable space.
>
> Their natural strength and steadfast attitude inevitably earns the trust and respect of the Eldanær. Following a brief first contact/annexation war, the Zdremites integrate with the Eldanær and are entrusted as honored protectors from other, dangerous xeno influences.

### Special Bonus for the Pre-Scripted Empire

If you play the Eldanær Stellar Authority with both of its species (Eldanær and K'foori) exactly as they are pre-scripted, you will receive a small bonus.  At game start, the Eldanær will also receive Natural Sociologists to use their unspent trait point, while the K'foori will have Strong replaced with Serviles as well as replacing Unruly with both Slow Learners and Deviants to more accurately reflect their lore.

# Custom Scripting

There is a new diplomatic personality, the Cautious Autocrats, that I re-weighted slightly to try and represent the Eldanær Stellar Authority. Unfortunately I can't find a way to get them to prefer opening embassies with other species. There are events to try and prompt the AI to set the preferred slavery types on the K'foori and Zdremites, but the AI seems to be able to change slavery policies even if they are on cooldown.

The bulk of the scripting is to support game setup and the new Colossus weapon. Have fun necrophaging entire worlds!

## Compatibility

Built for Stellaris version 3.6 "Orion."  Not compatible with achievements.

All of the mod's changes are fully custom-scripted, so it should play well with most other mods.

## When to Install

This mod can be safely added to your savegame after the game has started, but not removed.  This mod adds a technology, associated ship components, an origin, a species trait, and other types of object to the game.  All of these things will alter your savegame.

## Required Mod Dependencies

[Planetary Modifier Enhancements](https://steamcommunity.com/workshop/filedetails/?id=2496357128) is used to apply the "Part of an Extensive Moon System" to the homeworld.

## Recommended Companion Mods

I've made a few enhancement mods that were inspired by things I found in the code as I scripted the Eldanær Stellar Authority. These affect game areas that the ESA uses and will improve your experience.

[Primitive Conquest Enhancements](https://steamcommunity.com/workshop/filedetails/?id=2488154830) ensures that primitive planets you convert with the Necrophagic Spore Diffuser are properly given existing infrastructure as if conquered. It also helps with the primitive-conquering style of Necrophages, and because the Zdremites are lithoids this mod will be useful for avoiding farming districts being generated on their homeworld. It also helps the AI more fairly set up its starter primitives, should the ESA or any other necrophage be randomly selected to spawn.

[Special Leadership Privileges for Battle Thralls and Bio-Trophies](https://steamcommunity.com/sharedfiles/filedetails/?id=2496357447) will allow you to use Battle Thralls as military leaders if you so choose.  The role-play for the Zdremites is that of "honored protectors" so this allows them to serve in (military) leadership roles.

# Known Issues

Because `gov_bureaucratic_autocracy` is not a built-in type of government, it doesn't have a matching special message for when space pirates first spawn. The game will display a default fallback, but log an error like this:

`[14:43:11][effect_impl.cpp:18754]: Bureaucratic Autocracy is missing an option in pirate.1, using fallback option instead at file: events/pirate_events.txt line: 215`

# Changelog

* 1.0.0 Initial version
* 2.0.0 Support Planetary Modifier Enhancements new version
* 2.0.1 Improve README and Steam description (no functionality changes)
* 2.1.0
    * Tagged as "Military" because of the Colossus weapon
    * added the dependency on [Planetary Modifier Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2496357128) to the `.mod` file as well
    * Fixed scripted 3rd trait for Eldanaer starting governor - was incorrectly adding Iron Fist a second time instead of Righteous
    * Fix high gravity origin trait to allow exactly one of the high/regular/low-G versions at a time
    * Changed usage of `owner_main_species` to `owner_species` (based on [Dev Diary 204](https://forum.paradoxplaza.com/forum/developer-diary/stellaris-dev-diary-204-scripting-language-and-moddability-improvements.1461327/))
    * High-G origin gives +5% happiness on high-G planets, -5% on low-G
* 2.2.0 Maintenance release
    * Add event to flag the game as having this mod installed (global flag `eldanaer_stellar_authority_installed`)
    * Remove extra images files to keep distribution lightweight
    * Update README
* 2.2.1 Add "Technologies" tag because of the Colossus weapon, explicit mod dependency in description
* 2.3.0 Add install flag for single-player game load
* 2.3.1 Support new flag from Full Military Service for Battle Thralls (now known as Special Leadership Privileges for Battle Thralls and Bio-Trophies)
* 2.3.2 Support new flag from Leader Traits: Enhanced Randomisation, fix High-G origin so starting Pops have the positive trait
* 3.0.0 Mark as compatible with Stellaris version 3.1 "Lem"
    * Origin: High-G trait uses new triggered bonuses (similar to the changes to Void Dweller)
    * Origin: High-G is prohibited for Machine Intelligences
    * Handle hive mind necrophages (most of the special Eldanær setup is disabled but the Zdremites will still spawn)
    * Starting sector has a custom name
    * Necrophage colossus weapon updated to be unable to fire on crisis worlds, but fungoid, necrophage, hive minds can use it against hive planets
    * Colossus weapon works with new game features
    * Colossus weapon ignores presapients
* 3.1.0 Ensure Zdremites have enough mining districts available from deposits
    * Minor update for compatibility with Planetary Modifier Enhancements 2.5.0
* 4.0.0 Update for Stellaris version 3.2 "Herbert"
    * Prescripted empire species are both indeterminable gender
    * Zdremites are indeterminable gender
    * Planet killer denies usage unless you have full native interference
    * Add interaction with [Retain Leaders from Integrated Subjects](https://steamcommunity.com/sharedfiles/filedetails/?id=2553818684): primitive worlds necrophaged via the Necrophage Spore Diffuser will allow you to acquire its necrophaged leaders
    * Add interaction with [Primitive Conquest Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2488154830): primitive worlds necrophaged via the Necrophage Spore Diffuser will generate infrastructure as if they were conquered
* 4.1.0 Pre-scripted species enhancements
    * K'foori swap Rapid Breeders for Budding
    * If playing the Eldanær Stellar Authority with both species as originally designed, they will be altered slightly:
        * Eldanær gain Natural Sociologists (uses up previously unspent point)
        * K'foori trade Strong for Serviles
        * K'foori trade Unruly for Slow Learners and Deviants
* 5.0.0 Update for Stellaris version 3.3 "Libra" - integrate new Stellaris features; no functionality changes
* 6.0.0 Update for Stellaris version 3.4 "Cepheus" - integrate new Stellaris features; no functionality changes
* 7.0.0 Update for Stellaris version 3.6 "Orion" (and changes from version 3.5 "Fornax")
    * Integrate underlying game changes (notably random empire names)
    * Necrophagic Spore Dispersal technology is easier to draw if you have the Javorian Pox Sample
* 7.1.0 Remove no-longer-necessary custom on_actions `on_primitive_planet_transferring` and `on_primitive_planet_transferred`

## Source Code

Hosted on [Github](https://github.com/corsairmarks/eldanaer_stellar_authority)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.