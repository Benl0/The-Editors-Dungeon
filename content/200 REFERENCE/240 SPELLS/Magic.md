---
cssclasses:
  - cards
  - cards-1-1
  - cards-cols-4
date: 2024-03-03 16:05
type: moc
tags:
  - DnD/Reference
back: "[[Reference MOC]]"
---
Last Modified: (mday:: `= this.file.mday`)
# Defence items
**Continue importing from [[Foresight]]**

> [!INFO]- Conjuration
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('conjuration'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Necromancy
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('necromancy'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Evocation
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('evocation'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Abjuration
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('abjuration'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Transmutation
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('transmutation'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Divination
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('divination'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Enchantment
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('enchantment'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

> [!INFO]- Illusion
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains('illusion'))
> 
> dv.table(["Name", "Level", "Classes"], bestiaryArray.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class]))
> ```

---

> [!INFO]- Search
> ```dataviewjs
> const bestiary = FantasyStatblocks.getBestiary();
> const bestiaryArray = dv.array(Array.from(bestiary.values())).filter(m => m.school).where(m => m.school.toLowerCase().contains(''))
> 
> dv.el("bold", "Input: ")
> const inputField = dv.el('input', "input field")
> inputField.focus()
> 
> /* Fake table for show */
> dv.table(["Name", "Level", "Classes", "School"], [])
> 
> inputField.addEventListener('input', async (event) => {
> 	this.container.lastChild.remove()
> 	dv.table(["Name", "Level", "Classes", "School"], 
> 		bestiaryArray
> 			.filter(m => m.name)
> 			.filter(m => m.name.toLowerCase().includes(inputField.value.toLowerCase()))
> 		.map((spell) => [dv.fileLink(spell.name), spell.level, spell.class, spell.school]))	
> });
> ```

