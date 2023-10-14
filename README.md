
# OD&D — 3 Little Brown Books only

And Chainmail for combat rules.

RAW as much as possible. Fix mistakes/inconsistencies.

## Combat

TODO:

* d6 damage
* combat within 3" — however this is an argument for 1" (in book III, under surprise)
    * ah it's melee "range" (from Chainmail, 3") vs melee distance (1") — not sure what difference this actually makes?
    * 1" is definitely "striking distance" and "control"
    * sort of thinking of ignoring the 3" — still need move to get to "touching bases" which is 1"
    * it's like, if you haven't used all your movement, and you're within 3" at melee phase, then you can use your remaining movement to get to 1"...
        * some mention of "no more than half" in CM
        * which is good for defending units — one unit near another can move to help if enemy attacks
* surprise
    * which gives one free round (sort of) plus initiative in next round?
    * 10-30 feet (1-3")
    * free movement
    * it does seem that surprise doesn't give a full _round_ of activities...but it does give a second attack?
    * so you can move + attack, or if you're within 1" attack twice
        * no, it's getting initiative in the next round because it's the attacker
        * Reference: https://odd74.proboards.com/post/260448/thread and https://odd74.proboards.com/post/260448
* no initiative roll
* use weapon class (as per Chainmail, and assign WC to natural weapons)
* move and melee within a round
* only in melee do you determine who strikes first (by "attackers", WC etc.)
* missile and spells occur together
    * actually could have spells go first (ie. artillery phase) — vancian
    * for spell vs spell, it could be by Dex (same with missile vs missile — but easier just to make that simultaneous)
* if combatants don't move, they can take pass through fire
    * otherwise this isn't an option
    * this is the only way to take a 2nd attack
* possible for a movement, take missile fire, then melee because enemy runs into you
* no spell casting or missile in melee

Because Chainmail allows for multiple attacks of ... TODO

TODO simultaneous:

* write/declare actions
* do half move first — check for unordered melee
    * and if there is contact? resolve now or during melee phase? i think later, just that movement then stops
* conduct split moves and missile fire (basically Elves)
* do pass through fire
    * can only be done by missile troops who don't move
    * an extra attack
* TODO how to handle move toward melee and throw spears etc?
    * is this even possible in CM?
    * yes, but they'd have to take only a half move
* spells
* missile
    * RoF = every turn
        * can move up to half and fire once
    * If archers/longbowmen haven't moved (and aren't meleed) they can fire again at end of turn
    * Heavy crossbow is 1 every 2 (1 to load, 1 to fire)
        * can move up to half and do either of these
    * individual targets are selected (so not randomly chosen)
    * pass through
        * must be stationary
        * can make missile attack at half move
        * against anyone moving and within range
* melees
    * any troops with 3" and with spare movement can move into melee
* TODO morale

Turn:

1. first half move
1. second half move
1. spells
1. missile
1. melee

If you read CM, all the rules are there — it's just about adjusting bonuses/penalties for d20. For example:

* impetus bonus for charge (p.17) = +2 to hit
* man-to-man for flank/rear attacks
    * read = +2 to hit, defender can't strike back, lose initiative on next round
    * attacked on defender's left flank = lose initiative on first round
    * attacked on defender's right flank = shield can't be used (?)

Man-to-man, multiple attacks and parry:

* can't parry if weapon 2 or more classes higher than attacker's
* weapon 1 class higher to 3 lower than attacker, defender may parry (-2 to hit for attacker...actually should it be -4?) but can't counter attack
* 4-7 lower, defender can either take first blow or parry (as above)
    * if attacker would've hit (to-hit or to-hit -1 = range of to-hit penalty), defender's weapon is broken
    * if parry is successful, defender can make a counter attack
* 8 or lower, defender:
    * gets first blow
        * doesn't get first blow on charge
    * may parry or strike a second blow — this is only -1 on 2d6
        * same breaking rules — TODO doesn't work with a larger range above, means breaking is less likely...but then, parrying is less likely...
* multiple attacks is also noted — TODO how does this fit in with parrying? (wonder if i should not use them...)
    * 4-7 lower = 2 attacks per round
    * 8 or lower = 3 attacks per round
    * actually it does work with multiple attacks
        * 4-7: D, A, D OR A, Parry (possible counterattack), D
        * 8 or lower: D, D, A, D OR D, A, Parry, D
    * how do these multiple attacks work with multiple attacks against low HD?
        * I don't think it does — from CM, a Hero attacks as 4 troop-type (eg. Heavy Foot), and that got turned into multiple attacks in OD&D.
        * So the rules above really should only be used for fantastic combat, but then you're not going to use it for a lot of combat (eg. wading through orcs).

