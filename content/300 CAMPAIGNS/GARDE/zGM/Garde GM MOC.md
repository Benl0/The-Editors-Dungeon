---
title: Delve into the Ruins - cont
publish: true
cssclasses:
  - dashboard
date: 2024-04-21 12:13
type: moc
tags:
  - Garde/GM
world: Garde
campaign: Garde
---
##### Back: [[Garde]]

# General
- ## Plan
	- [[Story Bible]]
	- [[Compelling Villains]]
	- [[To Exploit]]
	- [[Garde Roadmap]]
- ## Inspiration
	- [[Monster ideas]]
	- [[Campaign Ideas]]
- ## Reference
	- [[Garde Calendar]]
	- [[Plugins]]
- ## Lore
	- [[Garde History]]
	- [[The Three Moons]]
	- [[Astral Plane Anchors]]
- ## Other
	- [[To Research]]

# Characters
`button-cha-npc`



## Factions
```dataview
TABLE WITHOUT ID
file.link AS "Faction", location AS "Location"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"faction")
```


---

# Sessions
`button-ses-recap`  `button-ses-plan`

## Plan
```dataview
TABLE WITHOUT ID
file.link AS "Session", sessionNum AS "n", sessionDate AS "Session date"
FROM "300 CAMPAIGNS/Garde/zGM/SESSIONS"
SORT sessionNum
```


## Recap
```dataview
TABLE WITHOUT ID
file.link AS "Session", sessionNum AS "n", sessionDate AS "Session date"
FROM "300 CAMPAIGNS/Garde/SESSIONS"
WHERE type = "session"
SORT sessionNum
```

---
# Map

```leaflet
id: Garde
image: [[Garde v2 - 6k.jpg]]
defaultZoom: 6
```

# Vault Info
- 🗄️ **Recent file updates** `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(10).file.link)`
- 📊 **Stats**
    - File Count: `$=dv.pages().length`
    - Rules: `$=dv.pages('"100 RULES"').length`
    - Reference: `$=dv.pages('"200 REFERENCE"').length`
    - Garde: `$=dv.pages('"300 CAMPAIGNS/Garde"').length`


> [!warning]- Old
> - [[Story Plan v1]]
> - [[Story plan v2]]