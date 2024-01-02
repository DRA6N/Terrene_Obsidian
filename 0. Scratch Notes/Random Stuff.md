---
Image: ![[Thandion Reeves.png]]

---

```button
name New NPC
type note(New_NPC, split) template
action NPC Template
templater true
```

### Button Tests
```meta-bind-button
label: Test Button
hidden: false
id: test
style: primary
actions:
  - type: open
    link: "![[Thandion Reeves.png]]"

```

```meta-bind-button
label: Show to Players
hidden: false
id: ""
style: primary
actions:
  - type: command
    command: image-window:open-image

```
---

```meta-bind-button
label: NPC Generate
hidden: false
id: NPC_Gen
style: primary
actions:
  - type: templaterCreateNote
    templateFile: Templates/NPC Template.md
    folderPath: 1. World Almanac/NPCs
    fileName: From Template
    openNote: true

```

