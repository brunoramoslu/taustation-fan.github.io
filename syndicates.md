# Syndicates

A Syndicate is a group of players with a common agenda teaming up.
They are roughly equivalent to guilds or teams of other games.

# Table of Contents

* [Formation Process](#formation-process)
* [Membership Management](#membership-management)
* [Banking](#banking)
* [Communication](#communication)
* [Experience](#experience)
* [Storage](#storage)
* [Campaigns](#campaigns)

## Formation Process

To form a syndicate, the designated leader must fulfill these requirements:

* Level 14 or higher
* Reputation *respected* or higher with the intended home station's faction
* must have finished the course *Syndicate Basics* (which has *Introduction to Leadership* as a prerequisite)
* must have at least 100,000 credits at their disposal.

Having fulfilled these requirements, a player can go to a government center of
the respective government, spend the 100,000 credits, and use this to
found the syndicate. It needs a name, a three-letter shorthand (limited to a-z, A-Z, 0-9) and a description (up to 300 characters).

A syndicate can specify a minimal player level and a required genotype for members.

Within the next 5 days, a syndicate needs three more co-signers.
The three co-signers need only fulfill the genotype
and level requirements of the syndicate (if any), there are no reputation or
monetary requirements for the co-signers or other syndicate members.

## Membership Management

Once a syndicate has its three co-signers, it is fully formed. The co-signers
automatically become applicants at the syndicate.

The owner can then approve or reject applicants, and configure whether the
syndicate is recruiting or not. If it is recruiting, players can apply
independently of location.

A syndicate starts with slots for 10 members. This limit can be extended
by spending bonds: 

|Extension to|Cost in bonds| cumulative costs |
|------------|-------------|------------------|
| 15         | 990         | 990              |
| 20         | 1290        | 2280             |
| 25         | 1790        | 4070             |
| 30         | 3090        | 7160             |
| 35         | 6190        | 13350            |
| 40         | 13890       | 27240            |

A syndicate also earns one slot for each tier-up (so every 5 levels).
Membership capacity is limited to 40. When a syndicate gains a slot
through advancing a tier, the bond cost for the final slots decrease
(but you also get fewer, since the limit stays at 40).

The syndicate founder can approve applicants, kick members, and even
ban them from re-applying. They can also give other members the same
privilege by applying the *Membership Management* role.

## Banking

Syndicates have a separate bank account. Members can donate bonds and
credits to the syndicate.

There is also a 5% tax by default on any credits that members get or
deposit into the bank, and this 5% is diverted to the syndicate bank account.

This tax rate can be changed to any integer number between 0 and 100% 
inclusive by the syndicate members with the "Money management" role.

## Communication

Syndicate members are clearly marked on their profile page as being a
member of a syndicate, and the chat shows the three-letter shorthand.

Syndicates get a private chat room.

At level 4 Syndicates get a private forum.

Syndicate members can also send broadcast in-game-mails to all members of the
syndicate.

## Experience

Syndicates gain experience points through member activity,
and level up when the experience counter reaches 100%.

So far, it is unclear what syndicate experience or levels are good for,
except that syndicate levels are also grouped in tiers, and the
syndicate gets another slot when ascending to another tier.

## Storage

Each Syndicate automatically gets a shared, insecure storage unit in the Ruins
area of the station where it was founded.

It is a *small* storage with 50 slots, which can be extended to 150
slot for 484 bonds, or to 500 slots for 1209 bonds.

Every member can donate items to the syndicate by putting them
into the storage, and members with the *Inventory Management* role
also can take out items.

## Campaigns

Every syndicate member with the *Campaign management* role can start
a campaign at the *Ruins*, in the *Wilds* sub-area. The campaign manager
can select the difficulty, with difficulty availability depending on
syndicate level. She can also select among the syndicate member's tier
for opponent tiers. For example if a syndicate contains tier 1 through
tier 3 members, any combination of tier 1, tier 2 and tier 3 opponents
is possible.

Everybody who wants to participate in a campaign must come to the station 
where the campaign was started.

A campaign consists of several waves of opponents that syndicate
members have to defeat in combat. A wave contains roughly equal number
of fighters of each selected tier. Defeating all opponents of a wave
unlocks the next wave (or for the last wave, successfully terminates
the campaign).

Any syndicate member present at the starting station can attack any
opponent of the current wave that hasn't been defeated yet, and that
isn't currently engaged in combat. A syndicate member who attacked
an opponent and then fled (or was sent to Sick Bay or Brig) can only
attack the same opponent again (and not other opponents), unless another
syndicate member continues the attack.

The waves of opponents contain progressively stronger fighters, both
in skill level and physical stats.

The number of opponents is based on the number of syndicate members (but
assuming at least 5 for small syndicates),
multiplied by a factor for the campaign difficulty:

| Difficulty | Factor | Unlocked by level |Number of Stims awarded|
|------------|:------:|:-----------------:|:---------------------:|
| easy       | 2      |                   |          1            |
| normal     | 4      |            3      |          2            |
| hard       | 8      |            5      |          3            |
| extreme    | 12     |            7      |          4            |

### Campaign Loot

Once all opponents are defeated, each syndicate member who participated
in the campaigns gets stims as personal rewards for participating in
the campaign, directly added to the player's inventory.

The number
of stims depends on the campaign difficulty as shown in the table above.
The stims tier is at most the minimum of your own tier and
the max enemy tier of the campaign.

The syndicate also gets loot, which is deposited into its insecure syndicate
storage at the syndicate's home station.

This loot is typically similar to the rewards from *look for trouble*
and discreet work on the same station:

| System         | Station           | Typical Loot                              |
|----------------|-------------------|-------------------------------------------|
| Sol            | Nouveau Limoges   | Bonds, Tier 2 rations, Tier 1 weapons     |
| Alpha Centauri | Yards of Gadani   | G-SAG1E, Paris Sabre, Fire Fu of firefu   |
| L 726-8 A      | Orwell Stronghold | Spidersilk Suit Jacket, Illuminated Spade |
| L 726-8 A      | Spirit of Tianjin | Stims                                     |
| YZ Ceti        | Cape Verde SH     | Enhanced Arc Dancer's Suit, T4 rations    |
| YZ Ceti        | Spirit of NYC     | Stims                                     |

#### Epic Campaign Loot Items

In addition, if the campaign difficulty is at least *hard* and you include
the highest tier opponents that are available to you, you get *epic* weapons
and armors as loot. From a *hard* campaign and 25-30 members, you get two epic
items, and three for a *hard* campaign an 34-35 members. For *extreme* campaigns,
these numbers are roughly twice as high. For *normal* and *easy* campaigns, epic
items can drop, but it's not reliable.

The items seem to be more or less randomly selected from the tiers that are
part of the campaign. For example, you might get a tier 1 and a tier 5 item
for a *hard* tier 1 through 5 campaign. Some of these items are available
for sales from NPC vendors for bonds, and some items are not available any
other way.

The following epic items have been observed to drop from syndicate campaigns:

| Tier  | Type         | Item            |
|-------|--------------|-----------------|
|   1   | Armor        | [Bar Brawler's Blouse](https://alpha.taustation.space/item/bar-brawlers-blouse) |
|   1   | Armor        | [Gaule Training Vest](https://alpha.taustation.space/item/gaule-training-vest) |
|   1   | Armor        | [Ruins Rat's Pyjamas](https://alpha.taustation.space/item/ruins-rats-pyjamas) |
|   1   | Shotgun      | [Joanna](https://alpha.taustation.space/item/joanna) |
|   1   | Rifle        | [Ajax Systems Flame Dispenser](https://alpha.taustation.space/item/ajax-systems-flame-dispenser) |
|   1   | Rifle        | [Sloane 6000](https://alpha.taustation.space/item/sloane-6000) |
|   2   | Handgun      | [Reaper's Little Helper](https://alpha.taustation.space/item/reapers-little-helper) |
|   2   | Rifle        | [The Ayy-Kii 47](https://alpha.taustation.space/item/the-ayy-kii-47) |
|   2   | Armor        | [Anti-Energy Harness](https://alpha.taustation.space/item/anti-energy-harness) |
|   2   | Armor        | [Hippocratic Vest](https://alpha.taustation.space/item/hippocratic-vest) |
|   2   | Armor        | [Ranger Vest](https://alpha.taustation.space/item/ranger-vest) |
|   2   | Armor        | [Rumble Jacket](https://alpha.taustation.space/item/rumble-jacket) |
|   2   | Armor        | [Thief's Second Skin](https://alpha.taustation.space/item/thiefs-second-skin) |
|   3   | Armor        | [Ajax Systems Tactical Vest](https://alpha.taustation.space/item/ajax-systems-tactical-vest) |
|   3   | Armor        | [Bloody Battle Jacket](https://alpha.taustation.space/item/bloody-battle-jacket) |
|   3   | Armor        | [Brig Warden's Stab Suit](https://alpha.taustation.space/item/brig-wardens-stab-suit) |
|   3   | Armor        | [Aurorahunter](https://alpha.taustation.space/item/aurorahunter) |
|   3   | Blade        | [Barman's Caltrop](https://alpha.taustation.space/item/barmans-caltrop) |
|   3   | Blade        | [Battle Blade: Trailblazing Blazers](https://alpha.taustation.space/item/battle-blade-trailblazing-blazers) |
|   3   | Blade        | [Modified Shanker](https://alpha.taustation.space/item/modified-shanker) |
|   3   | Handgun      | [Pistol: Trailblazing Blazers](https://alpha.taustation.space/item/pistol-trailblazing-blazers)|
|   3   | Handgun      | [Blaster: Trailblazing Blazers](https://alpha.taustation.space/item/blaster-trailblazing-blazers) |
|   3   | Handgun      | [Thowan 89](https://alpha.taustation.space/item/thowan-89)|
|   3   | Sniper rifle | [ALNA-MODEX](https://alpha.taustation.space/item/alna-modex) |
|   3   | Sniper rifle | [Sniper Rifle: Trailblazing Blazers](https://alpha.taustation.space/item/sniper-rifle-trailblazing-blazers) |
|   4   | Armor        | [Battered Jerkin](https://alpha.taustation.space/item/battered-jerkin) |
|   4   | Armor        | [Consortium Catsuit](https://alpha.taustation.space/item/consortium-catsuit) |
|   4   | Armor        | [Heavy Explorer's Coat](https://alpha.taustation.space/item/heavy-explorers-coat) |
|   4   | Armor        | [Nomad's Robes](https://alpha.taustation.space/item/nomads-robes) |
|   4   | Armor        | [Wanderer's Jumpsuit](https://alpha.taustation.space/item/wanderers-jumpsuit) |
|   4   | Blade        | [Modified Shanker Deluxe](https://alpha.taustation.space/item/modified-shanker-deluxe) |
|   4   | Blade        | [Rusted Skin Slicer](https://alpha.taustation.space/item/rusted-skin-slicer) |
|   5   | Armor        | [Armure Bodysuit](https://alpha.taustation.space/item/armure-bodysuit) |
|   5   | Armor        | [Stylish Jacket](https://alpha.taustation.space/item/stylish-jacket) |
|   5   | Armor        | [Magnus Burnshield](https://alpha.taustation.space/item/magnus-burnshield) |
|   5   | Armor        | [Water Miner's Jumpsuit](https://alpha.taustation.space/item/water-miners-jumpsuit) |
|   5   | Blade        | [Katana: Trailblazing Blazers](https://alpha.taustation.space/item/katana-trailblazing-blazers) |
|   5   | Blade        | [Machete](https://alpha.taustation.space/item/machete) |
|   5   | Blade        | [Well-Worn Machete](https://alpha.taustation.space/item/well-worn-machete) |
|   5   | Short Barrel Rifle | [Blue Steel](https://alpha.taustation.space/item/blue-steel)
|   5   | Rifle        | [Mudskipper](https://alpha.taustation.space/item/mudskipper) |
|   5   | Shotgun      | [The Burke & Hare](https://alpha.taustation.space/item/the-burke-hare) |

---

[Back to the main guide](/)
