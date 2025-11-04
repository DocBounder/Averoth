---
name: Arcane Basilisk Construct
classification: Homebrew
size: Large
type: Construct
alignment: Neutral
armor_class: 17 (Natural Armor)
hit_points: 85
hit_die: d10
speed:
  Walk: 20 ft
  Swim: 0 ft
  Fly: 0 ft
strength: 19
dexterity: 8
constitution: 17
intelligence: 3
wisdom: 12
charisma: 5
proficiency_bonus: 3
saving_throws: Strength,Constitution
skills: Perception,Athletics
damage_vulnerabilities:
  - None
damage_resistances:
  - Fire
  - Poision
damage_immunities:
  - Necrotic
condition_immunities:
  - Charmed
  - Poisoned
  - Petrified
senses: Darkvision
challenge_rating: "5"
xp: "1800"
created: 2025-03-29T16:39
updated: 2025-03-29T18:14
---
# `= this.name`
_`= this.size` `= this.type`, `= this.alignment`_

>[!info] *Description* 
>*Originally devised by a renegade Oriq researcher within Strixhaven, the Arcane Basilisk Construct combines the fearsome petrifying traits of a basilisk with specialized runic engineering designed to harness volatile Snarl magic. Iron braces and bands of etched runes secure segments of its basalt‐like exoskeleton, channeling arcane currents through the creature’s body. When threatened or roused by fresh spellcasting, this monstrous experiment roars to life, eager to siphon and unleash destructive magic. Though mindless and unaligned, it follows its Oriq master’s commands with unwavering obedience—an attempt by the cult to craft an unstoppable magical war machine.*

---
**Armor Class:** `= this.armor_class`  
**Hit Points:** `= this.hit_points` (10`= this.hit_die`+30)  
**Speed:** Walk `= this.speed.Walk`, Swim `= this.speed.Swim`, Fly `= this.speed.Fly`

---
### **Abilities**
| STR | DEX | CON | INT | WIS | CHA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| `= this.strength` (`= floor((this.strength - 10) / 2)`) | `= this.dexterity` (`= floor((this.dexterity - 10) / 2)`) | `= this.constitution` (`= floor((this.constitution - 10) / 2)`) | `= this.intelligence` (`= floor((this.intelligence - 10) / 2)`) | `= this.wisdom` (`= floor((this.wisdom - 10) / 2)`) | `= this.charisma` (`= floor((this.charisma - 10) / 2)`) |

---
**Proficiency Bonus:** +`= this.proficiency_bonus`  
**Saving Throws:** `= this.saving_throws`  
**Skills:** `= this.skills`  
**Damage Vulnerabilities:** `= this.damage_vulnerabilities`  
**Damage Resistances:** `= this.damage_resistances`  
**Damage Immunities:** `= this.damage_immunities`  
**Condition Immunities:** `= this.condition_immunities`  
**Senses:** `= this.senses`  
**Challenge Rating:** `= this.challenge_rating`
**XP:** 1800

---
##### **Traits**
Arcane Devourer
Whenever a creature within 30 feet of the basilisk casts a spell of 1st level or higher, the basilisk regains 5 hit points. If the basilisk is already at its hit point maximum, it gains advantage on its next attack roll before the end of its next turn.

Siege Monster
Drawing inspiration from Gravios’s sheer size and destructive power, the basilisk deals double damage to objects and structures.

Heavy Plating
The construct’s stone‐like plating grants it resistance to bludgeoning, piercing, and slashing damage from nonmagical attacks. (If you worry this might be too punishing for your party, change it to one damage type or remove it entirely.)

Immutable Form
The construct is immune to any spell or effect that would alter its form.

Magic-Powered Motion
While within 100 feet of an active Snarl (or another large magical source), the basilisk’s speed increases to 30 ft., and it has advantage on Dexterity saving throws.

Vulnerable Underbelly. If a creature scores a critical hit or finds a way to strike the basilisk’s underbelly (via a special tactic or after it’s knocked prone), it loses its damage resistances until the end of its next turn. This rewards creative play and references how Gravios is weaker on its underside.

---
##### **Actions**
---
**Multiattack**. The basilisk makes two attacks: one with its bite and one with its tail slam.

**Bite**. Melee Weapon Attack: +7 to hit, reach 5 ft., one target.
Hit: 14 (2d8 + 5) piercing damage.

**Tail Slam**. Melee Weapon Attack: +7 to hit, reach 10 ft., one target.
Hit: 13 (2d6 + 6) bludgeoning damage, and the target must succeed on a DC 14 Strength saving throw or be knocked prone.

**Petrifying Gas** (Recharge 6)
Inspired by both a basilisk’s petrification and Gravios’s gas attacks: The basilisk spews a 15‐foot cone of noxious stone‐infused gas. Each creature in that area must make a DC 13 Constitution saving throw. On a failed save, the creature is Restrained as its body begins to harden. A restrained creature repeats the saving throw at the end of its next turn, becoming Petrified for 1 minute on a failure. On a success, the effect ends. (A greater restoration or similar magic can end the petrification early.)

(If you want a lighter effect, you could have it deal some damage and impose disadvantage on Attack rolls instead of petrifying outright.)

**Heat Beam** (Recharge 5–6)
Channeling the Gravios’s signature laser: The basilisk unleashes a surge of arcane heat in a 30‐foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw, taking 22 (4d10) fire damage on a failed save, or half as much on a success. This beam ignites flammable objects in the area that aren’t being worn or carried.

##### **Reactions**
---
**Basalt Shell**
Trigger: The basilisk is hit by an attack that deals slashing, piercing, or bludgeoning damage.
Effect (Reaction): The basilisk’s basalt‐like plating momentarily hardens. It reduces the triggering damage by 6 (the creature’s proficiency bonus + its Constitution modifier, for example). If this reduces the damage to 0, the basilisk takes no damage and shatters the weapon on impact unless it’s a magical weapon.

**Steam Vent**
Trigger: A creature moves within 5 feet of the basilisk or ends its turn there.
Effect (Reaction): Superheated gas blasts from vents along the basilisk’s shoulders. The creature must succeed on a DC 13 Dexterity saving throw or take 1d8 fire damage and be pushed 5 feet away (or 10 feet on a failure of 5 or more).

##### **Legendary Actions**
**Arcane Overload** (1/Day). When the basilisk is reduced to half its hit points (42 or fewer), it regains 10 hit points and immediately recharges Heat Beam or Petrifying Gas (its choice). This simulates Gravios’s enrage mechanic and keeps the party on their toes.

**Legendary Resistance** (1/Day). You could grant it a single instance of Legendary Resistance to survive a crucial save—especially if the party has powerful spell combos.
## Description
A hulking, four‐legged fusion of stone plating and arcane engineering, the Arcane Basilisk Construct resembles a massive reptilian beast with thick volcanic armor. Instead of natural scales, each plate is carved from magically infused rock, reinforced with steel rivets and pulsating runes. Its eyes glow with molten‐purple radiance, betraying the swirling Snarl energy within. Between labored breaths, vents along its neck and shoulders exhale superheated steam or noxious petrifying gas. In battle, it capitalizes on its formidable bulk, smashing foes aside with a huge, spiked tail and unleashing bursts of raw, scalding power from its maw—all while greedily feeding on any arcane forces around it.