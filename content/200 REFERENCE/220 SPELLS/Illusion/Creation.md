---
title: Creation
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 229
tags:
  - DnD/Spells/Illusion
  - DnD/Spells/Lv5
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Artificer

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 229

# Creation
- ![[creation.png]]
- **Casting:**
    - **Casting Time:** 1 minute
    - **Duration:** Special
    - **Range:** 30 feet
    - **Ritual:** No
    - **Concentration:** No
- **Classes:**
    - [[Wizard]]
    - [[Sorcerer]]
    - [[Artificer]]

- **Info:**
    - **Level:** 5th
    - **School:** Illusion
- **Components:**
    - VSM
    - A tiny piece of matter of the same type of the item you plan to create

## Description:
You pull wisps of shadow material from the Shadowfell to create a nonliving object of vegetable matter within range: soft goods, rope, wood, or something similar. You can also use this spell to create mineral objects such as stone, crystal, or metal. The object created must be no larger than a 5-foot cube, and the object must be of a form and material that you have seen before.

The duration depends on the object's material. If the object is composed of multiple materials, use the shortest duration.

| Material              | Duration   |
| --------------------- | ---------- |
| Vegetable matter      | 1 day      |
| Stone or crystal      | 12 hours   |
| Precious metals       | 1 hour     |
| Gems                  | 10 minutes |
| Adamantine or mithral | 1 minute   |

Using any material created by this spell as another spell's material component causes that spell to fail.

## At Higher Levels:
When you cast this spell using a spell slot of 6th level or higher, the cube increases by 5 feet for each slot level above 5th.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Creation"
> image: [[creation.png]]
> level: "5th"
> school: "Illusion"
> class: "Wizard,Sorcerer,Artificer"
> duration: "Special"
> ritual: "No"
> casting_time: "1 minute"
> range: "30 feet"
>
> components: VSM
> comp_m: "a tiny piece of matter of the same type of the item you plan to create"
>
> description: "You pull wisps of shadow material from the Shadowfell to create a nonliving object of vegetable matter within range: soft goods, rope, wood, or something similar. You can also use this spell to create mineral objects such as stone, crystal, or metal. The object created must be no larger than a 5-foot cube, and the object must be of a form and material that you have seen before.\n\nThe duration depends on the object's material. If the object is composed of multiple materials, use the shortest duration.\n\n- Vegetable matter: 1 day\n\n- Stone or crystal: 12 hours\n\n- Precious metals: 1 hour\n\n- Gems: 10 minutes\n\n- Adamantine or mithral: 1 minute\n\nUsing any material created by this spell as another spell's material component causes that spell to fail."
> higher_level: "When you cast this spell using a spell slot of 6th level or higher, the cube increases by 5 feet for each slot level above 5th."
> ```
