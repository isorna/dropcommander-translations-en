---
title: 'Damage'
excerpt: 'Every Attack Dice that equals or exceeds its Lock number inflicts the number of Damage points indicated for the weapon system.'
position: 7
---

# {{ $frontmatter.title }}

## 4. Total up Hull damage inflicted

Every Attack Dice that t has scored a hit inflicts the number of Damage points indicated for the weapon system. Commonly this is one point of Hull damage per Attack Dice but particularly destructive weapons may inflict more.

Some weapon system are unpredictable and will inflict a variable number of damage points on each hit scored (e.g. D6, D6+1 etc.). Roll any additional dice needed to determine the actual amount of damage inflicted before any Armour saving throws are made.

::: info _For example; A ship's description includes a rail gun battery with a Lock of 4+, 3 Attack and 1 Damage. This means that when the weapon system is fired three dice are rolled and each one scores a hit on roll of 4, 5 or 6. Each hit scored by the rail gun battery inflicts 1 Hull damage on the target_.
:::

## 5. Roll Armour saving throws and deduct Hull points

When a ship suffers Hull damage its Passive countermeasures (if it has any) and Armour may be able to prevent the damage being applied.

Roll a D6 for **each point of Hull damage inflicted** and compare it to the ship's Armour characteristic (after any modifiers). Any dice that rolled at least that number are successful Armour saves. Each successful Armour save reduces the Hull damage inflicted by one.

When a ship has more than one Armour characteristic, players choose the best applicable save and compare their roll to that.

Any unsaved damage will remove Hull points from the target ship. Track the Hull damage lost by ships by using the damage wheel on the model's base, counters or dice. Ships that have no Hull points left are destroyed and must roll for catastrophic damage to see how fiery their demise is.

### Passive countermeasures

::: tip _Some advanced ships have additional 'passive' countermeasures like energy shields, ablative clouds and force fields to protect their ships in addition to regular armour_.
:::

Passive countermeasures are shown by an additional Armour characteristic (e.g. 3+/4+ indicating a Passive Countermeasure save of 4+). Passive countermeasures are highly effective because they give a ship protection against critical hits which would otherwise punch through armour completely.

The downside to passive countermeasures is that they often increase a ship's Signature and may prevent it using its Point Defence while they re operational - any negatives are covered in the ship's specific information, or in faction specific rules.

When a ship has more than one saving throw, players choose the best applicable save and compare their roll to this.

::: info _e.g. A ship has a 3+/4+ save. It receives five hits   three are normal hits, and the remaining two are critical hits. The ship's owner rolls three dice needing 3+ for the normal hits, as this is their best save. They cannot take normal saves against the critical hits, but may take Passive Countermeasure saves, so they roll the remaining two save needing 4+, as this is the best save they can take against these hits_.
:::

### Shields up!

::: info _Passive Countermeasures work in a variety of different ways for different races. Some are all encompassing energy bubbles that offer staunch defence against all attacks, while others are only in use to protect certain key areas of a ship, making them less effective overall_.
:::

Some (usually the less powerful) Passive Countermeasures may be constantly in use, whereas very strong versions require the player to choice to deploy them or not (as raising shields will often have downsides).

Players must choose to raise shields at the same time that special orders are chosen for a Battlegroup. Each ship can opt to raise shields or not, and if raised, that ship can use Passive Countermeasures until its next activation. Mark ships with raised shields with tokens.

### Point Defence (PD)

Ships usually have their Point Defence as another line of defence to specifically protect them against damage inflicted by **Launch Assets and Close Action weapon systems**.

When a ship receives damage from one of the above sources roll, a number of D6 equal to the ship's PD characteristic (after any modifiers). **Any dice that rolls a 5 or more is a success**. Each success reduces the amount of Hull damage the ship suffers by 1. Armour saves may then be taken against the remaining Hull damage.

Critical hits **can** be stopped by Point Defence but each point of critical hit damage blocked takes two Point Defence successes instead of one.

::: info _For example; A cruiser with a PD characteristic of 6 is attacked and suffers four normal points of Hull damage and two points of critical Hull damage from Close Action weapon systems. Rolling six dice for Point Defence it gets 1, 2, 3, 4, 5, 6. - two successes. The ship's Point Defence can stop two points of ordinary Hull damage or one of the points of critical Hull damage_.
:::

## 6. Roll for Crippling Damage

When a ship has lost a cumulative total of more 50% or more of its starting Hull points it becomes Crippled and suffers Crippling Damage (so a ship with 4 Hull points becomes crippled when it has lost 2 or more Hull points). This is a one-time check to represent major systems taking too much punishment, minor systems shorting out and continuous battle damage taking its toll on the vessel.

A ship with the Dreadnought special rule becomes Crippled and suffers Crippling Damage when the ship is reduced to 18 Hull and suffers Crippling Damage again at 10 Hull or less instead of the usual 50% of original hull.

