# Combat

During combat, each character has a limited set of Actions they can use (for most Player Characters, up to 2). They also get 1 Free move per turn. Their weapons, armor, equipment, talents, and traits determine how they can spend these actions.

Each Round of combat is divided into 2 phases: _Action Declaration_ and _Action Resolution_. In the _Action Declaration_ phase, each character declares the actions they intend to take. In the _Action Resolution_ phase, each of the declared actions is resolved.

* Typically, the Order of Resolution is
	* Resolve Free Movement
	* Resolve Independent or Uncontested Actions
	* Resolve Contested Actions

## Movement

Every player has a default speed, measured in squares (each square corresponds to about 1.5 meters). Most PCs have a default Move Speed of 4. They can spend an action to **Move**, moving up to their speed.

Characters get 1 Free Move Action per turn.

## Hit Points

You have a number of Hit Points (HP) equal to 10 + **Physical Resilience** + **Mental Resilience**

## Weapon Attacks

* Roll the Weapon's listed **Characteristic Die**. The result is your **Attack Value**.
* If your **Attack Value** beats their **Defense Value** you do damage equal to the weapon's Damage plus your **Characteristic Value**.
* **Advantage** allows you to roll one additional die and choose the higher. **Disadvantage** allows you to roll one additional die and take the lower. **Advantage** and **Disadvantage** can both stack with themselves, and cancel each other out.
* **Proficiency** with a Weapon grants an **Advantage**.

### Aim

If wielding a ranged or thrown weapon, like a Bow or Javelin, you can choose to take the Aim action. This grants **Advantage** with the next attack you make with that weapon before the end of the next round. This does not count as using a weapon for the purpose of multiple actions in a round.

### Unarmed Attacks

If you have a free hand, you can make a **Physical Power**-based **Weapon Attack** against a target of your choice. This has Speed 1 and Bludgeoning 0 by default.

### Damage

* If you hit with a Melee Weapon Attack, your damage is equal to the Weapon's Base Damage, plus your **Physical Power Value**.
* If you hit with a Ranged Weapon Attack, your damage is equal to the Weapon's Base Damage, plus your **Physical Finesse Value**.

### Two-handed Weapons

Attacking with a weapon with 2 hands uses 2 Actions, but grants Advantage on the attack.

## Defensive Actions

* For each time you take a **Defensive Action**, such as a **Block**, **Parry**, or **Dodge**, you can potentially avoid the damage of one incoming attack.
* Each **Defensive Action** gives you a **Defense Value**. If multiple attacks target you during the same turn, you must choose which **Defense Value** applies to which attack.
* If an **Attack Value** exceeds your **Defense Value**, you take damage.
* Any attacks against which you don't take an explicit **Defensive Action** will automatically hit.
* **Proficiency**, **Advantage**, and **Disadvantage** work in the same way as they do for **Weapon Attacks**.

### Block

* Shields and certain talents or traits grant you access to the **Block** action.
* A **Block**'s **Defense Value** is determined by rolling the corresponding **Characteristic Die** (usually Physical Resilience).
* Unlike **Parry** or **Dodge**, a single block value may be used against more than one incoming attacks. How many depends on the Item, Talent, or Trait granting the Block.

### Parry

* Certain weapons grant the **Parry** action.
* A **Parry**'s **Defense Value** is determined by rolling the corresponding **Characteristic Die** (usually Physical Power).
* A single **Parry** can only defend against one attack.

### Dodge

* Any character that isn't **Immobilized** can take the **Dodge** action.
* A **Dodge**'s **Defense Value** is determined by rolling **Physical Finesse**.
* A single **Dodge** can only defend against one attack.

## Armor and Damage Reduction

* Armor, as well as some Talents and Traits, provide Damage Reduction (DR). DR reduces the amount of damage taken from any attack, to a minimum of 1.
* If you aren't proficient with the Armor you're wearing, you only gain half of the DR benefit, and suffer an additional -1 Move Speed penalty.

