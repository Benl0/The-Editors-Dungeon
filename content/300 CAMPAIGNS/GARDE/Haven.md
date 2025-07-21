---
title: 
aliases: 
publish: true
cssclasses: 
date: 2024-05-06 11:56
type: location
tags:
  - Garde/City
world: Garde
campaign: Garde
faction: 
location: Verlust
description: Capital city of Verlust
species: 
gender: 
class:
---
##### Back: [[Verlust]]

*The capital and the largest cities in all of Garde. Home to the Trotz royal family of Garde and many economical districts, fed by the dockyards.*

# Places of Note
- [[The Spear Inn]]

> [!info]- Map
>![[Verlust - Haven.jpg]]

> [!example]- Districts
> - ### East Way
> 	- #### The Bowls
> 		- Seedy underbelly of Haven
> 		- Home to many taverns to drown your sorrows
> - ### Two Chapels
> 	- #### Castle
> 		- Home to the royal family
> 	- #### Milk Borough
> 	- #### Archer Street
> - ### Taylor’s Docks
> 	- Docks for the textile workers of the area. 
> 	- Their primary customers are the inventors, cooks and eccentrics of Black Lane.
> - ### Black Lane
> 	- Many inventors and tinkerers run down this street, on fire from another failed experiment. All the smoke leaves the area dark, gloomy and covered in black soot.
> - ### Cat Crest
> - ### Snow Docks
> - ### Ash Valley
> - ### Seven Hills
> - ### Egg Grove

---

> [!BUG]- GMs Corner
> ```dataview
> TABLE
> description AS "Description", faction AS "Faction", type AS "Type"
> FROM "300 CAMPAIGNS/Garde"
> WHERE contains(type,"npc") or contains(type,"faction") and location = "Haven"
> ```