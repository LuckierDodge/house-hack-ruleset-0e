# Combat

## Phases of Combat

Combat is divided into 4 distinct phases, which repeat until the action is resolved. They are the following:

* **Positioning**: during this phase, every character has the opportunity to move up to their speed.
* **Uncontested Actions**: during this phase, every character can make actions that don't impact the opposing team (e.g. heals, buffs, teleportation, recovery, etc.). If an action is taken during this phase that _leads to_ a contested action (e.g. you teleport a boulder above the enemies head or provoke an attack of opportunity), then the action is resolved during the next phase.
* **Contested Actions**: this is where attacks, harmful spells, grapples, and other actions that involve two opposing actors are resolved.
* **Contingent Actions**: this final phase is used to resolve certain special actions, such as those intended to resolve upon completion of other actions in earlier phases (e.g. "I want to move back behind cover after attacking")

## Stamina and Actions

By default, a Character can take one action in each of the 4 phases of combat. A character also has the option to burn Stamina to gain additional actions during a phase. For instance, a character might decide to use Stamina to gain extra movement during the _Positioning_ phase, or to make a second attack during the _Contested Actions_ phase.

The amount of stamina a character has available depends on their ?Fortitude? characteristic, and they can regain Stamina by taking the _Recover_ action during the _Uncontested Actions_ phase.

## Initiative

Initiative is rolled at the start of each round of combat, and determines which side acts first during each phase of combat. _House Hack_ uses Side Initiative, where every character on a "side" acts simultaneously.

To resolve initiative, have each side roll 1d20 and add the highest of any modifiers granted to that side by Talents or Traits. The side with the highest result (rerolling for ties) goes first for that round. Upon completion of the round, initiative is rolled again.

### Alternative: Trading Initiative

In this version, Initiative only matters for the first round. Subsequent rounds switch order.

For example, given two teams, T1 and T2, with T1 rolling higher initiative:

#### Round 1

* Positioning Phase: T1, T2
* Uncontested Action Phase: T2, T1
* Contested Action Phase: T1, T2
* Contingent Action Phase: T2, T1

#### Round 2

Same as Above, but switch T1 and T2.

### Handling Race Conditions

Sometimes, two members of the same party might try to race each other during their side's initiative. To resolve this, simply have anyone involved rolled individual initiative. In this case, individual's initiative modifiers are applied to their own initiative rolls.

## Attack and Defense

???

Some notion of "Each attacker rolls some dice determined by their characteristics/weapons/abilities etc., and the target rolls a save to reduce the damage".

## Damage Resistance

Armor, Wards, and certain Talents and Traits can grant Damage Resistance (DR).

Whenever you are hit by a damaging effect and don't reduce the damage to 0 with Saves, you can reduce the amount of the damage by the amount of DR you have of the same type.

If the damage received is in excess of your DR, you take the difference as damage.

At the end of the _Contested Rolls_ phase, reduce your DR by 1 for each attack that you negated damage from using DR (to a minimum of 0). This represents the degrading of your protection under repeated assault.
