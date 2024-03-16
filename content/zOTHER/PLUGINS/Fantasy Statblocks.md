---
date: 2023-01-28 20:29
publish: true
type: note
tags:
  - DnD/Plugins
back: "[[Plugins]]"
link: https://github.com/javalent/fantasy-statblocks
---
Back: 

---

# Fantasy Statblocks
## Item
Use the [[Stat - Item]] template for Item cards. Use `\n` to add line breaks in descriptions
```statblock
layout: Items
name: "Shield"
image: [[armour.png]]
category: "Shield"
cost: "10 gp"
rarity: "Common"

ac: "2"

damage: 
damage_type: 
properties: 

description: "A shield is made from wood or metal and is carried in one hand. Wielding a shield increases your Armor Class by 2. You can benefit from only one shield at a time. "
```

## Spells
Use the [[Stat - Spell]] template for spell cards
```statblock
layout: Spells
name: "Heat Metal"
image: [[armour.png]]
damage: 2d8
heal:

level: 2
school: Transmutation
class: "Druid, Bard"
casting: 1 action
duration: "Concentration, 1min max"
range: 60ft
ritual: No
components: 
- name: "V"
- name: "S"
- name: "M"
comp_m: "1 piece of iron. A flame"

description: "Choose a manufactured metal object, such as a metal weapon or a suit of heavy or medium metal armor, that you can see within range. You cause the object to glow red-hot. Any creature in physical contact with the object takes 2d8 fire damage when you cast the spell. Until the spell ends, you can use a bonus action on each of your subsequent turns to cause this damage again.\n\nIf a creature is holding or wearing the object and takes the damage from it, the creature must succeed on a Constitution saving throw or drop the object if it can. If it doesn’t drop the object, it has disadvantage on attack rolls and ability checks until the start of your next turn."
higher_level: "When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d8 for each slot level above 2nd"
```


## Character Sheet (full)
Use the [[Stat - Character Full]] template for detailed character sheets.
```statblock
layout: Character Sheet Full
dice: true
name: Alaric
race: Wood-Elf
class: Ranger
level: 1
exp: 100
image: [[elf archer.png]]

ac: 12
proficiency_bonus: "+2"
speed: 35
initiative: 14

senses: "Darkvision, Passive Perception 14"
vulnerabilities: None
resistances: Piercing
immunities: None

hp: 12
max_hp: 15
temp_hp: 0
hit_dice: 1
hit_dice_total: 1d8

stats: [12, 17, 12, 12, 12, 12]
skills: 
 - Acrobatics: 1 
 - Animal Handling: 1
 - Arcana: 1
 - Athletics: 1
 - Deception: 1
 - History: 1
 - Insight: 1
 - Intimidation: 1
 - Investigation: 1
 - Medicine: 1
 - Nature: 1
 - Perception: 1
 - Performance: 1
 - Persuasion: 1
 - Religion: 1
 - Sleight of Hand: 1
 - Stealth: 1
 - Survival: 1

actions:
  - name: Longbow
    desc: "Shoot a bow"
race_traits:
  - name: Darkvision
    desc: "See in the dark"
class_traits:      
  - name: Fleet of Foot
    desc: "Go fast"
proficiencies: Longbow, Short bow
languages: Common, Elvish

bonus_actions:
  - name: Bonus1
    desc: "Extra things"
reactions:
  - name: Reaction1
    desc: "Lightning reflexes"

spells:
  - spellcasting description
  - Cantrips: Eldritch blast
  - 1st level: Healing Word
  - 2nd level: text
  - 3rd level: text
  - 4th level: text
  - 5th level: text
  - 6th level: text
  - 7th level: text
  - 8th level: text
  - 9th level: text
  - "Spell notes"
spell_slots: [1,0,0,0,0,0,0,0,0]

currencies: 10gp
inventory: Explorer's pack
weapons: Longbow, 20 arrows

death_saves_successes: 0
death_saves_failures: 0

gender: Man
size: Medium
height: 5ft 8'
weight: 90kg
hair: Black
eyes: Hazel
skin: Wooden
alignment: NG
faith: None
age: 200

backstory: "Robin Hood is my hero"
background: Robin Hood
personality_traits: Robin Hood
ideals: Robin Hood
bonds: Robin Hood
flaws: Robin Hood
```


