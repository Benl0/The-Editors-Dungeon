---
cssclasses:
  - cards
  - cards-1-1
  - cards-cols-3
date: 2024-03-03 16:05
type: moc
tags:
  - DnD/Reference
back: "[[Reference MOC]]"
---
Last Modified: (mday:: `= this.file.mday`)
# Weapons
> [!INFO]- Simple Melee Weapons
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('simple'))
> 
> dv.table(["Name", "Damage", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.damage, item.cost]))
> ```

> [!INFO]- Martial Melee Weapons
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('martial'))
> 
> dv.table(["Name", "Damage", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.damage, item.cost]))
> ```

> [!INFO]- Simple Ranged Weapons
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('simple ranged'))
> 
> dv.table(["Name", "Damage", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.damage, item.cost]))
> ```

> [!INFO]- Martial Ranged Weapons
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('martial ranged'))
> 
> dv.table(["Name", "Damage", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.damage, item.cost]))
> ```