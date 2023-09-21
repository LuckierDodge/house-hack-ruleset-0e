# Combat

During Combat, each character can take 2 Actions and 1 Maneuver on their turn every round.

## Initiative

Each side involved in a combat rolls a d20, rerolling on ties. If either side has bonuses to their groups Initiative, they can add those to the roll. The Initiative then proceeds in order from highest to lowest, with each side having the opportunity to act.

Each time a side takes the Initiative, each of its members can take their actions in whatever order they deem appropriate (including interleaving actions).

## Maneuvers

### Move

Every player has a default speed, measured in squares (each square corresponds to about 1.5 meters). Most PCs have a default Move Speed of 4. They can spend an action to **Move**, moving up to their speed.

### Reposition

When **Engaged**, a character **Moving** may provoke Attacks of Opportunity. **Repositioning** allows a character to move 1 square in any direction without provoking Attacks of Opportunity.

### Stand

A character who is **Prone** can stand up as a **Maneuver**.

## Health and Morale

* You have **Morale** equal to 5 + **Mental Resilience** times your Level.
* You have **Health** equal to 5 + **Physical Resilience**.
* Unless specified otherwise, damage is first applied to your Morale. Damage that reduces your Morale to 0 does not roll over to Health, and Morale can't be negative.
* If your Morale is at 0, you suffer a **Disadvantage** on all checks, and future damage is applied to Health.
* If your Health is at 0, you are **Unconscious**. If you reach negative Health equal to your maximum Health, you are dead.

## Weapon Attacks

* To attack with a weapon, you roll a **Weapon Attack** to determine the **Threat**, and compare it to the target's **Defense**. If your **Threat** exceeds their **Defense**, they take the difference as damage.
* You can usually only make one Weapon Attack with any given weapon in a turn.

`Threat = Characteristic Die + Proficiency Die`

### Aim

If wielding a ranged or thrown weapon, like a Bow or Javelin, you can choose to take the Aim action, targeting a creature or object. This grants an **Advantage** with all attacks you make with that weapon equal to your **Physical Finesse**. This effect requires Concentration, and lasts until you lose sight of the target. Attacking the target with the Aimed weapon does not break Concentration.

### Unarmed Attacks

If you have a free limb, you can make a **Physical Power**-based **Weapon Attack** against a target of your choice. This attack does Bludgeoning by default.

## Defense

Whenever under **Threat**, roll a **Defense** Test. **Defense** Tests are **Characteristic** Tests, with the type of **Characteristic** determined by the attack and how you choose to defend.

* The chosen defense has to make sense. You can't block a Sword with Social Resilience.
* Physical Attacks are typically dodged with **Physical Finesse** or parried with **Physical Power**.
* Poisons can be resisted with **Physical Resilience**.

## Armor

* Armor grants a Defense Minimum. If you roll under the Defense Minimum for your armor, you use that as your Defense Value instead.
* Armor also comes with a Bulk value and a Movement Penalty. More protective Armor tends to be more Encumbering. Proficiency with a class of armor reduces the movement penalty by 1. Proficiency with Armor also allows you to reduce the Bulk value when worn by 2.

## Stamina

Every Player Character, and many Non-Player Characters, have a certain amount of a resource called **Stamina**. This is a resource that regenerates between fights, and can be spent in a variety of ways during combat:

* Certain Talents and Traits grant abilities that require **Stamina** to use.
* **Stamina** can be spent to gain a **Surge**. A **Surge** allows for a character to gain an extra action. Only one **Surge** can be used per round, and a **Surge** can be declared at any time. If a **Surge** is declared, it is resolved immediately after the current action.
* You can recover 1 **Stamina** by taking the **Recover** action. You can take this action once per round (you cannot take this action and use a **Surge** in the same round).
* If you reach 0 **Stamina**, roll Physical Resilience. On a minimum roll, you gain +1 **Exhaustion**.

## Conditions

