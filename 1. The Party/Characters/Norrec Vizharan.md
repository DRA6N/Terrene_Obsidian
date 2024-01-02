---
Type: character
Alias: Norrec
tags:
- character
- PC
Name: Norrec Vizharan
Race: "[[human|Human]]"
gender: Male
class: "[[fighter|Fighter]]"
level: 1
background: 
alignment: Neutral Good
age: 27
height: 5'7"
weight: 185lbs
hair: Dark Brown
eyes: Brown
skin: Pale
faction:
portrait: "![[Norrec Vizharan.png]]"
campaign: 

Strength: 19
Dexterity: 12
Constitution: 14
Intelligence: 19
Wisdom: 11
Charisma: 10
HP: 20
AC: 10
Speed: 30 ft.
Initiative: 12

cssclass: 
  - illusion
---
# `=this.file.name`

> [!infobox|left]
> ![[Norrec Vizharan.png]]
>
> |||
> |---|---|
> |Race| `=this.race`|
> |Class| `=this.class`|
> |Level| `=this.level`|
> |Alignment| `=this.alignment`|
> ###### Stats  
> Type |  Stat |  
> ---|:---:|  
> HP | `=this.hp` |  
> AC | `=this.ac` |  
> Speed | `=this.speed` |  
> Initiative | `=this.initiative` |
> ## Ability Scores
> 
> |Stat |Score|Modifier|
> | --- | :---: | :---: |
> | STR | `=this.Strength` |`$=Math.floor((dv.current().Strength-10)/2)`|
> | DEX |`=this.Dexterity` |`$=Math.floor((dv.current().Dexterity-10)/2)`|
> | CON |`=this.Constitution` |`$=Math.floor((dv.current().Constitution-10)/2)`|
> | INT |`=this.Intelligence` |`$=Math.floor((dv.current().Intelligence-10)/2)`|
> | WIS |`=this.Wisdom` |`$=Math.floor((dv.current().Wisdom-10)/2)`|
> | CHA |`=this.Charisma` |`$=Math.floor((dv.current().Charisma-10)/2)`|
> # Saves
> 
> |||
> |-|:-:|
> |AC|11
> |INT|+6
> |WIS|+2

> [!infobox|right]
> ## Appearance
> |     |     |
> | --- | :---: |
> |Gender| `=this.gender`|
> |Age| `=this.age`|
> |Height| `=this.height`|
> |Weight| `=this.weight`|
> |Hair| `=this.hair`|
> |Eyes| `=this.eyes`|
> |Skin| `=this.skin`|
> |Faction| `=this.faction`|

#   
### Personality Traits
- I've lost too many friends, and I'm slow to make new ones.
- To me, a tavern brawl is a nice way to get to know a new city.
### Ideals
- Sincerity. There's no good pretending to be something I'm not.
### Bonds
### Flaws
### Background:
Norrec, the embodiment of strength and honor in the fantasy realm, stands as a paragon of resilience and unwavering principles. Guided by a personal code, he navigates the complexities of his world with a dedication to honor and integrity, manifesting in each action on and off the battlefield. Known for his loyalty, Norrec forms unbreakable bonds with comrades, cherishing the value of camaraderie in his quest for a just and noble cause. Determination fuels his endeavors, as he faces challenges with an unyielding resolve, pushing through obstacles until his goals are attained. Disciplined through rigorous training, Norrec's every movement reflects precision and effectiveness in combat. As a natural protector, he assumes a guardian role, extending his shield to friends, family, and the innocent, his actions resounding louder than spoken vows. Reserved in speech, Norrec lets his deeds speak for him, preferring the eloquence found in actions over prolonged discussions. Pragmatic in his decision-making, he favors practical solutions, navigating his journey with a clear sense of purpose. Adaptability, coupled with a cautious yet versatile approach, marks Norrec as a formidable force on any quest or battlefield, his name echoing through the annals of fantasy lore.

___
# Attributes