When a ship experiences Crippling Damage, roll a D6 and consult the relevant table on the following page to see where the Crippling Damage has occurred, and then roll a second D6 on the appropriate sub-table to discover the result. Dreadnoughts use special Crippling Damage and Catastrophic Damage tables, rolled in the same way.

**Ships with a starting hull value of 3 or less are never subject to being Crippled and do not roll on the on the Crippling Damage table**.

**If the Crippling Damage is the result of an attack, roll for the result at the end of the firing ships activation**.

**Ships only roll for Crippling Damage this way once, even if they pass their Crippling Damage threshold again (but would still be Crippled)**.

### Extra damage results and Armour saving throws

Many Crippling Damage results inflict additional Hull damage on the ship. Armour saving throws never apply against Crippling Damage as it represents the ship suffering internal collapses, cascade failures and systems quite literally melting down. It's worth noting that smaller ships like frigates are quite likely to be destroyed outright by Crippling Damage.

<table>
  <thead>
    <tr>
      <th colspan="6">Crippling Damage Table</th>
    </tr>
  </thead>
  <thead>
    <tr>
      <th>1st roll</th>
      <th>2nd roll</th>
      <th>Result on ship</th>
      <th>Extra Hull Damage</th>
      <th>Repair?</th>
      <th>Orbital Decay</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">1-2 Subsystems</td>
      <td>1-2</td>
      <td><strong>Bright flash... and nothing else:</strong> Gains a Minor Spike. If using Silent Running special orders, Signature is returned to normal instead.</td>
      <td>0</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Fire:</strong> Inflicts 1 additional point of Hull damage in each Roundup phase, before rolling Damage Control.</td>
      <td>0</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Energy Surges:</strong> May not use special orders.</td>
      <td>2</td>
      <td>Yes</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td rowspan="3">3-4 Hull</td>
      <td>1-2</td>
      <td><strong>Scanners Offline:</strong> Scan reduced to 1".</td>
      <td>0</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Armour Cracked:</strong> Armour value suffers +2 modifier for the rest of the game.</td>
      <td>2</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Hull breach:</strong> No additional effect.</td>
      <td>2</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td rowspan="3">5-6 Core Systems</td>
      <td>1-2</td>
      <td><strong>Engines Disabled:</strong> Thrust reduced by 50% (rounded up), and may not turn or change orbit.</td>
      <td>2</td>
      <td>Yes</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Weapons Offline:</strong> The next time it activates it may not fire any weapons or use any launch asset the next time it would be able to. In subsequent activations it may fire and launch assets as normal.</td>
      <td>3</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Reactor Overload:</strong> Roll again on the Crippling Damage Table.</td>
      <td>3</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
  </tbody>
  <thead>
    <tr>
      <th colspan="6">Dreadnought Crippling Damage Table</th>
    </tr>
  </thead>
  <thead>
    <tr>
      <th>1st roll</th>
      <th>2nd roll</th>
      <th>Result on ship</th>
      <th>Extra Hull Damage</th>
      <th>Repair?</th>
      <th>Orbital Decay</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">1-2 Subsystems</td>
      <td>1-2</td>
      <td><strong>Bright flash... and nothing else:</strong> Gains a Minor Spike. If using Silent Running special orders, Signature is returned to normal instead.</td>
      <td>0</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Atmospheric Containment Failure:</strong> Inflicts 2 additional points of Hull damage in each Roundup phase, before rolling Damage Control.</td>
      <td>0</td>
      <td>Yes - 2 needed</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Power Fluctuations:</strong> Suffers D3 Hull Points if going on Special Orders. If using Silent Running special orders, Signature is returned to normal instead. May not go on Silent Running.</td>
      <td>0</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <td rowspan="3">3-4 Hull</td>
      <td>1-2</td>
      <td><strong>Scanners Damaged:</strong> Scan reduced to 6".</td>
      <td>0</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Bulkhead Ruptured:</strong> No additional effect.</td>
      <td>1</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Auxiliary Core Collapse:</strong> No additional effect.</td>
      <td>2</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td rowspan="3">5-6 Core Systems</td>
      <td>1-2</td>
      <td><strong>Engine Destroyed:</strong> Thrust reduced by 2" and suffers D3 Hull Points if going on Max Thrust or Course Change.</td>
      <td>0</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>3-4</td>
      <td><strong>Weapon Destroyed:</strong> One weapon system at random may not be used for the rest of the game.</td>
      <td>0</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <td>5-6</td>
      <td><strong>Primary Core Leak:</strong> Suffer 3 additional points of Hull damage at the end of the Clean-Up Phase for the rest of the game.</td>
      <td>0</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

## 7. Roll for Catastrophic Damage

When a ship has no Hull points remaining it is destroyed. Ships with a starting Hull characteristic of 4 or more suffer Catastrophic Damage. Roll a D6 on the table below to see if its destruction has any additional effects that apply to other ships nearby. Ships with the Dreadnought special rule have their own Catastrophic Damage table.