* **dX Burning**
	* A **Burning** creature or object takes Fire Damage vs. **Physical Resilience** (bypassing Armor and Defenses). For example _d6 Burning_ would deal 1d6 Fire damage - the creature/objects **Physical Resilience**. Unless actively exposed to a continual source of **Burning**, like a fire, hot magma, or molten metal, the condition is **Diminishing** and can additionally be reduced by 1 step for each action spent extinguishing it.
* **Encumbered**
	* One Disadvantage to Physical Power and Finesse Characteristics per level (this does not affect Bulk Capacity calculations), and reduce movement speed by 1
	* +1 **Exhaustion** for each 4 hours spent carrying the extra bulk per level
	* Add 25% to overland travel times.
* **Exhaustion**
	* Reduces Stamina Reserves by 1 for each level
	* Applies a **Disadvantage** to Physical Tests per level.

## Condition Properties

* **Diminish**
	* A Condition or Effect with the **Diminish** property has its level reduced by one step each time its effect is evaluated. So, for instance, **Diminishing** _d6 Burning_ would be reduced to _d4 Burning_ after the damage is evaluated at the start of the **Burning** creature or object's turn.
* **Intensify**
	* A Condition or Effect with the **Intensify** property has its level increased by one step each time its effect is evaluated. So, for instance, **Intensifying** _d6 Necrosis_ increases to _d8 Necrosis_ after the damage is evaluated at the start of the _Necrotizing_ creature's turn.

## Examples

| Weapon     | Size   | Reach/Range | Melee Attack             | Ranged Attack                  | Bulk | Properties           |
| ---------- | ------ | ----------- | ------------------------ | ------------------------------ | ---- | -------------------- |
| Zweihander | Medium | 1sq/1sq     | Piercing/Slashing        | Piercing/Slashing (Improvised) | 4    | Parry                |
| Longsword  | Medium | 1sq/2sq     | Piercing/Slashing        | Piercing/Slashing (Improvised) | 3    | Parry                |
| Shortsword | Small  | 1sq/3sq     | Piercing/Slashing        | Piercing/Slashing (Improvised) | 2    | Parry                |
| Dagger     | Tiny   | 1sq/4sq     | Piercing/Slashing        | Piercing/Slashing              | 1    | Thrown Weapon, Parry |
| Cross Bow  | Medium | 1sq/10sq    | Bludgeoning (Improvised) | Piercing                       | 3    | Fragile              |
| Long Bow   | Medium | 1sq/10sq    | Bludgeoning (Improvised) | Piercing                       | 3    | Fragile              |
| Short Bow  | Small  | 1sq/6sq     | Bludgeoning (Improvised) | Piercing                       | 2    | Fragile              |
| Slingshot  | Tiny   | 1sq/6sq     | Bludgeoning (Improvised) | Bludgeoning                    | 1    | Fragile              |

| Shield              | Size   | Defense Minimum | Melee Attack             | Bulk | Properties |
| ------------------- | ------ | --------------- | ------------------------ | ---- | ---------- |
| Tower Shield        | Medium | 5 Physical      | Bludgeoning (Improvised) | 4    |            |
| Kite Shield         | Medium | 4 Physical      | Bludgeoning (Improvised) | 3    |            |
| Round Wooden Shield | Small  | 3 Physical      | Bludgeoning (Improvised) | 2    |            |
| Buckler             | Tiny   | 2 Physical      | Bludgeoning (Improvised) | 1    | Parry      |

| Armor       | Class  | Size   | Defense Minimum | Movement Penalty | Bulk | Properties |
| ----------- | ------ | ------ | --------------- | ---------------- | ---- | ---------- |
| Clothing    | -      | Medium | -               | -                | 0    |            |
| Leather     | Light  | Medium | 2               | -                | 1    |            |
| Chain Mail  | Medium | Medium | 3               | 1                | 2    | Metallic   |
| Plate Armor | Heavy  | Medium | 5               | 2                | 4    | Metallic   |