>[!columns|no-icon] Skills
>>[!note|no-icon]
> |                          |                 |     |                          |
> | ------------------------ | --------------- | --- | ------------------------ |
> | <input type="checkbox" checked> | Acrobatics      | Dex | <input type="checkbox" > |
> | <input type="checkbox" > | Animal Handling | Wis | <input type="checkbox" > |
> | <input type="checkbox" > | Arcana          | Int | <input type="checkbox" > |
> | <input type="checkbox" checked> | Athletics       | Str | <input type="checkbox" > |
> | <input type="checkbox" > | Deception       | Cha | <input type="checkbox" > |
> | <input type="checkbox" > | History         | Int | <input type="checkbox" > |
> | <input type="checkbox" checked> | Insight         | Wis | <input type="checkbox" > |
> | <input type="checkbox" > | Intimidation    | Cha | <input type="checkbox" > |
> | <input type="checkbox" > | Investigation   | Int | <input type="checkbox" > |
> | <input type="checkbox" > | Medicine        | Wis | <input type="checkbox" > |
> | <input type="checkbox" > | Nature          | Int | <input type="checkbox" > |
> | <input type="checkbox" > | Perception      | Wis | <input type="checkbox" > |
> | <input type="checkbox" > | Performance     | Cha | <input type="checkbox" > |
> | <input type="checkbox" checked> | Persuasion      | Cha | <input type="checkbox" > |
> | <input type="checkbox" > | Religion        | Int | <input type="checkbox" > |
> | <input type="checkbox" > | Sleight of Hand | Dex | <input type="checkbox" > |
> | <input type="checkbox" > | Stealth         | Dex | <input type="checkbox" > |
> | <input type="checkbox" > | Survival        | Wis | <input type="checkbox" > |
> 
 >
 >>[!note|no-t]
>> ### Untrained
>>| Name            | Bonus |
>>| --------------- | ----- |
>>| Acrobatics      | +1    |
>>| Animal Handling | +0    |
>>| Athletics       | -1    |
>>| Deception       | +0    |
>>| History         | +4    |
>>| Intimidation    | +0    |
>>| Nature          | +4    |
>>| Performance     | +0    |
>>| Persuasion      | +0    |
>>| Religion        | +4    |
>>| Sleight of Hand | +1    |
>>| Stealth         | +1    |
>>| Survival        | +0    |


> [!columns|no-icon] ## Spellcasting (DC: 14)
>> [!feature] ### Innate Casting 
>>> [!error]- Invisibility (1/LR)
>>> A creature you touch becomes invisible until the spell ends. Anything the target is wearing or carrying is invisible as long as it is on the target's person. The spell ends for a target that attacks or casts a spell.
> >
> >> [!error]- Inflict Wounds (1/LR)
> >> Make a melee spell Attack against a creature you can reach. On a hit, the target takes 3d10 necrotic damage.
> 
> >[!feature] ### Cantrip
>>> [!error]- Chill Touch
> >>![[Chill Touch|no-title clean]]
> >
> >
>>> [!error]- Toll the Dead 
> >>![[Toll the Dead|no-title clean]]
> >
> >
>>> [!error]- Prestidigitation
> >>![[Prestidigitation|no-title clean]]
> >
> >
>>> [!error]- Light
> >>![[Light|no-title clean]]
> 
> 
>>[!feature] ### 1st Level (4/LR)
>>> [!error]- Identify
> >>![[Identify|no-title clean]]
> >
> >
>>> [!error]- Unseen Servant
> >>![[Unseen Servant|no-title clean]]
> >
> >
>>> [!error]- Ray of Sickness
> >>![[Ray of Sickness|no-title clean]]
> >
> >
>>> [!error]- Sleep
> >>![[Sleep|no-title clean]]
> >
> >
>>> [!error]- Shield
> >>![[Shield|no-title clean]]
> >
> >
>>> [!error]- Feather Fall
> >>![[Feather Fall|no-title clean]]
> >
> >
>>> [!error]- Find Familiar
> >>![[Find Familiar|no-title clean]]
> >
> >
>>> [!error]- Floating Disk
> >>![[Floating Disk|no-title clean]]
> >
>>>[!error]- Inflict Wounds
> >>![[Inflict Wounds|no-title clean]]
> 
> 
>>[!feature] ### 2nd Level (3/LR)
>>> [!error]- Hold Person
> >>![[Hold Person|no-title clean]]
> >
> >
>>> [!error]- Scorching Ray
> >>![[Scorching Ray|no-title clean]]
> >
> >
>>> [!error]- Locate Object
> >>![[Locate Object|no-title clean]]
> >
> >
>>> [!error]- See Invisibility
> >>![[See invisibility|no-title clean]]
> >
> >
>>> [!error]- Invisibility
> >>![[Invisibility|no-title clean]]
> 
> 
>>[!feature] ### 3rd Level (3/LR)
>>> [!error]- Animate Dead 
> >>![[Animate Dead |no-title clean]]
> >
> >
>>> [!error]- Counterspell
> >>![[Counterspell|no-title clean]]
> >
> >
>>> [!error]- Fireball
> >>![[Fireball|no-title clean]]
> >
> >
>>> [!error]- Haste
> >>![[Haste|no-title clean]]
> >
> >
>>> [!error]- Summon Undead
> >>![[Summon Undead|no-title clean]]
> 
> 
>>[!feature] ### 4th Level (1/LR)
>>> [!error]- Polymorph
> >>![[Polymorph|no-title clean]]

