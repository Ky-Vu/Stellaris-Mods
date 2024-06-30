# Stellaris-Mods
Collection of various mods I made

# Resource Mods #
* Note: B1/B2/B3 denotes each level of building - see https://stellaris.paradoxwikis.com/Unique_buildings to get a grasp on what I mean in the details below
## Basic Resource Rework ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3265433130
### Description ###
This mod is an attempt to change the instant gratification that the resource production enhancement buildings give of +25% (+12.5/16% food depending on empire type) to each worker and make it more worthwhile to build tall on planets. I.e. instead of +25/50% for every Technician on build/upgrade, you now get additive multiplier based on the number of Technicians you have (+100% at 50 Technicians with Energy Nexus).

It is also an attempt at making Strategic Resources (SR) feel more in-lore. Rather than slapping on an upkeep of 2 SR for the building, you now have to worry about each worker utilising the SR for their job. This also curbs the ease of access into Strategic Resources for increased base resource production, as you would now have to account for how many workers you have before upgrading your relevant building (-10 SR for 50 workers of the job type).

I may or may not continue updating this in the future. But this should essentially work for previous versions as well (unless the structure of the game is different).

May or may not be compatible with my other works. I haven't really tested but I will be making an all-in-one resource overhaul one day.
### Detailed Changes ###
* Energy Grid/Nexus || Mineral Purification Plant/Hub || Food Processing Facility/Center
  - Each Technician/Miner/Farmer increases output of other Technicians/Miners/Farmers by 1%/2% for B1/B2

* Energy Nexus || Mineral Purification Hub || Food Processing Center
  - Each respective building Strategic Resource (Exotic Gases/Rare Crystals/Volatile Motes) upkeep reduced to 1
  - Increases upkeep of each Technician/Miner/Farmer by 0.2 of respective strategic resource
    - Miners and Purification Hub utilize Rare Crystals instead of Volatile Motes - this is to make gestalts rely on all 3 Strategic Resources more evenly

* Galactic Stock Exchange
  - Provides only flat 5% trade multiplier for the planet, but each Clerk now provides 2.5% trade multiplier

* Bio-Reactor/Advanced Bio-Reactor
  - Base Food production for Anglers and Farmers now only reduced by 2
  - Base Energy production for Anglers and Farmers now only increases by 1 ***but***
    - Each Angler and Farmer increases Energy production by 1%/2%
## Advanced and Abstract Resource Rework ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3276200012
### Description ###
Similar to the Basic Resource Rework mod, this mod is an attempt to change the instant gratification that the resource production enhancement buildings give and is also an attempt at making Strategic Resources (SR) feel more in-lore.

I may or may not continue updating this in the future. But this should essentially work for previous versions as well (unless the structure of the game is different).

