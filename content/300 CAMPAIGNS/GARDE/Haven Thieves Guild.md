---
title: 
aliases: 
publish: false
cssclasses: 
date: 2024-06-21 13:09
type: faction
tags:
  - Garde/Factions
world: Garde
campaign: Garde
faction: 
location: Haven
description: 
species: 
gender: 
class:
---
##### Back: [[Garde]]
# Heading


```dataview
TABLE WITHOUT ID
file.link AS "Character", race AS "Race", class AS "Class", location AS "Home", description AS "Description"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"npc") AND faction = this.file.name
SORT file.name
```