> [!columns|no-icon] ## Class Features: Wizard - Necromancer
>> [!feature]- Arcane Recovery (1/Long Rest)
>> You have learned to regain some of your magical energy by studying your spellbook. Once per day when you finish a short rest, you can choose expended spell slots to recover. The spell slots can have a combined level that is equal to or less than half your wizard level (rounded up), and none of the slots can be 6th level or higher.
>> 
>> For example, if you're a 4th-level wizard, you can recover up to two levels worth of spell slots. You can recover either a 2nd-level spell slot or two 1st-level spell slots.
>
>> [!feature]- Grim Harvest (Level 2)
>> You gain the ability to reap life energy from creatures you kill with your spells. Once per turn when you kill one or more creatures with a spell of 1st level or higher, you regain hit points equal to twice the spell's level, or three times its level if the spell belongs to the School of Necromancy. You don't gain this benefit for killing constructs or undead.
>
>>[!feature]- Undead Thralls (Level 6)
>>You add the Animate Dead spell to your spellbook if it is not there already. When you cast Animate Dead, you can target one additional corpse or pile of bones, creating another zombie or skeleton, as appropriate.
>>Whenever you create an undead using a necromancy spell, it has additional benefits:
>>- The creature's hit point maximum is increased by an amount equal to your wizard level.
>>- The creature adds your proficiency bonus to its weapon damage rolls.

> [!columns|no-icon] ## Feats / Traits
> > [!feat]- Shadow Touched (Human Varient)
> > Your exposure to the Shadowfell's magic has changed you, granting you the following benefits:
> > - Increase your Intelligence, Wisdom, or Charisma score by 1, to a maximum of 20.
> > - You learn the Invisibility spell and one 1st-level spell of your choice. The 1st-level spell must be from the Illusion or Necromancy school of magic. You can cast each of these spells without expending a spell slot. Once you cast either of these spells in this way, you can't cast that spell in this way again until you finish a long rest. You can also cast these spells using spell slots you have of the appropriate level. The spells' spellcasting ability is the ability increased by this feat.
> 
> 
> >[!feat]- Gambling Addiction, Mild
> >She has a bit of a gambling addiction she has to sate once a while with mild **Wisdom Saving Throw DC 11 Check** to not fall prone to gamble.
> >
> >Wisdom Saving Throw:  `dice:1d20+2`
> 
> > [!feat]- All Eyes on You (Background: Far Traveler)
> > Your accent, mannerisms, figures of speech, and perhaps even your appearance all mark you as foreign. Curious glances are directed your way wherever you go, which can be a nuisance, but you also gain the friendly interest of scholars and others intrigued by far-off lands, to say nothing of everyday folk who are eager to hear stories of your homeland.
> > 
> > You can parley this attention into access to people and places you might not otherwise have, for you and your traveling companions. Noble lords, scholars, and merchant princes, to name a few, might be interested in hearing about your distant homeland and people.
> 
> 
> > [!feat]- Ability Score Improvement (Level 4)
> > When you reach 4th level, and again at 8th, 12th, 16th, and 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.


# Campaign Logs
```dataview
table session as Session, date as "Date"
from #ttrpg
where file.frontmatter.campaign = this.file.frontmatter.campaign
sort date desc
```

Spells list %% Have yet to use it so unlinked%% 

Hold Person 
Scorching ray
Locate Object
See invisibility
Invisibility 

Animate Dead
Counterspell
Fireball
Summon Undead 
Haste

Polymorph