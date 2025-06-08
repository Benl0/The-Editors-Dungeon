---
title: Confusion
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 224
tags:
  - DnD/Spells/Enchantment
  - DnD/Spells/Lv4
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Druid
  - DnD/Spells/Class/Bard

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 224

# Confusion
- ![[confusion.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 1 minute
    - **Range:** 90 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]
    - [[Sorcerer]]
    - [[Druid]]
    - [[Bard]]

- **Info:**
    - **Level:** 4th
    - **School:** Enchantment
- **Components:**
    - VSM
    - Three nut shells

## Description:
This spell assaults and twists creatures' minds, spawning delusions and provoking uncontrolled action. Each creature in a 10-foot radius sphere centered on a point you choose within range must succeed on a Wisdom saving throw when you cast this spell or by affected by it.

An affected target can't take reactions and must roll a d10 at the start of each of its turns to determine its behaviour for that turn.

| d10  | Behaviour                                                                                                                                                                                       |
| :--: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1   | The creature uses all its movement to move in a random direction. To determine the direction, roll a d8 and assign a direction to each die face. The creature doesn't take an action this turn. |
| 2-6  | The creature doesn't move or take actions this turn.                                                                                                                                            |
| 7-8  | The creature uses its action to make a melee attack against a randomly determined creature within its reach. If there is no creature within its reach, the creature does nothing this turn.     |
| 9-10 | The creature can act and move normally.                                                                                                                                                         |

At the end of each of its turns, an affected target can make a Wisdom saving throw. If it succeeds, this effect ends for that target

## At Higher Levels:
When you cast this spell using a spell slot of 5th level or higher, the radius of the sphere increases by 5 feet for each spell slot above 4th.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Confusion"
> image: [[confusion.png]]
> level: "4th"
> school: "Enchantment"
> class: "Wizard,Sorcerer,Druid,Bard"
> duration: "Concentration, up to 1 minute"
> ritual: "No"
> casting_time: "1 action"
> range: "90 feet"
>
> components: VSM
> comp_m: "three nut shells"
>
> description: "This spell assaults and twists creatures' minds, spawning delusions and provoking uncontrolled action. Each creature in a 10-foot radius sphere centered on a point you choose within range must succeed on a Wisdom saving throw when you cast this spell or by affected by it.\n\nAn affected target can't take reactions and must roll a d10 at the start of each of its turns to determine its behaviour for that turn.\n\n - **1**: The creature uses all its movement to move in a random direction. To determine the direction, roll a d8 and assign a direction to each die face. The creature doesn't take an action this turn.\n\n- **2-6**: The creature doesn't move or take actions this turn.\n\n- **7-8**: The creature uses its action to make a melee attack against a randomly determined creature within its reach. If there is no creature within its reach, the creature does nothing this turn.\n\n- **9-10**: The creature can act and move normally.\n\nAt the end of each of its turns, an affected target can make a Wisdom saving throw. If it succeeds, this effect ends for that target"
> higher_level: "When you cast this spell using a spell slot of 5th level or higher, the radius of the sphere increases by 5 feet for each spell slot above 4th."
> ```
