---
name: Leaf, Spirit of the Forest's Edge
classification: Homebrew
size: Medium
type: Fey
alignment: Neutral
armor_class: 11 (None)
hit_points: 76
hit_die: 12d8+24
speed:
  Walk: 40 ft
  Climb: 20 ft
  Swim: 0 ft
  Fly: 0 ft
strength: 10
dexterity: 18
constitution: 14
intelligence: 10
wisdom: 18
charisma: 14
initiative: 4
passive_perception: 14
proficiency_bonus: 2
saving_throws:
  - Dexterity
  - Wisdom
  - Charisma
skills:
  - Perception
damage_vulnerabilities:
  - Fire
damage_resistances:
  - None
damage_immunities:
  - None
condition_immunities:
  - Charmed
senses:
  - None
languages: Sylvan but cannot speak
challenge_rating: "3"
xp: 700
monster_image: None
created: 2025-03-26T02:27
updated: 2025-05-30T01:48
---

# `= this.name`
_`= this.size` `= this.type`, `= this.alignment`_

>[!info] *Description*
>*None*

**Armor Class:** `= this.armor_class`
**Hit Points:** `= this.hit_points` (`dice: 12d8+24`)
**Speed:** Walk `= this.speed.Walk`, Climb `= this.speed.Climb`, Swim `= this.speed.Swim`, Fly `= this.speed.Fly`

### **Abilities**
| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `= this.strength` (`= floor((this.strength - 10) / 2)`) | `= this.dexterity` (`= floor((this.dexterity - 10) / 2)`) | `= this.constitution` (`= floor((this.constitution - 10) / 2)`) | `= this.intelligence` (`= floor((this.intelligence - 10) / 2)`) | `= this.wisdom` (`= floor((this.wisdom - 10) / 2)`) | `= this.charisma` (`= floor((this.charisma - 10) / 2)`)|

**Initiative:** `= this.initiative`
**Passive Perception:** `= this.passive_perception`
**Proficiency Bonus:** +`= this.proficiency_bonus`
**Saving Throws:** Dexterity, Wisdom, Charisma
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
Evasive Form (Skirmisher Feature)Leaf can take the Disengage action as a bonus action each round. 

Paragon Power (1/round)At the end of another creature's turn, Leaf may either: 

Take a single action (e. g., another Flicker Claw)

Or repeat a saving throw vs. an ongoing effect

Spirit Instinct (Trigger)If Leaf sees Tamar or a marked divine symbol, it hesitates. First attack against that PC has disadvantage and Leaf whispers:

"You were. .. mine once."

Twisted Loyalty (Optional Trigger)If Thornshade dies, Leaf makes a DC 15 Wisdom save: 

On success: Leaf flees into the fog, confused. 

On fail: Enraged, it fights to the death. 

##### **Actions**
Multiattack (2 attacks) 

Leaf makes two Flicker Claw or Vine Snare attacks. 

Flicker Claw (Melee Weapon Attack)+7 to hit, reach 5 ft. , one creature.Hit: `dice: 1d8+4` slashing damage. Target must make a DC 15 Dex save or suffer Disoriented Movement (movement speed halved until end of next turn).

Vine Snare (Ranged, Recharge 5–6)+6 to hit, range 30 ft. Hit: `dice: 2d6+3` bludgeoning. Target must succeed a DC 15 Strength save or be Restrained (save ends).

Tanglestep (1/round, Bonus Action)Leaf teleports 15 feet to an unoccupied space it can see and gains advantage on its next attack. This movement does not provoke opportunity attacks.

##### **Reactions**
None

##### **Legendary Actions**
None

##### **Lair Actions**
None

##### **Regional Effects**
None

## Description
None

```statblock
image: 
name: Leaf, Spirit of the Forest's Edge
type: Medium Fey, Neutral
ac: 11
hp: 76 (12d8+24)
speed: Walk 40 ft, Swim 0 ft, Fly 0 ft, Climb 20 ft
str: 10
dex: 18
con: 14
int: 10
wis: 18
cha: 14
saves:
  - dexterity: +6
  - wisdom: +6
  - charisma: +4
skills: Perception
damage_vulnerabilities: Fire
damage_resistances: none
damage_immunities: none
condition_immunities: Charmed
senses: none
languages: Sylvan but cannot speak
cr: 3
xp: 700
traits:
  - name: "Evasive Form (Skirmisher Feature)Leaf can take the Disengage action as a bonus action each round."
    desc: ""
  - name: "Paragon Power (1/round)At the end of another creature's turn, Leaf may either:"
    desc: ""
  - name: "Take a single action (e."
    desc: "g., another Flicker Claw)"
  - name: "Or repeat a saving throw vs."
    desc: "an ongoing effect"
  - name: "Spirit Instinct (Trigger)If Leaf sees Tamar or a marked divine symbol, it hesitates."
    desc: "First attack against that PC has disadvantage and Leaf whispers:"
  - name: "\"You were."
    desc: ".. mine once.\""
  - name: "Twisted Loyalty (Optional Trigger)If Thornshade dies, Leaf makes a DC 15 Wisdom save:"
    desc: ""
  - name: "On success: Leaf flees into the fog, confused."
    desc: ""
  - name: "On fail: Enraged, it fights to the death."
    desc: ""
actions:
  - name: "Multiattack (2 attacks)"
    desc: ""
  - name: "Leaf makes two Flicker Claw or Vine Snare attacks."
    desc: ""
  - name: "Flicker Claw (Melee Weapon Attack)+7 to hit, reach 5 ft."
    desc: ", one creature.Hit: 1d8+4 slashing damage. Target must make a DC 15 Dex save or suffer Disoriented Movement (movement speed halved until end of next turn)."
  - name: "Vine Snare (Ranged, Recharge 5–6)+6 to hit, range 30 ft."
    desc: "Hit: 2d6+3 bludgeoning. Target must succeed a DC 15 Strength save or be Restrained (save ends)."
  - name: "Tanglestep (1/round, Bonus Action)Leaf teleports 15 feet to an unoccupied space it can see and gains advantage on its next attack."
    desc: "This movement does not provoke opportunity attacks."

reactions:
  - none
legendary_actions:
  - none
lair_actions:
  - none
regional_effects:
  - none
```