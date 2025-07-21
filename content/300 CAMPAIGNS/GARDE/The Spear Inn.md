---
title: 
aliases: 
publish: true
cssclasses: 
date: 2024-05-06 12:47
type: faction
tags:
  - Garde/Location/Verlust
world: Garde
campaign: Garde
faction: 
location: Haven
description: Inn within the city of Haven
species: 
gender: 
class:
---
##### Back: [[Haven]]

*An inn within the city of [[Haven]]*

## Staff and Patrons
- Barkeep [[Torz]]

> [!INFO]- Map
> ![[The Spear Inn - 1st floor.jpg]]


```dataview
TABLE WITHOUT ID
file.link AS "Character", race AS "Race", class AS "Class", location AS "Home", description AS "Description"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"npc") AND faction = this.file.name
SORT file.name
```