---
title: 
alias: 
publish: false
cssclasses: 
date: 2024-07-17 12:01
type: 
tags: 
world: Garde
campaign: Garde
faction: 
location: 
description: 
species: 
gender: 
class:
---
##### Back: [[The Crumbling Moon]]

---

> [!IMPORTANT] Life for the people. Blood for The Crumbling Moon.

Kidnap sorcerer's from all over Garde. Sap away the magic from their body to stop them from ascending
An ancient order that has lost it's original purpose and goals. They operate via traditions that have lost their meanings

## [[Crumbling Moon Manifesto|Manifesto]]


# Members
```dataview
TABLE WITHOUT ID
file.link AS "Character", race AS "Race", class AS "Class", location AS "Home", description AS "Description"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"npc") AND faction = "The Crumbling Moon"
SORT file.name
```
