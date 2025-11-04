---
name: "First-Year"
classification: "Homebrew"
size: "Medium"
type: "Humanoid"
alignment: "Lawful Good"
armor_class: 11 (None)
hit_points: 32
hit_die: "6d8+6"
speed:
  Walk: 30 ft
  Climb: 0 ft
  Swim: 0 ft
  Fly: 0 ft

strength: 8
dexterity: 12
constitution: 13
intelligence: 12
wisdom: 10
charisma: 11
initiative: 1
passive_perception: 10
proficiency_bonus: +2
saving_throws:
- None
skills:
- None
damage_vulnerabilities:
- None
damage_resistances:
- None
damage_immunities:
- None
condition_immunities:
- None
senses:
- None
languages: Common plus any two languages
challenge_rating: "1/2"
xp: 100
monster_image: [[~Attachments/NPCs/Avymys.jpg]]
created: 2025-03-26T02:27
updated: 2025-03-30T01:58
---

![[~Attachments/NPCs/Avymys.jpg]]

# `= this.name`
_`= this.size` `= this.type`, `= this.alignment`_

>[!info] *Description*
>*A student who has not yet chosen one of Strixhaven’s five mystic colleges is referred to as a first-year student, after the one year of basic curriculum that most students must complete before selecting their school. These beginner students are taught by faculty from all of Strixhaven’s colleges, learning rudimentary magic as they acclimate to the university’s environment. Once a student has selected a college, they trade their plain gray first-year uniforms for the trappings of their chosen school and begin honing—or even replacing—the magic they learned in their initial year with other skills.*

**Armor Class:** `= this.armor_class`
**Hit Points:** `= this.hit_points` (`dice: 6d8+6`)
**Speed:** Walk `= this.speed.Walk`, Climb `= this.speed.Climb`, Swim `= this.speed.Swim`, Fly `= this.speed.Fly`

### **Abilities**
| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `= this.strength` (`= floor((this.strength - 10) / 2)`) | `= this.dexterity` (`= floor((this.dexterity - 10) / 2)`) | `= this.constitution` (`= floor((this.constitution - 10) / 2)`) | `= this.intelligence` (`= floor((this.intelligence - 10) / 2)`) | `= this.wisdom` (`= floor((this.wisdom - 10) / 2)`) | `= this.charisma` (`= floor((this.charisma - 10) / 2)`)|

**Initiative:** `= this.initiative`
**Passive Perception:** `= this.passive_perception`
**Proficiency Bonus:** +`= this.proficiency_bonus`
**Saving Throws:** None
**Skills:** `= this.skills`
**Damage Vulnerabilities:** `= this.damage_vulnerabilities`
**Damage Resistances:** `= this.damage_resistances`
**Damage Immunities:** `= this.damage_immunities`
**Condition Immunities:** `= this.condition_immunities`
**Senses:** `= this.senses`
**Languages:** `= this.languages`
**Challenge Rating:** `= this.challenge_rating`
**XP:** `= this.xp`

##### **Traits**
Excited to Be Here. The student has advantage on initiative rolls.

##### **Actions**
Magic Flare. Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. Hit: 7 (`dice: 1d12+1`) force damage.

##### **Reactions**
Beginner’s Luck (2/Day). When the student fails a saving throw, it can reroll the d20. It must use the new roll.

##### **Legendary Actions**
None

##### **Lair Actions**
None

##### **Regional Effects**
None

## Description
None

##### **Spells**
First-Year is a 1st-level spellcaster (Intelligence). Spell save DC 11, +3 to hit with spell attacks.
  - Cantrip (at will): <a href='Mage Hand' class='internal-link'>Mage Hand</a>, <a href='Prestidigitation' class='internal-link'>Prestidigitation</a>
  - 1st level (2 slots): <a href='Detect Magic' class='internal-link'>Detect Magic</a>

```statblock
image: Avymys.jpg
name: First-Year
type: Medium Humanoid, Lawful Good
ac: 11
hp: 32 (6d8+6)
speed: Walk 30 ft, Swim 0 ft, Fly 0 ft, Climb 0 ft
str: 8
dex: 12
con: 13
int: 12
wis: 10
cha: 11
saves:
  - none
skills: none
damage_vulnerabilities: none
damage_resistances: none
damage_immunities: none
condition_immunities: none
senses: none
languages: Common plus any two languages
cr: 1/2
xp: 100
traits:
  - name: "Excited to Be Here."
    desc: "The student has advantage on initiative rolls."
actions:
  - name: "Magic Flare."
    desc: "Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. Hit: 7 (1d12 + 1) force damage."
spells:
  - First-Year is a 1st-level spellcaster (Intelligence). Spell save DC 11, +3 to hit with spell attacks.
  - Cantrip (at will): <a href='Mage Hand' class='internal-link'>Mage Hand</a>, <a href='Prestidigitation' class='internal-link'>Prestidigitation</a>
  - 1st level (2 slots): <a href='Detect Magic' class='internal-link'>Detect Magic</a>
reactions:
  - name: "Beginner’s Luck (2/Day)."
    desc: "When the student fails a saving throw, it can reroll the d20. It must use the new roll."
legendary_actions:
  - none
lair_actions:
  - none
regional_effects:
  - none
```