# d20 Hack

* Roll d20 + Mods

| Roll                    | Degree of Success |
| ----------------------- | ----------------- |
| 10 or more below Target | Critical Failure  |
| 1 to 9 below Target     | Failure           |
| 0 to 9 above Target     | Success           |
| 10 or more above Target | Critical Success  |

* Rolling a 1 on a d20 decreases the degree of success by 1.
* Rolling a 20 on a d20 increases the degree of success by 1.
* Qualified Success: when a roll is a Failure but not a Critical Failure, the GM can offer a Qualified Success, allowing the character to at least partially succeed, but typically at the cost of some complication or cost. If they decline, the normal conditions of a Failure occur.

## Characteristics

* Strength: running, jumping, climbing, lifting, swimming, melee weapons
* Finesse: sleight of hand, lock picking, tools, stealth, finesse melee weapons, ranged weapons
* Agility: acrobatics, reflex defense
* Constitution: endurance, fortitude defense, durability
* Wits: knowledge checks, initiative, spell casting
* Will: will defense, durability, spell casting
* Intuition: perception, spell casting, initiative, insight
* Charisma: persuasion, intimidation, deception, performance

### Assignment

There are 3 ways to determine your Characteristics:

1. All your Characteristic Values start at 0.
2. Roll a d4. You can add the result to any one Characteristic, but must subtract the result from another Characteristic in turn. You can (but do not have to) do this until all values are assigned, without assigning to any Characteristic multiple times.
2. Roll 1d8-4 in order.

### Increasing Your Characteristics

Whenever you level up, you choose one Characteristic to increase by 1.

### Defenses

* Each Characteristic has a corresponding Defense value, equal to the Characteristic Value plus 10
* Defenses: 10 + Characteristic

## Damage

### Damage Type

* Physical
	* Cutting
	* Piercing
	* Striking
	* Crushing
* Energy
	* Fire
	* Frost
	* Lightning
	* Thunder
	* Positive
	* Negative
* Blight
	* Toxin
	* Disease
	* Acid
* Supernatural
	* Psionic
	* Necrotic
	* Holy
	* Unholy

### Durability

* Hit Dice: 1d8 per level
* Durability: 8 + CON + WILL + Toughness Skill (minimum 1)
* For every level after first, roll one Hit Die and gain that much Durability

## Skills

* Having Skill Ranks in a Skill grants a bonus to rolls related to that skill. At the end of each session, you can increase your Rank in a Skill used during that session by 1. You can't increase any single skill above your Player Level.
* You start the game with a number of Skill Ranks equal to 5 + Wits (minimum 1).
* Magic and Psionics have 2 relevant Skill Ranks for each check: your overall Spellcasting or Psionics skill, respectively, and a skill for the specific magic or power being harnessed (Fire, Illusions, Telepathy, Charms, etc). You must have at least one skill rank in a type of magic or power to cast that magic.
* Similarly, Weapons have 2 relevant Skill Ranks for each check: a general Melee or Ranged Skill, and a specific Weapon Skill.

### Magic and Psionics

* Casting any spell or using a Psionic ability requires a successful DC10 spellcasting/psionics check, which is also compared to the relevant defense of any targeted character or object.
* On a Critical Failure, you suffer a Magical/Psionic Catastrophe determined by the GM.
* Damaging spells and powers have a Damage Pool, which is divided up evenly when there are multiple targets
	* Damage Pool: Damage Di(c)e + Characteristic (typically Wits, Will, Intuition, or Constitution) + Spellcasting/Psionic Skill Rank + Magic/Power Type Skill Rank
* For instance, to use Psionic Telekinesis to hit someone with a rock
	* Roll d20 + Will + Psionics Skill + Telekinesis Skill
	* If it hits, deal damage equal to 1d(Damage Die) + Will + Psionics Skill + Telekinesis Skill
* Spellcasting/psionics tests have a DC determined by the GM. For simple tasks where failure isn't a risk (e.g. lighting a candle in your hand), the GM shouldn't call for a roll.

| Spell Attacks     | DC               |
| ----------------- | ---------------- |
| Base              | 10               |
| Additional Target | +5               |
| Add Damage Die    | +2               |
| Sphere            | +2 * Radius      |
| Line              | +1 per Cell      |
| Cone              | +2 * Length      |
| Cube              | +2 * Side Length |

| Spellcasting/Psionics Skill Rank | Damage Die |
| -------------------------------- | ---------- |
| 1-2                              | 1d4        |
| 3-5                              | 1d6        |
| 5-8                              | 1d8        |
| 8-10                             | 1d12       |

## Armor

* Armor provides Resistance against any attack that doesn't explicitly bypass it, at the cost of reduced Agility, Speed, Finesse, and Awareness.
	* More protective armor grants greater Resistances, but also larger penalties.
* The result is that characters with Heavy Armor are less maneuverable and easier to hit, but will take less (and sometimes no) damage from certain attacks that do land.
* Shields provide varying degrees of Cover, increasing the wielder's Agility Defense at the cost of Finesse.

| Armor          | Resistance | Penalties              |
| -------------- | ---------- | ---------------------- |
| Light          | 1-2        |                        |
| Medium         | 3-4        | -1 Agility, -1 Finesse |
| Heavy          | 5-6        | -2 Agility, -2 Finesse |
| Helmet         | +1         | -1 Awareness           |
| Visored Helmet | +2         | -2 Awareness           |

## Weapons

* Attack: d20 + Strength/Finesse + Melee/Ranged Skill Rank + Weapon Specialization Skill Rank
* Defense: 10 + Agility + Dodge/Parry Skill Rank
* Critical Hit: Bypass Resistance
* Two Handing: Double your Strength/Finesse

### Damage

* Weapon Damage + Strength or Finesse + Skill Rank - Resistance
* Weapon Damage
	* Unarmed: 1
	* Light Weapons: d4
	* Medium Weapons: d6
	* Heavy Weapons: d8

## Action Economy

* Every Character has 1 Action
* An Action can be used to attack, cast a spell, pull something from a pack, or any other activity that could be reasonably completed in a short period of time (5-10 seconds)
* Characters can also **Multitask**, doing 2 actions at once (attacking two different targets, sheathing a weapon and then drawing and attacking with another), but have disadvantage on any of the actions that involve rolling.
* Characters can also move up to their speed. If they take no other actions, they can move twice their speed.

## Initiative

Each character acts in order of Agility Defense. Ties are broken by opposing d20 roll.
