---
AssociatedGroup: 
Gender: 
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Location: 
NoteIcon: npc
Condition: 
Image: 
---

<% tp.file.title %>
<% await tp.file.move("/1. World Almanac/NPCs/" + tp.file.title) %>

<%* const hasTitle = !tp.file.title.startsWith("");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[1. World Almanac/NPCs/NPC Images/ImagePlaceholder.png|cover hsmall]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.Gender` |
> Race | `=this.Race` |
> Age | `=this.Age` |
> Condition | `=this.Condition` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

# `=this.file.name`
## Profile

**<Add description here, extend it with AI Text Generator using Ctrl J>*

> [!info] Statblock
> ```statblock
> image: 
> name: Individual
> monster: Commoner
> columns: 2
> ```
