---
name: "Dags"
classification: "Homebrew"
size: "Medium"
type: "Humanoid"
alignment: "Lawful Good"
armor_class: 11 (None)
hit_points: 33
hit_die: "1d8-5"
speed:
  Walk: 30 ft
  Climb: 0 ft
  Swim: 0 ft
  Fly: 0 ft

strength: 0
dexterity: 0
constitution: 0
intelligence: 0
wisdom: 0
charisma: 0
initiative: -5
passive_perception: 5
proficiency_bonus: +2
saving_throws:
- Strength
skills:
- Athletics
damage_vulnerabilities:
- None
damage_resistances:
- None
damage_immunities:
- None
condition_immunities:
- None
senses:
- Perception +5
languages: Common
challenge_rating: "1/2"
xp: 100
monster_image: [[dagm]]
created: 2025-03-26T02:27
updated: 2025-03-30T01:58
---

![[dagm]]

# `= this.name`
_`= this.size` `= this.type`, `= this.alignment`_

>[!info] *Description*
>*DS*

**Armor Class:** `= this.armor_class`
**Hit Points:** `= this.hit_points` (`dice: 1d8-5`)
**Speed:** Walk `= this.speed.Walk`, Climb `= this.speed.Climb`, Swim `= this.speed.Swim`, Fly `= this.speed.Fly`

### **Abilities**
| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `= this.strength` (`= floor((this.strength - 10) / 2)`) | `= this.dexterity` (`= floor((this.dexterity - 10) / 2)`) | `= this.constitution` (`= floor((this.constitution - 10) / 2)`) | `= this.intelligence` (`= floor((this.intelligence - 10) / 2)`) | `= this.wisdom` (`= floor((this.wisdom - 10) / 2)`) | `= this.charisma` (`= floor((this.charisma - 10) / 2)`)|

**Initiative:** `= this.initiative`
**Passive Perception:** `= this.passive_perception`
**Proficiency Bonus:** +`= this.proficiency_bonus`
**Saving Throws:** Strength
**Skills:** `= this.skills`
**Damage Vulnerabilities:** `= this.damage_vulnerabilities`
**Damage Resistances:** `= this.damage_resistances`
**Damage Immunities:** `= this.damage_immunities`
**Condition Immunities:** `= this.condition_immunities`
**Languages:** `= this.languages`
**Challenge Rating:** `= this.challenge_rating`
**XP:** `= this.xp`

##### **Traits**
Something 

##### **Actions**
Something 

##### **Reactions**
something 

##### **Legendary Actions**
None

##### **Lair Actions**
None

##### **Regional Effects**
None

## Description
SD

##### **Spells**
Dags is a 1st-level spellcaster (Intelligence). Spell save DC 5, +-3 to hit with spell attacks.
  - Cantrip (at will): <a href='Mage Hand' class='internal-link'>Mage Hand</a>, <a href='Prestidigitation' class='internal-link'>Prestidigitation</a>
  - 1st level (2 slots): <a href='Detect Magic' class='internal-link'>Detect Magic</a>

```statblock
image: dagm
name: Dags
type: Medium Humanoid, Lawful Good
ac: 11
hp: 33 (1d8-5)
speed: Walk 30 ft, Swim 0 ft, Fly 0 ft, Climb 0 ft
str: 0
dex: 0
con: 0
int: 0
wis: 0
cha: 0
saves:
  - strength: -3
skills: Athletics
damage_vulnerabilities: none
damage_resistances: none
damage_immunities: none
condition_immunities: none
languages: Common
cr: 1/2
xp: 100
perception:
  - name: "Perception"
    desc: "Perception +5"
traits:
  - name: "Something"
    desc: ""
actions:
  - name: "Something"
    desc: ""
spells:
  - Dags is a 1st-level spellcaster (Intelligence). Spell save DC 5, +-3 to hit with spell attacks.
  - Cantrip (at will): <a href='Mage Hand' class='internal-link'>Mage Hand</a>, <a href='Prestidigitation' class='internal-link'>Prestidigitation</a>
  - 1st level (2 slots): <a href='Detect Magic' class='internal-link'>Detect Magic</a>
reactions:
  - name: "something"
    desc: ""
legendary_actions:
  - none
lair_actions:
  - none
regional_effects:
  - none
```