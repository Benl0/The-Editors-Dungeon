---
cssclass: 
date: 2024-03-05
publish: true
type: Magic
book: "[[Players Handbook.pdf]]"
tags:
  - "#DnD/Spells/Enchantment"
back: "[[Magic]]"
stablock: inline
---
Back: 


```statblock
layout: Spells
source: "SRD"
name: "Confusion"
image: [[confusion.png]]
level: "4"
school: "Enchantment"
class: "Bard, Druid, Sorcerer, Wizard"
duration: "Concentration, up to 1 minute"
ritual: "No"
casting_time: "1 action"
range: "90 feet"

components:
- name: "V"
- name: "S"
- name: "M"
comp_m: "three nut shells"

description: "This spell assaults and twists creatures' minds, spawning delusions and provoking uncontrolled action. Each creature in a 10-foot radius sphere centered on a point you choose within range must succeed on a Wisdom saving throw when you cast this spell or by affected by it.\n\nAn affected target can't take reactions and must roll a d10 at the start of each of its turns to determine its behaviour for that turn.\nAt the end of each of its turns, an affected target can make a Wisdom saving throw. If it succeeds, this effect ends for that target"
higher_level: "When you cast this spell using a spell slot of 5th level or higher, the radius of the sphere increases by 5 feet for each spell slot above 4th."
```



| d10  | Behaviour                                                                                                                                                                                       |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | The creature uses all its movement to move in a random direction. To determine the direction, roll a d8 and assign a direction to each die face. The creature doesn't take an action this turn. |
| 2-6  | The creature doesn't move or take actions this turn.                                                                                                                                            |
| 7-8  | The creature uses its action to make a melee attack against a randomly determined creature within its reach. If there is no creature within its reach, the creature does nothing this turn.     |
| 9-10 | The creature can act and move normally.                                                                                                                                                         |

