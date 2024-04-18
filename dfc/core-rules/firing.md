---
title: 'Firing'
excerpt: 'Once a group has moved, all of its ships may fire weapon systems if their orders permit them to do so.'
position: 6
---

# {{ $frontmatter.title }}

Once a group has moved, all of its ships may fire weapon systems if their orders permit them to do so.

## Firing Procedure

1. Check detection range and arc.
1. Allocate Attack dice.
1. Roll to hit.
1. Total up Hull damage inflicted.
1. Roll saving throws and deduct Hull points.
1. Roll for crippling damage if Hull is reduced to 50% or less.
1. Roll for catastrophic damage effects if Hull is reduced to 0 or less.

## 1. Check Detection Range and Firing Arc

In space combat few weapons really have a 'maximum range'. Take away the effects of atmosphere and gravity from the energy of a shot - whether from a kinetic striker or a thermal beam - and it will keep going for an almost infinite distance.

However ships still need to be able to accurately predict where enemies will be when the weapon's fire reaches them in order to plot their location and accurately fire on them.

To fire a weapon at a target, it must be within both weapon range and firing arc.

To determine the effective range of a ships weapons, nominate a target and use the following formula to determine weapon range:

**Attacker's Scan + Target's Signature = Weapon range for attacker**.

If the attacker is within range of the target, it may potentially fire upon it. The next step is to check whether the target is within any of the attackers weapons' firing arcs.

Look at the weapon system's Arc characteristic in the firing ship's description and use the arcs on the base to check if it is within arc of any potential targets. If there are any targets within both weapon range and firing arc, the attacking ship may fire weapons at those targets.

There are many potential targets in Dropfleet, but you may not fire upon friendly ships.

As orbital space is three dimensional, and because of the ability to see all other models as stated above, ships do not block each other from shooting other ships - this applies even if on the table top they may appear to be hiding behind each other or unable to actually 'see' the other ship.

Close Action weapons are short ranged, only using the attacker's Scan - see [Weapon Special](/en/dfc/special-rules#close-action) rules for more detail.

### Energy Spikes

Certain events cause Energy Spikes to be placed on ships to mark their current status. Energy spikes represent all kinds of different events that assist the enemy in accurately targeting the ship - engine usage, weapons fire, even leaks caused by damage or enemy ships actively scanning for the vessel. Energy spikes come in two types: Minor and Major.

* **A Minor energy spike increases the ship's Signature characteristic by 6"**.
* **A Major energy spike increases the ship's Signature characteristic by 12"**.

A ship only has one Spike at a time. If a ship already has a Minor Spike and it gets a second one, it increases the Minor Spike into a Major Spike. If a ship already has a Major Spike token it is lit up like a proverbial Christmas tree and doesn't receive any further spikes until the Major Spike has been removed or reduced to a Minor Spike.

Signature increases gained through Spikes only last as long as the Spike is present on that ship.

::: info _For example; A ship with a Signature of 6" gains a Minor Spike. Its Signature will count as 12" until the Spike is removed. If the ship gains another Minor Spike it becomes a Major Spike and the ship counts as Signature 18" until the Spike is removed. When the Spike is removed, the ship returns to having a Signature of 6"_.
:::

Use the status wheel on a ship's base to track its energy spikes, turning the wheel as appropriate when spikes are gained or lost. Players may use a marker to represent these if they wish.

## 2. Allocate attack dice

The Attack number on a weapon profile is the number of Attack Dice that are rolled when that weapon is used.

Each firing ship selects a weapon system and a target in both weapon range and weapon arc. The target is then allocated **all** of that weapon systems Attack Dice. Attack Dice from a single weapon system may not be split over multiple ships. You may repeat this for all weapon systems the firing ship(s) are allowed to fire.

When rolling for several weapon systems with different characteristics at once it can be helpful to use different coloured dice to represent the different weapon systems instead of rolling each one separately.

Some weapon systems roll a random number of Attack Dice (i.e. D6 or D3) that is determined each time they shoot. Roll to see how many Attack Dice the weapon system generates before allocating them to available targets.

An active Group will usually contain multiple ships with weapon systems to fire. **All of a Group's Attack Dice must be allocated between the available targets before any rolls to hit are made**. This helps to speed up game play and prevents the firing player from excessively optimising their shooting in an unrealistic fashion.

