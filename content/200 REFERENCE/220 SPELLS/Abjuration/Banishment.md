---
title: Banishment
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 217
tags:
  - DnD/Spells/Abjuration
  - DnD/Spells/Lv4
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Warlock
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Paladin
  - DnD/Spells/Class/Cleric

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 217

# Banishment
- ![[banishment.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 1 minute
    - **Range:** 60 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]
    - [[Warlock]]
    - [[Sorcerer]]
    - [[Paladin]]
    - [[Cleric]]

- **Info:**
    - **Level:** 4th
    - **School:** Abjuration
- **Components:**
    - VSM
    - An item distasteful to the target

## Description:
You attempt to send one creature that you can see within range to another plane of existence. The target must succeed on a Charisma saving throw or be banished.

If the target is native to the plane of existance you're on, you banish the target to a harmless demiplane. While there, the target is incapacitated. The target remains there until the spell ends, at which point the target reappears in the space it left or in the nearest unoccupied space if that space is occupied.

If the target is native to a different plane of existance than the one you're on, the target is banished with a faint popping noise, returning to its home plane. If the spell ends before 1 minute has passed, the target reappears in the space it left or in the nearest unoccupied space if that space is occupied. Otherwise, the target doesn't return.

## At Higher Levels:
When you cast this spell using a spell slot of 5th level or higher, you can target one additional creature for each slot level above 4th.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Banishment"
> image: [[banishment.png]]
> level: "4th"
> school: "Abjuration"
> class: "Wizard,Warlock,Sorcerer,Paladin,Cleric"
> duration: "Concentration, up to 1 minute"
> ritual: "No"
> casting_time: "1 action"
> range: "60 feet"
>
> components: VSM
> comp_m: "an item distasteful to the target"
>
> description: "You attempt to send one creature that you can see within range to another plane of existence. The target must succeed on a Charisma saving throw or be banished.\n\nIf the target is native to the plane of existance you're on, you banish the target to a harmless demiplane. While there, the target is incapacitated. The target remains there until the spell ends, at which point the target reappears in the space it left or in the nearest unoccupied space if that space is occupied.\n\nIf the target is native to a different plane of existance than the one you're on, the target is banished with a faint popping noise, returning to its home plane. If the spell ends before 1 minute has passed, the target reappears in the space it left or in the nearest unoccupied space if that space is occupied. Otherwise, the target doesn't return."
> higher_level: "When you cast this spell using a spell slot of 5th level or higher, you can target one additional creature for each slot level above 4th."
> ```
