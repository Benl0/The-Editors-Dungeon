---
cssclass: 
date: 2024-03-05
type: Magic
book: "[[Players Handbook.pdf]]"
tags:
  - "#DnD/Spells/Enchantment"
back: "[[Magic]]"
stablock: inline
---
Last Modified: (mday:: `= this.file.mday`)


```statblock
layout: Spells
source: "SRD"
name: "Sleep"
image: [[sleep.png]]
level: "1"
school: "Enchantment"
class: "Bard, Sorcerer, Wizard"
duration: "1 minute"
ritual: "No"
casting_time: "1 action"
range: "90 feet"

components:
- name: "V"
- name: "S"
- name: "M"
comp_m: "a pinch of fine sand, rose petals, or a cricket"

description: "This spell sends creatures into a magical slumber. Roll 5d8; the total is how many hit points of creatures this spell can affect. Creatures within 20 feet of a point you choose within range are affected in ascending order of their current hit points (ignoring unconscious creatures).\n\nStarting with the creature that has the lowest current hit points, each creature affected by this spell falls unconscious until the spell ends, the sleeper takes damage, or someone uses an action to shake or slap the sleeper awake. Subtract each creature's hit points from the total before moving on to the creature with the next lowest hit points. A creature's hit points must be equal to or less than the remaining total for that creature to be affected.\n\nUndead and creatures immune to being charmed aren't affected by this spell."
higher_level: "When you cast this spell using a spell slot of 2nd level or higher, roll an additional 2d8 for each slot level above 1st."
```