---
cssclass: 
date: <%tp.file.creation_date()%>
type: <%tp.system.suggester(["Note","Item","Weapon","Magic","PC","NPC","Monster"],["note","item","weapon","magic","pc","npc","monster"])%>
book: "[[<%tp.system.suggester(["Players Handbook","Dungeon Masters Guide","Monster Manual","Tashas Cauldron of Everything"],["Players Handbook.pdf","Dungeon masters guide.pdf","Monster Manual.pdf","Tashas Cauldron of Everything.pdf"])%>#page=<%tp.system.prompt("Page Number","1")%>]]"
tags: 
back:
stablock: inline
---
Last Modified: (mday:: `= this.file.mday`)