Ships with a starting Hull characteristic of **3 or less** do not roll on this table and are removed from play when destroyed.

Ships in Atmosphere are do not roll on this table and are removed from play when destroyed.

Ships with a starting Hull characteristic of 10 and above increase the result of the D6 by 1.

Most Catastrophic Damage results can cause a ship to explode in some fashion. **The size of the explosion is determined by the starting Hull characteristic of the ship**.

* **Ships with a Hull characteristic of 4-6 explode with a D3" radius**.
* **Ships with a Hull characteristic of 7 and above explode with a D6" radius**.

Note that the explosion only ever effects ships on the **same Orbital Layer** as the destroyed ship.

<table>
  <thead>
    <tr>
      <th colspan="2">Catastrophic Damage Table</th>
    </tr>
  </thead>
  <thead>
    <tr>
      <th>D6 roll</th>
      <th>Result to all ships in explosion range</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1-2</td>
      <td><strong>Burn Up:</strong> No additional effect.</td>
    </tr>
    <tr>
      <td>3</td>
      <td><strong>Blazing Wreck:</strong> Gain a Minor Spike. If using Silent Running special orders, Signature is returned to normal instead.</td>
    </tr>
    <tr>
      <td>4</td>
      <td><strong>Shredded:</strong> Suffer 1 point of Hull damage. Armour and Passive Countermeasures may be used as normal.</td>
    </tr>
    <tr>
      <td>5</td>
      <td><strong>Explosion:</strong> Suffer 2 points of Hull damage. Armour and Passive Countermeasures may be used as normal.</td>
    </tr>
    <tr>
      <td>6</td>
      <td><strong>Radiation Burst:</strong> Suffer 2 points of Hull damage. Armour and Passive Countermeasures may <strong>not</strong> be used.</td>
    </tr>
    <tr>
      <td>7+</td>
      <td><strong>Distortion Bubble:</strong> Suffer D6 points of Hull damage (roll for each ship individually). Armour and Passive Countermeasures may <strong>not</strong> be used.</td>
    </tr>
  </tbody>
  <thead>
    <tr>
      <th>D6 roll</th>
      <th>Dreadnought Catastrophic Damage Table</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2-3</td>
      <td><strong>Fiery Descent:</strong> Any sector within 8&quot; of the ship suffers D6 Hull Points of damage. Tokens in these Sectors are destroyed on a roll of 2+ (roll separately for each).</td>
    </tr>
    <tr>
      <td>4</td>
      <td><strong>Immolation:</strong> All ships within 8&quot; gain a Major Spike and D3 Fires (see <a href
      ="#crippling-damage-table">Crippling Damage</a>).</td>
    </tr>
    <tr>
      <td>5</td>
      <td><strong>Superstructure Failure:</strong> All ships within 12&quot; take 2D6 damage on a roll of 5+ (roll separately for each). Armour and Passive saves may be made as normal.</td>
    </tr>
    <tr>
      <td>6</td>
      <td><strong>Magazine Detonation:</strong> All ships within 12&quot; take 2 damage. Armour and Passive saves may be made as normal.</td>
    </tr>
    <tr>
      <td>7+</td>
      <td><strong>Space-Time Rent:</strong> All ships with 6 or more starting Hull within 8&quot; take 3+D3 damage. Armour and Passive saves may be made as normal. All ships with 5 or less starting Hull within 8&quot; are removed from play with no Catastrophic Damage rolls.</td>
    </tr>
  </tbody>
</table>

## Damage control

Ships are able to repair crippling damage at the start of the 3rd step in the Roundup Phase. To repair crippling damage, select a friendly ship with one or more repairable crippling damage effects. Roll a D6 for each crippling damage effect that requires repair and consult the table below. Repeat this for each friendly ship that has a repairable effect and has not made a damage control attempt this turn.

Armour and Passive Countermeasures cannot prevent Hull damage from this source.

<table>
  <thead>
    <tr>
      <th colspan="2">Damage Control Table</th>
    </tr>
  </thead>
  <thead>
    <tr>
      <th>D6 roll</th>
      <th>Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>The ship suffers one point of Hull damage (no saves) and the Crippling Damage is not repaired. Roll again for repair at the end of the next game turn.</td>
    </tr>
    <tr>
      <td>2-3</td>
      <td>Crippling Damage is not repaired. Roll again for repair at the end of the next game turn.</td>
    </tr>
    <tr>
      <td>4-6</td>
      <td>The Crippling Damage is repaired and has no further effect.</td>
    </tr>
  </tbody>
</table>

### Orbital Decay

Several Crippling Damage results may also affect a ship with an Orbital Decay Crippling Damage effect which may be repaired.

A ship affected with Orbital Decay moves down one Orbital Layer in the Orbital Decay step of the Roundup Phase.

**Any ship that does not have the Atmospheric Rule that moves into atmosphere because of Orbital Decay is Destroyed - remove it from play without rolling on the Catastrophic damage table**.
