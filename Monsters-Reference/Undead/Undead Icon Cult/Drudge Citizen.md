---
aliases: [Drudge Citizen]
created: 
description: 
image: 
level: 3
publish: 
role: troop
statblock: inline
strength: normal
tags: ["13A/Bestiary/undead", "13A/Monsters/Type/troop"]
type: undead
updated: 
---
```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Drudge Citizen"
size: "normal"
level: "3"
levelOrdinal: "3rd"
role: "troop"
type: "undead"
initiative: "3"
actions:
    - name: "Clumsy scythe +8 vs. AC"
      desc: "10 damage"
      traits:
          - name: "Natural 1-5"
            desc: "Deal damage equal to the natural d20 roll to both the target and the drudge citizen."
traits:
    - name: "Sudden intelligence"
      desc: "Once per battle when the drudge moves it does not provoke opportunity attacks and if it makes a _clumsy scythe_ attack immediately after it moves it gets a +2 bonus to its attack and deals half damage on a miss."
nastier_traits:
    - name: "Smarter than it looks"
      desc: "Once per battle the drudge gets to reroll a missed _clumsy scythe_ attack, and deals 5 damage if it still miss."
ac: "18"
pd: "18"
md: "10"
hp: "52"
```
