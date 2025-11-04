---
name: Thornshade, Spirit of the Wildedge
classification: Homebrew
size: Small
type: Fey
alignment: Chaotic Neutral
armor_class: 14 (None)
hit_points: 102
hit_die: 19d6+38
speed:
  Walk: 30 ft
  Climb: 0 ft
  Swim: 0 ft
  Fly: 30 ft
strength: 10
dexterity: 10
constitution: 14
intelligence: 14
wisdom: 18
charisma: 18
initiative: 0
passive_perception: 14
proficiency_bonus: 2
saving_throws:
  - Dexterity
  - Wisdom
  - Charisma
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
languages: Celestial, Sylvan
challenge_rating: "3"
xp: 700
monster_image: None
created: 2025-03-26T02:27
updated: 2025-05-30T01:53
---

# `= this.name`
_`= this.size` `= this.type`, `= this.alignment`_

>[!info] *Description*
>*None*

**Armor Class:** `= this.armor_class`
**Hit Points:** `= this.hit_points` (`dice: 19d6+38`)
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
Paragon Power (1/round)At the end of another creature’s turn, Thornshade may either: 

Take an action (e. g., a third attack or retreat)

Repeat a saving throw against an ongoing effect 

Opportunist (Controller Feature)May make 1 opportunity attack per round. Gains advantage on the attack if the target is marked or Disoriented.

Dream-Bound (Trigger)If a PC mentions the dream aloud: 

Gains +2 AC until the end of its next turn 

Whispers a line of truth tied to a marked character 

Death BurstWhen reduced to 0 HP, Thornshade dissolves into spores. Each creature within 10 ft. must make a DC 15 Wisdom save or glimpse a future where they fail profoundly.

##### **Actions**
Multiattack (2 attacks) 

Thornshade makes two Dreamclaw or Spirit Thorns attacks. 

Dreamclaw (Melee Spell Attack)+6 to hit, 5 ft. range, 1 creatureHit: `dice: 1d10+4` psychic damage. If the target is marked (divine brand), they must succeed a DC 15 Wisdom save or suffer Disorientation (disadvantage on their next attack or saving throw).

Spirit Thorns (Ranged Spell Attack)+6 to hit, 60 ft. range, 1 targetHit: `dice: 2d8+3` necrotic damage. If the target is concentrating, they must make a DC 15 Constitution save or lose concentration.

Tether to the Root (Recharge 5–6)Thornshade targets one creature that failed a save this round. The target sees a vision of a failed Vigil and takes `dice: 3d6` psychic damage. On a failed DC 15 Wisdom save, they are Stunned until the end of their next turn.

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
name: Thornshade, Spirit of the Wildedge
type: Small Fey, Chaotic Neutral
ac: 14
hp: 102 (19d6+38)
speed: Walk 30 ft, Swim 0 ft, Fly 30 ft, Climb 0 ft
str: 10
dex: 10
con: 14
int: 14
wis: 18
cha: 18
saves:
  - dexterity: +2
  - wisdom: +6
  - charisma: +6
skills: none
damage_vulnerabilities: none
damage_resistances: none
damage_immunities: none
condition_immunities: none
senses: none
languages: Celestial, Sylvan
cr: 3
xp: 700
traits:
  - name: "Paragon Power (1/round)At the end of another creature’s turn, Thornshade may either:"
    desc: ""
  - name: "Take an action (e."
    desc: "g., a third attack or retreat)"
  - name: "Repeat a saving throw against an ongoing effect"
    desc: ""
  - name: "Opportunist (Controller Feature)May make 1 opportunity attack per round."
    desc: "Gains advantage on the attack if the target is marked or Disoriented."
  - name: "Dream-Bound (Trigger)If a PC mentions the dream aloud:"
    desc: ""
  - name: "Gains +2 AC until the end of its next turn"
    desc: ""
  - name: "Whispers a line of truth tied to a marked character"
    desc: ""
  - name: "Death BurstWhen reduced to 0 HP, Thornshade dissolves into spores."
    desc: "Each creature within 10 ft. must make a DC 15 Wisdom save or glimpse a future where they fail profoundly."
actions:
  - name: "Multiattack (2 attacks)"
    desc: ""
  - name: "Thornshade makes two Dreamclaw or Spirit Thorns attacks."
    desc: ""
  - name: "Dreamclaw (Melee Spell Attack)+6 to hit, 5 ft."
    desc: "range, 1 creatureHit: 1d10+4 psychic damage. If the target is marked (divine brand), they must succeed a DC 15 Wisdom save or suffer Disorientation (disadvantage on their next attack or saving throw)."
  - name: "Spirit Thorns (Ranged Spell Attack)+6 to hit, 60 ft."
    desc: "range, 1 targetHit: 2d8+3 necrotic damage. If the target is concentrating, they must make a DC 15 Constitution save or lose concentration."
  - name: "Tether to the Root (Recharge 5–6)Thornshade targets one creature that failed a save this round."
    desc: "The target sees a vision of a failed Vigil and takes 3d6 psychic damage. On a failed DC 15 Wisdom save, they are Stunned until the end of their next turn."

reactions:
  - none
legendary_actions:
  - none
lair_actions:
  - none
regional_effects:
  - none
```