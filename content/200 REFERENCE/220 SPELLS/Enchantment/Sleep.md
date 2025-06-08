---
title: Sleep
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 276
tags:
  - DnD/Spells/Enchantment
  - DnD/Spells/Lv1
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Bard

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 276

# Sleep
- ![[sleep.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** 1 minute
    - **Range:** 90 feet
    - **Ritual:** No
    - **Concentration:** No
- **Classes:**
    - [[Wizard]]
    - [[Sorcerer]]
    - [[Bard]]

- **Info:**
    - **Level:** 1st
    - **School:** Enchantment
- **Components:**
    - VSM
    - A pinch of fine sand, rose petals, or a cricket

## Description:
This spell sends creatures into a magical slumber. Roll 5d8; the total is how many hit points of creatures this spell can affect. Creatures within 20 feet of a point you choose within range are affected in ascending order of their current hit points (ignoring unconscious creatures).

Starting with the creature that has the lowest current hit points, each creature affected by this spell falls unconscious until the spell ends, the sleeper takes damage, or someone uses an action to shake or slap the sleeper awake. Subtract each creature's hit points from the total before moving on to the creature with the next lowest hit points. A creature's hit points must be equal to or less than the remaining total for that creature to be affected.

Undead and creatures immune to being charmed aren't affected by this spell.

## At Higher Levels:
When you cast this spell using a spell slot of 2nd level or higher, roll an additional 2d8 for each slot level above 1st.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Sleep"
> image: [[sleep.png]]
> level: "1st"
> school: "Enchantment"
> class: "Wizard,Sorcerer,Bard"
> duration: "1 minute"
> ritual: "No"
> casting_time: "1 action"
> range: "90 feet"
>
> components: VSM
> comp_m: "a pinch of fine sand, rose petals, or a cricket"
>
> description: "This spell sends creatures into a magical slumber. Roll 5d8; the total is how many hit points of creatures this spell can affect. Creatures within 20 feet of a point you choose within range are affected in ascending order of their current hit points (ignoring unconscious creatures).\n\nStarting with the creature that has the lowest current hit points, each creature affected by this spell falls unconscious until the spell ends, the sleeper takes damage, or someone uses an action to shake or slap the sleeper awake. Subtract each creature's hit points from the total before moving on to the creature with the next lowest hit points. A creature's hit points must be equal to or less than the remaining total for that creature to be affected.\n\nUndead and creatures immune to being charmed aren't affected by this spell."
> higher_level: "When you cast this spell using a spell slot of 2nd level or higher, roll an additional 2d8 for each slot level above 1st."
> ```