## Stamina

Every Player Character, and many Non-Player Characters, have a certain amount of a resource called **Stamina**. This is a resource that regenerates between fights, and can be spent in a variety of ways during combat:

* Certain Talents and Traits grant abilities that require **Stamina** to use.
* **Stamina** can be spent to gain **Surges**.

### Surges

A **Surge** allows for a character to gain an extra action during a given round. Only one **Surge** can be used per round, and a **Surge** can be declared at any time during either the action declaration or resolution phases of combat. A **Surge** can not be used to take an Action using an item that has already been used a number of times equal to its **Speed**.

### Recovery

You can recover 1 **Stamina** by taking the **Recover** action. You can take this action once per round (you cannot take this action and use a **Surge** in the same round).

## Attacking or Defending Multiple Times in a Single Round

In general, you may only use a single item to attack or defend a number of times during a round equal to its **Speed**. If you are using a weapon for two or more different actions during a single round, use the smallest of the speeds.

If you are wielding multiple items, the Speed applies individually for each Item.

## Examples

### Example Weapons

* **Zweihander**
	* Size: Medium
	* Speed 1
	* Melee Weapon Attack (Physical Finesse, Piercing/Slashing 4, 2-handed)
	* Parry (Physical Power)
	* 1-handed attacks have Disadvantage
* **Longsword**
	* Size: Medium
	* Speed 1
	* Melee Weapon Attack (Physical Finesse, Piercing/Slashing 3)
	* Parry (Physical Power)
	* 2-handed attacks have Advantage
* **Shortsword**
	* Size: Small
	* Speed 2
	* Melee Weapon Attack (Physical Finesse, Piercing/Slashing 2)
	* 2-handed attacks have Advantage
	* Parry (Physical Power)
* **Dagger**
	* Size: Tiny
	* Speed 3
	* Melee Weapon Attack (Physical Finesse, Piercing/Slashing 1)
	* Thrown Weapon Attack (Physical Finesse, Piercing/Slashing 1)
	* Parry (Physical Power)
* **Short Bow**
	* Size: Small
	* Speed 2
	* Ranged Attack (Physical Finesse, Piercing 2)
	* Parry (Physical Power, Fragile)
	* Aim: Grants **Advantage** on next Ranged Attack with this weapon.
* **Long Bow**
	* Size: Medium
	* Speed 1
	* Ranged Attack (Physical Finesse, Piercing 4)
	* Parry (Physical Power, Fragile)
	* Aim: Grants **Advantage** on next Ranged Attack with this weapon.
* **Cross Bow**
	* Size: Medium
	* Speed 1
	* Ranged Attack (Physical Finesse, Piercing 6)
	* Parry (Physical Power, Fragile)
	* Aim: Grants **Advantage** on next Ranged Attack with this weapon.

### Example Shields

* **Tower Shield**
	* Size: Medium
	* Speed 1
	* Block (Physical Resilience, Max 5)
	* Melee Weapon Attack (Physical Power, Bludgeoning 2)
* **Kite Shield**
	* Size: Medium
	* Speed 1
	* Block (Physical Resilience, Max 3)
	* Melee Weapon Attack (Physical Power, Bludgeoning 2)
* **Round Wooden Shield**
	* Size: Small
	* Speed 1
	* Block (Physical Resilience, Max 2)
	* Melee Weapon Attack (Physical Power, Bludgeoning 1)
* **Buckler**
	* Size: Tiny
	* Speed 3
	* Parry (Physical Power)
	* Block (Physical Resilience, Max 1)
	* Melee Weapon Attack (Physical Power, Bludgeoning 1)

## Example Armor

* **Leather Armor**
	* Light Armor
	* Size: Medium
	* DR 2
* **Chain Mail**
	* Medium Armor
	* Size: Medium
	* DR 4
	* -1 Move Speed
* **Plate Armor**
	* Heavy Armor
	* Size: Medium
	* DR 6
	* -2 Move Speed
