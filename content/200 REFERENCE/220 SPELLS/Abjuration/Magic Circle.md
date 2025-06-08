---
title: Magic Circle
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 256
tags:
  - DnD/Spells/Abjuration
  - DnD/Spells/Lv3
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Warlock
  - DnD/Spells/Class/Paladin
  - DnD/Spells/Class/Cleric

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 256

# Magic Circle
- ![[magic-circle.png]]
- **Casting:**
    - **Casting Time:** 1 minute
    - **Duration:** 1 hour
    - **Range:** 10 feet
    - **Ritual:** No
    - **Concentration:** No
- **Classes:**
    - [[Wizard]]
    - [[Warlock]]
    - [[Paladin]]
    - [[Cleric]]

- **Info:**
    - **Level:** 3rd
    - **School:** Abjuration
- **Components:**
    - VSMgp
    - Holy water or powdered silver and iron worth at least 100 gp, which the spell consumes

## Description:
You create a 10-foot-radius, 20-foot-tall cylinder of magical energy centered on a point on the ground that you can see within range. Glowing runes appear wherever the cylinder intersects with the floor or other surface.

1. The creature can't willingly enter the cylinder by nonmagical means. If the creature tries to use teleportation or interplanar travel to do so, it must first succeed on a Charisma saving throw.
2. The creature has disadvantage on attack rolls against targets within the cylinder.
3. Targets within the cylinder can't be charmed, frightened, or possessed by the creature.

When you cast this spell, you can elect to cause its magic to operate in the reverse direction, preventing a creature of the specified type from leaving the cylinder and protecting targets outside it.

## At Higher Levels:
When you cast this spell using a spell slot of 4th level or higher, the duration increases by 1 hour for each slot level above 3rd.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Magic Circle"
> image: [[magic-circle.png]]
> level: "3rd"
> school: "Abjuration"
> class: "Wizard,Warlock,Paladin,Cleric"
> duration: "1 hour"
> ritual: "No"
> casting_time: "1 minute"
> range: "10 feet"
>
> components: VSMgp
> comp_m: "holy water or powdered silver and iron worth at least 100 gp, which the spell consumes"
>
> description: "You create a 10-foot-radius, 20-foot-tall cylinder of magical energy centered on a point on the ground that you can see within range. Glowing runes appear wherever the cylinder intersects with the floor or other surface.\n\n* The creature can't willingly enter the cylinder by nonmagical means. If the creature tries to use teleportation or interplanar travel to do so, it must first succeed on a Charisma saving throw.\n\n* The creature has disadvantage on attack rolls against targets within the cylinder.\n\n* Targets within the cylinder can't be charmed, frightened, or possessed by the creature.\n\nWhen you cast this spell, you can elect to cause its magic to operate in the reverse direction, preventing a creature of the specified type from leaving the cylinder and protecting targets outside it."
> higher_level: "When you cast this spell using a spell slot of 4th level or higher, the duration increases by 1 hour for each slot level above 3rd."
> ```
