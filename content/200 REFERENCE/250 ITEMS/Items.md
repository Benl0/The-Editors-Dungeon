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

> [!INFO]- Armour
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('armour'))
> 
> dv.table(["Name", "Category", "AC", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.ac, item.cost]))
> ```

> [!INFO]- Tools
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('tools'))
> 
> dv.table(["Name", "Category", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.cost]))
> ```

> [!INFO]- Potions & Oils
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('potions oils'))
> 
> dv.table(["Name", "Category", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.cost]))
> ```

> [!INFO]- Poisons
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('poisons'))
> 
> dv.table(["Name", "Category", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.cost]))
> ```

> [!INFO]- Adventuring Gear
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('adventuring gear'))
> 
> dv.table(["Name", "Category", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.cost]))
> ```

> [!INFO]- Other
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains('other'))
> 
> dv.table(["Name", "Category", "Cost"], bestiaryArray.map((item) => [dv.fileLink(item.name), item.category, item.cost]))
> ```

---

> [!INFO]- Search
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.category).where(m => m.category.toLowerCase().contains(''))
> 
> dv.el("bold", "Input: ")
> const inputField = dv.el('input', "input field")
> inputField.focus()
> 
> /* Fake table for show */
> dv.table(["Name", "Category", "Cost"], [])
> 
> inputField.addEventListener('input', async (event) => {
> 	this.container.lastChild.remove()
> 	dv.table(["Name", "Category", "Cost"], 
> 		bestiaryArray
> 			.filter(m => m.name)
> 			.filter(m => m.name.toLowerCase().includes(inputField.value.toLowerCase()))
> 		.map((item) => [dv.fileLink(item.name), item.category, item.cost]))	
> });
> ```