Absolutely have to use weapon vs AC, even if I redo the values...this is required to make these multiple attack daggers less lethal — just use the values from the Greyhawk supplement.

Another thought — using CM combat rules (including parrying and multiple attacks) for my OD&D+supplements rules (you'd lose initiative dice though). This would offset multiple attacks with both Weapon vs AC _and_ variable damage.

### Attack Matrices

#### Humans Attacking

RAW:

Fighter<br/>Level | Magic-User<br/>Level  | Cleric<br/>Level  | Monster HD  | 2  | 3  | 4  | 5  | 6   | 7   | 8   | 9
--------|-------------|---------|-------------|----|----|----|----|-----|-----|-----|---
1-3     | 1-5         | 1-4     |  up to 1    | 17 | 16 | 15 | 14 | 13  | 12  | 11  | 10
&nbsp;  | &nbsp;      | &nbsp;  |  1+1        | 16 | 15 | 14 | 13 | 12  | 11  | 10  | 9
4-6     | 6-10        | 5-8     |  2 to 3     | 15 | 14 | 13 | 12 | 11  | 10  | 9   | 8
&nbsp;  | &nbsp;      | &nbsp;  |  &nbsp;     | 14 | 13 | 12 | 11 | 10  | 9   | 8   | 7
&nbsp;  | &nbsp;      | &nbsp;  |  3+1 to 4   | 13 | 12 | 11 | 10 | 9   | 8   | 7   | 6
7-9     | 11-15       | 9-12    |  4+1 to 6   | 12 | 11 | 10 | 9  | 8   | 7   | 6   | 5
&nbsp;  | &nbsp;      | &nbsp;  |  6+1 to 8+1 | 11 | 10 | 9  | 8  | 7   | 6   | 5   | 4
10-12   | 16-20       | 13-16   |  &nbsp;     | 10 | 9  | 8  | 7  | 6   | 5   | 4   | 3
&nbsp;  | &nbsp;      | &nbsp;  |  9 to 10+   | 9  | 8  | 7  | 6  | 5   | 4   | 3   | 2
13-15   | 21-25       | 17-20   |  &nbsp;     | 8  | 7  | 6  | 5  | 4   | 3   | 2   | 1
&nbsp;  | &nbsp;      | &nbsp;  |  11+        | 7  | 6  | 5  | 4  | 3   | 2   | 1   | 1


#### Monsters Attacking

Because this is broken use the following:

Monster HD | 2  | 3  | 4  | 5  | 6   | 7   | 8   | 9
-----------|----|----|----|----|-----|-----|-----|---
up to 1    | 17 | 16 | 15 | 14 | 13  | 12  | 11  | 10
1+1        | 16 | 15 | 14 | 13 | 12  | 11  | 10  | 9
2 to 3     | 15 | 14 | 13 | 12 | 11  | 10  | 9   | 8
&nbsp;     | 14 | 13 | 12 | 11 | 10  | 9   | 8   | 7
3+1 to 4   | 13 | 12 | 11 | 10 | 9   | 8   | 7   | 6
4+1 to 6   | 12 | 11 | 10 | 9  | 8   | 7   | 6   | 5
6+1 to 8+1 | 11 | 10 | 9  | 8  | 7   | 6   | 5   | 4
&nbsp;     | 10 | 9  | 8  | 7  | 6   | 5   | 4   | 3
9 to 10+   | 9  | 8  | 7  | 6  | 5   | 4   | 3   | 2
&nbsp;     | 8  | 7  | 6  | 5  | 4   | 3   | 2   | 1
11+        | 7  | 6  | 5  | 4  | 3   | 2   | 1   | 1

# Generate a character

## Abilities

Roll 3d6 for each of the six abilities in order:

* Strength
* Intelligence
* Wisdom
* Constitution
* Dexterity
* Charisma

## Race

Choose a race:

* Human
* Dwarf
* Elf
* Halfling

## Choose a class

Choose a class:

* Fighter
* Magic-User
* Cleric

### Spells

Magic-Users need to determine which spells are in their spellbook.

Clerics can't cast spells until 2nd level, but when they do, they can choose from all available spells.

## Modify abilities

Only prime requisite abilities (Strength for Fighters, Intelligence for Magic-Users and Wisdom for Clerics) may be modified.

In no case may an ability be lowered to less than 9.

Fighters can increase their Strength by 1 point by lowering their Intelligence by 2 points.

Fighters can increase their Strength by 1 point by lowering their Wisdom by 3 points.

Magic-Users can increase their Intelligence by 1 point by lowering their Wisdom by 2 points.

Clerics can increase their Wisdom by 1 point by lowering their Strength by 3 points.

Clerics can increase their Wisdom by 1 point by lowering their Intelligence by 2 points.

## Hit points

Roll for hit points (HP).

## Alignment

There are three alignments: Neutral, Law and Chaos.

## Gold and equipment

Roll 3d6 x 10 for the number of Gold Pieces (GP) you begin with.

Use this money to buy [starting weapons, armour and equipment](#Equipment).

# Abilities

Prime attributes may adjust XP awarded:

Prime Attribute<br/>Score | XP adjustment
---|---
15+   | +10%
13-14 | +5%
7-8   | -10%
6-    | -20%

## Strength

Strength is the prime requisite for Fighters.

## Intelligence

Intelligence is the prime requisite for Magic-Users.

Each character can speak their "common" language.

For each point of Intelligence above 10, a character can speak an additional language.

## Wisdom

Wisdom is the prime requisite for Clerics.

## Constitution

Score | Adjustment
---|---
6-  | -1 HP per HD\*
7   | 40% chance of survival
8   | 50% chance of survival
9   | 60% chance of survival
10  | 70% chance of survival
11  | 80% chance of survival
12  | 90% chance of survival
15+ | +1 HP per HD

\* With a minimum of 1.

## Dexterity

Score | Missile fire to-hit
---|---
8- | -1
13+ | +1

Score | Initiative
---|---
6- | -1
15+ | +1

## Charisma

Score | Maximum<br/>Hirelings | Loyalty Base
---|---|---
3-4 | 1 | -2
5-6 | 2 | -1
7-9 | 3 |
10-12 | 4 |
13-15 | 5 | +1
16-17 | 6 | +2
18 | 12 | +3

### Loyalty

Score | Morale Rating
------|-------------
3-    | Will desert at first opportunity
4-6   | -2 on morale dice
7-8   | -1 on morale dice
9-12  | Average morale dice
13-14 | +1 on morale dice
15-18 | +2 on morale dice
19+   | Morale does not need to be checked

# Races

## Dwarves

Dwarves may only be Fighters up to a maximum of level 6.

They have a high level of magic resistance: add 4 levels when making saving
throws.

They are the only characters that can fully employ the +3 Magic War Hammer.

They detect slanting passages, traps, shifting walls and new constructions when underground.

They can speak Common, Dwarvish, Gnomish, Kobold and Goblin.

## Elves

Elves have both classes: Fighter (maximum 4th level) and Magic-User (maximum 8th level). They choose in which class to progress XP for an adventure.

They use the saving throws and attack matrix for the class in which they are advancing XP.

Track HP for both classes separately and use the highest.

Otherwise they get all abilities of both classes at any time.

They can use any weapons whether adventuring as a Fighter or Magic-User (since all weapons do 1d6 damage anyway).

When adventuring as a Magic-User, they are permitted to wear magical armour.

They can both move and make a missile fire attack in one round.

Elves are better able to detect secret and hidden doors.

They can speak Common, Elvish, Orc, Hobgoblin and Gnoll.

## Halflings

Halflings may only be Fighters up to a maximum of 4th level.

They have a high level of magic resistance: add 4 levels when making saving throws.

# Classes

## Experience points (XP)

XP for a PC is gained for every GP obtained.

The XP is proportioned by the monster level / player level (at a maximum ratio of 1:1).

A PC should not increase more than 1 level per adventure.

## Fighter

Level | Title         | XP      | HP<br/>per level | HP<br/>total
------|---------------|---------|-----------------|--------------
1     | Veteran       | 0       | d6 + 1          | 1d6 + 1
2     | Warrior       | 2000    | d6 + 1          | 2d6 + 2
3     | Swardsman     | 4000    | d6 + 1          | 3d6 + 3
4     | Hero          | 8000    | d6 + 1          | 4d6 + 4
5     | Swashbuckler  | 16000   | d6 + 1          | 5d6 + 5
6     | Myrmidon      | 32000   | d6 + 1          | 6d6 + 6
7     | Champion      | 64000   | d6 + 1          | 7d6 + 7
8     | Super Hero    | 120000  | d6 + 1          | 8d6 + 8
9\*   | Lord          | 240000  | d6 + 1          | 9d6 + 9
10    | Lord          | 480000  |                 |
11    | Lord          | 720000  | d6              | 10d6 + 9
12    | Lord          | 960000  |                 |
13    | Lord          | 1200000 | d6              | 11d6 + 9
14    | Lord          | 1440000 |                 |
15    | Lord          | 1680000 | d6              | 12d6 + 9

\* Name level.

## Magic-User

Level | Title         | XP      | HP<br/>per level | HP<br/>total
------|---------------|---------|-----------------|--------------
1     | Medium        | 0       | d6              | 1d6
2     | Seer          | 2500    | + 1             | 1d6 + 1
3     | Conjurer      | 5000    | d6              | 2d6 + 1
4     | Theurgist     | 10000   | + 1             | 2d6 + 2
5     | Thaumaturgist | 20000   | d6              | 3d6 + 2
6     | Magician      | 35000   | + 1             | 3d6 + 3
7     | Enchanter     | 50000   | d6              | 4d6 + 3
8     | Warlock       | 75000   | + 1             | 4d6 + 4
9     | Sorcerer      | 100000  | d6              | 5d6 + 4
10    | Necromancer   | 200000  | + 1             | 5d6 + 5
11\*  | Wizard        | 300000  | d6              | 6d6 + 5
12    | Wizard        | 600000  |                 |
13    | Wizard        | 900000  |                 |
14    | Wizard        | 1200000 | d6              | 7d6 + 5
15    | Wizard        | 1500000 |                 |
18    | Wizard        | 1800000 |                 |
19    | Wizard        | 2100000 | d6              | 8d6 + 5
20    | Wizard        | 2400000 |                 |
21    | Wizard        | 2700000 |                 |
22    | Wizard        | 3000000 | d6              | 9d6 + 5


\* Name level.

Level | 1  | 2  | 3  | 4  | 5  | 6
------|----|----|----|----|----|----
1     | 1  |    |    |    |    |
2     | 2  |    |    |    |    |
3     | 3  | 1  |    |    |    |
4     | 4  | 2  |    |    |    |
5     | 4  | 2  | 1  |    |    |
6     | 4  | 2  | 2  |    |    |
7     | 4  | 3  | 2  | 1  |    |
8     | 4  | 3  | 3  | 2  |    |
9     | 4  | 3  | 3  | 2  | 1  |
10    | 4  | 4  | 3  | 3  | 2  |
11    | 4  | 4  | 4  | 3  | 3  |
12    | 4  | 4  | 4  | 4  | 4  | 1
13    | 5  | 5  | 5  | 4  | 4  | 2
14    | 5  | 5  | 5  | 4  | 4  | 3
15    | 5  | 5  | 5  | 4  | 4  | 4
16    | 5  | 5  | 5  | 5  | 5  | 5
17    | 6  | 6  | 6  | 5  | 5  | 5
18    | 6  | 6  | 6  | 6  | 6  | 6

## Cleric

Level | Title         | XP      | HP<br/>per level | HP<br/>total
------|---------------|---------|------------------|-------------
1     | Acolyte       | 0       | d6      | 1d6
2     | Adept         | 1500    | d6      | 2d6
3     | Priest        | 3000    | d6      | 3d6
4     | Vicar         | 6000    | d6      | 4d6
5     | Curate        | 12000   | d6      | 5d6
6     | Bishop        | 25000   | d6      | 6d6
7     | Lama          | 50000   | d6      | 7d6
8\*   | Patriarch     | 100000  | d6      | 8d6
9     | Patriarch     | 300000  |         |
10    | Patriarch     | 500000  |         |
11    | Patriarch     | 700000  | d6      | 9d6
12    | Patriarch     | 900000  |         |
13    | Patriarch     | 1100000 |         |
14    | Patriarch     | 1300000 | d6      | 10d6
15    | Patriarch     | 1500000 |         |
16    | Patriarch     | 1700000 |         |
17    | Patriarch     | 1900000 | d6      | 11d6

\* Name level.

Level | 1  | 2  | 3  | 4  | 5
------|----|----|----|----|---
1     |    |    |    |    |
2     | 1  |    |    |    |
3     | 2  |    |    |    |
4     | 2  | 1  |    |    |
5     | 2  | 2  |    |    |
6     | 2  | 2  | 1  | 1  |
7     | 2  | 2  | 2  | 1  | 1
8     | 2  | 2  | 2  | 2  | 2
9     | 3  | 3  | 3  | 2  | 2
10    | 3  | 3  | 3  | 3  | 3
11    | 4  | 4  | 4  | 3  | 3
12    | 5  | 5  | 5  | 4  | 4

## XP and name levels

To increase beyond name level, XP required equals that to get to name level.

The exception is Clerics — each level after name level requires 200k XP.

# References

* https://gelatinouscubism.wordpress.com/2022/06/05/using-chainmail-with-odd/
* http://deltasdnd.blogspot.com/2010/09/surprise.html
* https://www.geekeratimedia.com/2019/12/initiative-in-od-remember-when-d-combat.html
* https://www.donjonlands.com/2021/07/chainmail-odd-and-the-one-minute-combat-round.html
* https://forums.somethingawful.com/showthread.php?threadid=3858338
