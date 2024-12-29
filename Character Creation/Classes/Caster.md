# Caster

## First Level

* Hit Die: 1d4
* Skills: Gain 1 Supernatural Skill Rank
* Class Talent: Supernatural Power
	* You have access to supernatural powers: arcane sorcery, divine Favor, psionic manifestation, or something otherwise beyond the capability of mere mortals.
	* This is a repeatable talent. Each time you take this talent, select a subclass from the list below.

## Subsequent Levels

* Gain 1 Supernatural Skill Rank
* Gain 1 Talent from a Caster Talent Tree

## Subclasses

### Mage

_Years of careful study have allowed you to sense and harness the latent magic of the Aether that infuses the unseen world._

* Prereq: Wits >= 1
* Skill: You gain a rank in Arcane Magic.
* Your casting Characteristic is Wits
* Fuel: Aether
* Aether Capacity: Arcane Magic Rank + Wits
* Power Type: Arcane
* You can regain 1 * Mage Level of Aether per Rest.

#### Aether Drain

_Your own Aether reserves can be supplemented with the innate magic of powerful artifacts_

* Prereq: Caster (Mage) Level >= 2
* As an action, you absorb the magic imbued in a magical item. You regain Aether equal to the level of the item, an the item loses it's magical properties. If this would put you above your Aether Capacity, you can immediately use the excess to cast a Spell, otherwise it is lost.
* You can't use this talent on items that are higher level than your Caster level

### Chosen

_You have been touched by Divinity itself, selected for a higher purpose. Your patron Deity rewards your piety and with miracles, but expects devotion and service in turn._

* Prereq: Will >= 1
* Skill: You gain a rank in Miracleworking.
* Your casting Characteristic is Will
* Fuel: Faith
* Faith Capacity: Miracleworking Rank + Will
* Power Type: Divine
* You regain 1 * Chosen Level Faith per Rest in a holy place, if you engage in prayer and meditation.
* Your GM can restore Faith when you complete Worthy Acts of Piety, especially when such acts involve personal sacrifice.
* Choose a Deity that you are a servant of:
	* TODO

### Inheritor

_You were born with magic in your blood. It is a powerful wellspring, but beware drawing too deeply._

* Prereq: Vigor >= 1
* Skill: You gain a rank in the Bloodline Magic Skill
* Your casting Characteristic is Vigor
* Fuel: Stamina
* Stamina Capacity: Increase your Stamina capacity by your Bloodline Magic Rank
* Choose an Ancestral Source:

| d20   | Ancestral Source   | Power Type |
| ----- | ------------------ | ---------- |
| 1-6   | Celestial          | Divine     |
| 7-12  | Dragon, Elemental  | Elemental  |
| 13-16 | Fae, Nature Spirit | Nature     |
| 17-20 | Fiend, Abomination | Wyrd       |

### Pactbound

_You are bound by a pact with a powerful entity. You pledge service in exchange for power beyond the grasp of mere mortals._

* Prereq: Wits >= 1
* Skill: You gain a rank in Pact Magic
* Your casting Characteristic is Wits
* Fuel: Favor
* Favor Capacity: Pact Magic + Wits
* Power Type: Wyrd
* Favor is regained (or removed) according to the terms of the Pact.

TODO: Add guidance for creating pacts

## Caster Talent Trees

### Pyromancer

A specialist in creating and shaping flame.

* Prereq: Power Type (Arcane/Elemental/Wyrd)
* Gain Pyromancy Rank 1

#### Ignite

* Range: Touch
* As an action, ignite a flammable object (such as a torch or clump of straw), or temporarily cover a small area with flames. Size of the object/area ignited is proportional to the amount of Fuel invested, starting with Small at 1 Fuel and increasing by 1 category for each Fuel thereafter. The flames continue until extinguished or they run out of things to burn.
* Deal Magic Damage (Fire) to anyone or anything touching the flames; they also take 1 Ongoing Fire Damage (Vigor Test or taking an action to extinguish ends). Characters can attempt to Dodge to avoid damage.

#### Control Flames

_Some fear the unpredictable nature of the flame, but you have learned to guide it._

* Casting Test
* Range: Pyromancy Rank
* You can manipulate an extant flame, growing, shrinking, or shaping it as you desire.
* As an action, you can increase or decrease it's Size by a number of units equal to your Pyromancy Rank, move the flame a number of units equal to your Pyromancy Rank, or create any shape or image you desire (though the image is clearly identifiable by an observer as made of flame)

#### Fireball

_Some problems are best solved by indiscriminate immolation._

* Casting Test
* Prereq: Ignite
* Range: 5 + Pyromancy Rank
* You can hurl a ball of magical fire that explodes on contact, creating a sphere of fiery destruction wherever it strikes
* Area Casting Attack, 2+ Fuel: Deal Magic Damage (Fire) to any targets caught in a sphere of size proportional to 1d4 + Fuel invested (Medium at 2, increasing by 1 with each additional Fuel). Characters can attempt to Dodge to avoid damage.

### Vitamancer

_Using supernatural powers to heal, cure, and nurture._

* Casting Test
* Prereq: Power Type (Divine/Nature)
* Gain Vitamancy Rank 1

#### Preserve Life

_Death will claim us all, but not this day. Not on your watch._

* Casting Test
* Range: Touch
* Concentration
* Spend 1 Fuel as an action to preserve the life of a creature on Death's Door for 1 day. For the duration, the target gains DR equal to your Vitamancy Rank and can't be killed by any disease, toxin, ongoing condition, curse, or other effect of a level less than or equal to your Vitamancy Rank.
* You can Preserve the lives of a number of targets equal to your Vitamancy Rank
* The effect ends after one day or if the target ever leaves Death's Door.

#### Healing Touch

_Channel the natural healing of the body, binding wounds in seconds that would normally take hours or days._

* Casting Test
* Prereq: Preserve Life
* Range: Touch
* Spend 1+ Fuel as an action to allow a target to expend the same number of Reserves to increase their HP, up to their current maximum.
* Spend 2 Fuel and an hour to cure a Disease or Toxin of a level equal to or lower than your Vitamancy Rank

#### Infuse Life

_Channel vital energy into a creature, temporarily imbuing them with supernatural health_

* Casting Test
* Prereq: Preserve Life
* Range: Touch
* Duration: 1 day
* Spend 1+ Fuel to increase a target's current and maximum HP by your Vitamancy Rank multiplied by the fuel invested. The effect ends after 1 day or when the target Rests.
