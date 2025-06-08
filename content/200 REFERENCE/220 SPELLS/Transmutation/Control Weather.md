---
title: Control Weather
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: '[[Players Handbook.pdf]]'
page: 228
tags:
  - DnD/Spells/Transmutation
  - DnD/Spells/Lv8
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Druid
  - DnD/Spells/Class/Cleric

---

##### Back: [[Magic]] || Book: Player's Handbook || Page: 228

# Control Weather
- ![[sleet-storm.png]]
- **Casting:**
    - **Casting Time:** 10 minutes
    - **Duration:** Concentration, up to 8 hours
    - **Range:** Self (5-mile radius)
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]
    - [[Druid]]
    - [[Cleric]]

- **Info:**
    - **Level:** 8th
    - **School:** Transmutation
- **Components:**
    - VSM
    - Burning incense and bits of earth and wood mixed in water

## Description:
You take control of the weather within 5 miles of you for the duration. You must be outdoors to cast this spell. Moving to a place where you don't have a clear path to the sky ends the spell early.

 When you cast the spell, you change the current weather conditions, which are determined by the DM based on the climate and season. You can change precipitation, temperature, and wind. It takes 1d4 x 10 minutes for the new conditions to take effect. Once they do so, you can change the conditions again. When the spell ends, the weather gradually returns to normal. 

 When you change the weather conditions, find a current condition on the following tables and change its stage by one, up or down. When changing the wind, you can change its direction.


### Precipitation

| Stage | Condition                                  |
| ----- | ------------------------------------------ |
| 1     | Clear                                      |
| 2     | Light Clouds                               |
| 3     | Overcast or ground fog                     |
| 4     | Rain, hail, or snow                        |
| 5     | Torrential rain, driving hail, or blizzard |

### Temperature

| Stage | Condition       |
| ----- | --------------- |
| 1     | Unbearable heat |
| 2     | Hot             |
| 3     | Warm            |
| 4     | Cool            |
| 5     | Cold            |
| 6     | Artic cold      |

### Wind

| Stage | Condition     |
| ----- | ------------- |
| 1     | Calm          |
| 2     | Moderate wind |
| 3     | Strong wind   |
| 4     | Gale          |
| 5     | Storm         |



---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Control Weather"
> image: [[sleet-storm.png]]
> level: "8th"
> school: "Transmutation"
> class: "Wizard,Druid,Cleric"
> duration: "Concentration, up to 8 hours"
> ritual: "No"
> casting_time: "10 minutes"
> range: "Self (5-mile radius)"
>
> components: VSM
> comp_m: "burning incense and bits of earth and wood mixed in water"
>
> description: "You take control of the weather within 5 miles of you for the duration. You must be outdoors to cast this spell. Moving to a place where you don't have a clear path to the sky ends the spell early.\n\n When you cast the spell, you change the current weather conditions, which are determined by the DM based on the climate and season. You can change precipitation, temperature, and wind. It takes 1d4 x 10 minutes for the new conditions to take effect. Once they do so, you can change the conditions again. When the spell ends, the weather gradually returns to normal. \n\n When you change the weather conditions, find a current condition on the following tables and change its stage by one, up or down. When changing the wind, you can change its direction.\n\n**Temperature**\n\n- 1: Unbearable heat\n\n- 2: Hot\n\n- 3: Warm\n\n- 4: Cool\n\n- 5: Cold\n\n- 6: Arctic cold\n\n**Wind**\n\n- 1: Calm\n\n- 2: Moderate wind\n\n- 3: Strong wind\n\n- 4: Gale\n\n- 5: Storm\n\n**Precipitation**\n\n- 1: Clear\n\n- 2: Light clouds\n\n- 3: Overcast or ground fog\n\n- 4: Rain, hail, or snow\n\n- 5: Torrential rain, driving hail, or blizzard"
> higher_level: ""
> ```