### Close Action weapons

Close Action weapon systems have a short effective range but they are fast firing and require small amounts of energy to use.

Close Action weapon systems can always be fired in addition to any other weapon systems permitted by a ship's orders. If a ship may not fire weapon systems it may not fire its close action weapon systems either.

## 3. Roll to hit

Roll allocated Attack Dice and compare the results to the weapon's Lock characteristic (after applying any modifiers). Any dice that have rolled at least that number have scored a hit. Any dice that have rolled under that number have failed to hit.

Remember, rolls of a 1 after modifiers always miss and rolls of 6 after modifiers always hit.

You can group identical weapons firing at the same target and roll them together to help speed up game play.

### Critical Hits

**Any Attack Dice which scores two or more higher than the weapon system's Lock number is considered to have scored a 'critical hit'. The Hull damage caused by that Attack Dice ignores the target's Armour saving throw altogether**.

Passive Countermeasures can still attempt to save against critical hits using their additional Armour value (see [Passive Countermeasures](/en/dfc/core-rules/damage#passive-countermeasures) for more details).

::: info _For example, if a weapon system has a Lock roll of 4+ any Attack Dice that roll 6 will ignore the target's Armour saving throw and be applied directly to the target's Hull. A weapon system with a Lock roll of 3+ would ignore Armour saves on rolls of 5 or 6 and so on_.
:::

### Shooting between Orbital Layers

A ship firing from one Orbital Layer to another suffers a +1 penalty to its weapon's Lock value (i.e. 4+ Lock becomes 5+).

### Shooting into & out of Atmosphere

::: tip _The difficulty of shooting between Orbital Layers is compounded when shooting through Atmosphere, where firing anything from a laser to a mass driver becomes highly inaccurate as energy bleeds off and is lost, plasma disperses etc. Targeting and effectively damaging ships or cities in Atmosphere is roughly analogous to hitting an object at the bottom of a slime filled pond_.
:::

**Unless a weapon system is specifically designed to attack such enemies, any weapon system firing from Atmosphere or at a ship in Atmosphere has its lock value changed to 6+ regardless of any other modifiers. In addition to this, detection range is limited to the firer's Scan value**. Signature and energy spikes are ignored.

Close Action weapons may not fire into or out of Atmosphere.

Close Action weapons may not be fired while in atmosphere unless otherwise stated by a ship or weapon special rule.

Certain rules such as Bombardment and Air- to-Air override the penalties for shooting through orbital layers; these are covered in the special rules section or in individual ship entries.

### Bombardment

Sometimes a ship's best course of action is to destroy the very planet it is fighting over. Ships may target Sectors (see [Sectors](/en/dfc/core-rules/ground-combat#sectors)) just like any other target, but the following rules apply. See the [Ground Combat](/en/dfc/core-rules/ground-combat) section for more details on Sectors and Clusters.

**Sectors can only be targeted by ships in Low Orbit** and follow the normal rules for being in Atmosphere.

If a Sector receives any damage it takes saving throws against it just like a ship. Critical hits ignore the saving throw as usual, however as most weapons will have a Lock value of 6+ for targeting something in Atmosphere, you will need a specialist weapon to achieve a Critical hit. (i.e. a weapon with the Bombardment special rule). **You may only target a Sector with weapon systems if it does not contain any friendly Ground Assets**.

### Bombardment Collateral Damage

If a Sector takes a damage point and the Sector is occupied by Ground Assets then you must roll for collateral damage. Each point of damage will inflict one point of damage on a Ground Asset in this sector (armour saving throws may be taken as normal - see [Ground Assets](/en/dfc/core-rules/ground-combat#ground-assets) for more details). The player that inflicted the damage chooses how to distribute this damage. One point of damage must be allocated to each Ground Asset before a second point may be allocated.

A Sector that loses all of its Hull points is turned into ruins. If there are any Ground Assets in the sector, roll a D6. If the result is a 2 or more, all Ground Assets in the Sector are destroyed, representing the apocalyptic devastation done to a wide area of the surface. This will also remove the Sector's value as a strategic objective. Ruins can still be bombarded to try and destroy ground assets, though they have no hull value so do not record this damage.
