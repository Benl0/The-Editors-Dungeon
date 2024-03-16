---
cssclass:
  - cards
  - cards-1-1
  - cards-cols-3
date: 2024-03-03 16:05
publish: true
type: moc
tags:
  - DnD/Reference
back: "[[Reference MOC]]"
---
Back: 
# Defence items

## Shields
```dataviewjs
const bestiary = FantasyStatblocks.getBestiary();
const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.name).where(m => m.type.toLowerCase().contains('shield'))

dv.table(["Name", "Type", "Cost", "Weight"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.type, item.cost, item.weight]))
```
## Armour
```dataviewjs
const bestiary = FantasyStatblocks.getBestiary();
const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.name).where(m => m.type.toLowerCase().contains('armour'))

dv.table(["Name", "Type", "Cost", "Weight"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.type, item.cost, item.weight]))
```
