---
title: Wall of Fire
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 285
tags:
  - DnD/Spells/Evocation
  - DnD/Spells/Lv4
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Druid

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 285

# Wall of Fire
- ![[wall-of-fire.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 1 minute
    - **Range:** 120 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]
    - [[Sorcerer]]
    - [[Druid]]

- **Info:**
    - **Level:** 4th
    - **School:** Evocation
- **Components:**
    - VSM
    - A small piece of phosphorus

## Description:
You create a wall of fire on a solid surface within range. You can make the wall up to 60 feet long, 20 feet high, and 1 foot thick, or a ringed wall up to 20 feet in diameter, 20 feet high, and 1 foot thick. The wall is opaque and lasts for the duration.

When the wall appears, each creature within its area must make a Dexterity saving throw. On a failed save, a creature takes 5d8 fire damage, or half as much damage on a successful save.

One side of the wall, selected by you when you cast this spell, deals 5d8 fire damage to each creature that ends its turn within 10 feet of that side or inside the wall. A creature takes the same damage when it enters the wall for the first time on a turn or ends its turn there. The other side of the wall deals no damage.

## At Higher Levels:
When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d8 for each slot level above 4th.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Wall of Fire"
> image: [[wall-of-fire.png]]
> level: "4th"
> school: "Evocation"
> class: "Wizard,Sorcerer,Druid"
> duration: "Concentration, up to 1 minute"
> ritual: "No"
> casting_time: "1 action"
> range: "120 feet"
>
> components: VSM
> comp_m: "a small piece of phosphorus"
>
> description: "You create a wall of fire on a solid surface within range. You can make the wall up to 60 feet long, 20 feet high, and 1 foot thick, or a ringed wall up to 20 feet in diameter, 20 feet high, and 1 foot thick. The wall is opaque and lasts for the duration.\n\nWhen the wall appears, each creature within its area must make a Dexterity saving throw. On a failed save, a creature takes 5d8 fire damage, or half as much damage on a successful save.\n\nOne side of the wall, selected by you when you cast this spell, deals 5d8 fire damage to each creature that ends its turn within 10 feet of that side or inside the wall. A creature takes the same damage when it enters the wall for the first time on a turn or ends its turn there. The other side of the wall deals no damage."
> higher_level: "When you cast this spell using a spell slot of 5th level or higher, the damage increases by 1d8 for each slot level above 4th."
> ```