May or may not be compatible with my other works. I haven't really tested but I will be making an all-in-one resource overhaul one day.
### Detailed Changes ###
* Research
  - **Institute/Supercomputer**
    - Empire limit increased to 10
    - Planet limit of 1
    - +5% all research now reduced to +0.5% (this will show up as +0% in the modifiers but it is working - I don't know how to fix this)
    - +1 Scientist Leader cap now reduced to +0.2
    - +0.5% all research produced for each researcher per researcher
    - +0.5 Exotic Gases upkeep for each researcher
  - **Faculty of Archaestudies**
    - Empire limit removed - now Planet limit of 1
    - If built on *non-*Relic world:
      - +0.1 Minor Artifacts produced for Archaeoengineers on non-Relic worlds
      - +3% Archaeostudies research (+13% with AP)
      - +30 Max Minor Artifacts cap (+130 with AP)
    - If built on Relic world:
      - +0.3 Minor Artifacts produced for Archaeoengineers on Relic worlds
      - **All** researchers +0.05 Minor Artifacts (this affects the above points so it's actually +0.35 yes...)
      - +15% Archaeostudies research
      - +150 Max Minor Artifacts cap
    - AP effects
      - **All** researchers +0.05 Minor Artifacts
      - +10% Archaeostudies research
      - +100 Max Minor Artifacts cap
* Unity
  - **Monuments**
    - +0.15%/+0.3%/+0.5% unity per Bureacrat/Manager/Priest/Steward/Synapse Drone/Coordinator/Bio-Trophy for B1/B2/B3
    - +0.25/+0.5 rare crystals upkeep per Bureacrat/Manager/Priest/Steward/Synapse Drone/Coordinator for B2/B3
    - +0.05/+0.1 rare crystals upkeep per Bio-Trophy for B2/B3
* Alloys/CGs
  - Alloy Plant/Fabricator
    - +0.5% (0.63% catalytic) alloy/CG per metallurgist/artisan respectively and doubles for each upgrade (+1/2 % with ringworld boost (e.g. +0.75% on base))
    - +0.2 volatile motes on B2 and +0.4 volatile motes on B3 per metallurgist/artisan
  - Ministry of Production/Resource Processing Center
    - +1% (1.5% catalytic) alloy/CG per metallurgist/artisan respectively
    - -0.5% minerals upkeep per metallurgist/artisan respectively
    - -0.75% food upkeep per catalytic technician
    - -0.1 volatile motes upkeep for each metallurgist/artisan/catalytic technician
## Strategic Resource Rework ##
### Detailed Changes ###
* Strategic Resource Gatherers:
  - Base output increased to 4
* Ancient Refinery:
  - +15% to all Strategic Resource Gatherers and Refiners reduced to only +10% to all Strategic Resource Gatherers
  - Each respective Strategic Resource Refiner increases output of their respective SR by 2.5% and mineral upkeep by 1%
  - Each respective Strategic Resource Gatherer increases the output of Refiners of their respective SR by 5% and mineral upkeep by 2%
* Ascension Perk
  - Increases Ancient Refinery bonus of +10% to +35%
  - Increases base output of all Refiners by 1
## Bio Waste Reactor ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3252366076
### Description ###
A mod for allowing machine empires to reprocess food into usable energy. This is based on the previous version of the bio reactor. Also has a FE/Cosmogenesis equivalent. Created on/for v 3.12.*

Highly recommended to start a new save file to avoid any issues. This mod was made for my own entertainment.

May or may not be compatible with my other works.
### Detailed Changes ###

* Bio-Waste Reactor:
  - Upkeep: 25 food
  - Produces: 15 energy

* Advanced Bio-Waste Reactor:
  - Upkeep: 50 food
  - Produces: 30 energy

* Organo-Conversion Hub:
  - Upkeep: 50 food
  - Produces: 50 energy

* Organo-Conversion Center:
  - Upkeep: 50 food
  - Produces: 150 energy
## Food Market ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3266126155
### Description ###
An alternative to the bio-reactor for angler empires which effectively converts food to trade instead. Angler empires cannot research the bio-reactor but can research the Fish/Food Market for increased trade value.

This variant is meant to be a simple add-on to the base game. This was not made with my resource reworks in mind.

May or may not be compatible with my other works.
### Detailed Changes ###
* Fish Market
  - Alternative to the Bio-Reactor which effectively converts 2 Food to 2 Trade
# Civic Mods #
## Natural Neural Network Civic Rework ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3266010733
### Description ###
Natural Neural Network always felt out of lore and lackluster, being only +1 to all research for unemployed pops. It doesn't really make sense to have only the drones not working be mini-computation chips. It'd be like having a CPU dedicate an entire single core to doing calculations rather than all of them process it.

This rework makes it so all pops get some amount of research and is fundamentally dependent on the number of drones dedicated to research. I.e. the more research drones you have, the more each drone provides research.

This is also aimed at making NNN more viable for hive empires as a research-focus civic.

Highly recommended to start a new save file to avoid any issues. May or may not be compatible with my other works.
### Detailed Changes###
All drones - +0.005 all research. Stacks additively per brain drone employed (+0.1 for 20/+0.3 for 60).

E.g. for 60 brain drones, all drones provide +0.3. If you have 300 drones, that's +90 monthly all research.
(Math: 0.005\*(insert number of brain drones)\*(insert modifiers)\*number of pops=monthly research)
# Trait Mods #
## Machine Durable Trait Change ##
### Link ###
https://steamcommunity.com/sharedfiles/filedetails/?id=3266013571
### Description ###
Made on a whim to keep consistency with the cyborg trait of the same name.

Highly recommended to start a new save file to avoid any issues. This mod was made for my own entertainment.

May or may not be compatible with my other works.
### Detailed Changes ###
* Machine/Robot Trait - Durable
  - Cost increased to 2
  - Changed Energy upkeep (-10%) to Amenity usage reduction (-50%)
* Machine/Robot Trait - High Maintenance
  - Cost decreased to -2
  - Changed Energy upkeep (+10%) to Amenity usage increase (+25%)
# Miscellaneous Building Mods #
