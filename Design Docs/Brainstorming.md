# Brainstorming

## Ryan's Design Goals

1. Easy to hack: can easily create new character features/monsters/items/systems with some level of confidence that you won't completely break your game.
2. Mechanical Depth and Tactical Combat, but keep it streamlined. No 3 page grappling rules
3. Emphasis on Party Teamwork
4. Easy Action Resolution: make it easy for the GM to adjudicate action resolution without having to rely too heavily on referencing the rules.
5. Talent Trees!

## Matt's Design Goals

1. Emphasis on Party Teamwork
2. Worldbuilding: mechanics can be setting-agnostic, but I would love a fun, unique default setting

## Ideas to Explore

* Talent Trees
* Class System vs. Point Buy vs. Hybrid
* Group Character Sheets/Group Maneuvers (see _Kingdoms and Warfare_)
	* Build-a-Combo, Talents that provide combo ingredients
* Lifepath Char Creation
* Build-a-Spell

## AnyDice Formula

[Link](https://anydice.com/program/2edef)

```
ATTACK_DICE: 2d6
DEFENSE_DICE: 1d6
ATTACK_BONUS: 2
DEFENSE_BONUS: 0
DR: 1
DICE_RESULT: [highest of ([highest 1 of ATTACK_DICE] + ATTACK_BONUS - [highest 1 of DEFENSE_DICE] - DEFENSE_BONUS) and 0]
function: minimumdamage NUMBER:n{
 if NUMBER = 0 { result: 0 }
 result: [highest of NUMBER - DR and 1]
}
output [minimumdamage DICE_RESULT]
```
