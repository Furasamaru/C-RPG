# YGGDRASIL RPG — Skeleton Mage Evolution & Stat Mechanics Manual

This document provides a comprehensive guide to the **Skeleton Mage** Heteromorphic evolution tree based on the mechanics of **YGGDRASIL** (*Overlord* universe). It includes stat point growth math, evolution prerequisites, racial abilities, and endgame build strategies.

---

<details>
<summary><h2>⚙️ Core Racial Mechanics & Stat Scaling Rules</h2></summary>

### The 3-Tier Heteromorphic Hierarchy
Heteromorphic races in YGGDRASIL scale across three distinct tiers. Higher-tier racial classes grant higher stat growth multipliers per level and higher individual stat caps.

```
 [ Tier 1: Basic Race ]  ────────► Level Cap: 15  │ Stat Multiplier: +3 Points / Level
          │
          ▼
 [ Tier 2: High Race ]   ────────► Level Cap: 10  │ Stat Multiplier: +5 Points / Level
          │
          ▼
 [ Tier 3: Rare Race ]   ────────► Level Cap: 5   │ Stat Multiplier: +8 Points / Level
```

### Stat Pool Distribution Logic
Racial classes do not allow manual point assignment; instead, stat growth points are automatically distributed across the 9 core stat metrics based on the race's archetype:

* **Skeleton Mage Line Archetype:** Heavily prioritizes **MP**, **Magical Attack**, and **Magical Defense**, while leaving **Physical Attack** and **HP** low.
* **Point Budget Formula:**
  $$\text{Total Base Stats} = \sum (\text{Racial Tier Multiplier} \times \text{Racial Level}) + (1 \times \text{Job Level})$$

</details>

---

<details>
<summary><h2>💀 Tier 1: Skeleton Mage (Basic Race)</h2></summary>

### Overview
The starting Heteromorphic class for players pursuing Undead Arcane Mastery. Skeleton Mages are fragile, fleshless spellcasters clad in simple robes with dark-vision sockets.

* **Class Cap:** Level 15
* **Stat Pool Multiplier:** +3 Points per level (45 Total Points at Level 15)
* **Archetype Allocation:** 33% MP, 27% Mag Atk, 13% Mag Def, 10% Agility, 7% Phy Def/HP, 3% Phy Atk.

### Level 1 Starting Stat Profile (3.0 Total Points)

| Stat Metric | Base Value | Visual Gauge (0 - 100 Scale) |
| :--- | :---: | :--- |
| **HP** | **0.2** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **MP** | **1.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Phy. Atk** | **0.1** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Phy. Def** | **0.2** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Agility** | **0.3** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Mag. Atk** | **0.8** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Mag. Def** | **0.4** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Resistance**| **0.2** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Special** | **0.0** | `[░░░░░░░░░░░░░░░░░░░░]` |

### Level 15 Maxed Skeleton Mage Stat Profile (45.0 Total Points)

| Stat Metric | Base Value | Visual Gauge (0 - 100 Scale) |
| :--- | :---: | :--- |
| **HP** | **3.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **MP** | **15.0** | `[███░░░░░░░░░░░░░░░░░]` |
| **Phy. Atk** | **1.5** | `[░░░░░░░░░░░░░░░░░░░░]` |
| **Phy. Def** | **3.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Agility** | **4.5** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Mag. Atk** | **12.0** | `[██░░░░░░░░░░░░░░░░░░]` |
| **Mag. Def** | **6.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Resistance**| **3.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Special** | **0.0** | `[░░░░░░░░░░░░░░░░░░░░]` |

### Inherent Traits & Passive Abilities
* **Undead Body I:** Immunity to Poison, Sleep, Disease, Paralysis, and Mind Control.
* **Negative Energy Healing:** Healed by Negative Energy / Dark Magic; damaged by Healing spells.
* **Racial Vulnerabilities:** Takes **2.0x Damage** from Bludgeoning physical attacks and Holy/Light magic.
* **Basic Darkvision:** Complete vision in standard dark environments.

</details>

---

<details>
<summary><h2>🔮 Tier 2: Elder Lich (High Race)</h2></summary>

### Overview
An evolved form of the Skeleton Mage possessing higher mental resilience, commanding presence over lesser undead, and amplified spellcasting capacity.

* **Class Cap:** Level 10
* **Stat Pool Multiplier:** +5 Points per level (50 Additional Points at Level 10)
* **Prerequisites:**
    1. `Skeleton Mage` Level 15
    2. Item Catalyst: **Book of the Dead** (Consumable)
    3. Minimum Level 10 in Arcane or Necromancy Job Classes (e.g., `Mage`, `Necromancer`)

### Level 25 Profile (Max Skeleton Mage 15 + Max Elder Lich 10 = 95.0 Base Points)

| Stat Metric | Base Value | Visual Gauge (0 - 100 Scale) |
| :--- | :---: | :--- |
| **HP** | **6.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **MP** | **33.0** | `[██████░░░░░░░░░░░░░░]` |
| **Phy. Atk** | **2.5** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Phy. Def** | **6.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Agility** | **8.5** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Mag. Atk** | **26.0** | `[█████░░░░░░░░░░░░░░░]` |
| **Mag. Def** | **13.0** | `[██░░░░░░░░░░░░░░░░░░]` |
| **Resistance**| **7.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Special** | **3.0** | `[█░░░░░░░░░░░░░░░░░░░]` |

### Key Abilities & Unlocks
* **Flight Magic:** Innate access to passive/active levitation and flight spells.
* **Undead Command:** Ability to summon and permanently control low-to-mid tier undead (Skeletons, Zombies, Wraiths).
* **Tier 3–6 Spell Access:** Drastically lowers the level barrier for high-tier Arcane and Necromancy spells.
* **Despair Aura I:** Passive fear effect causing low-level enemies to suffer minor stat penalties.

</details>

---

<details>
<summary><h2>👑 Tier 3: Overlord (Rare / Epithet Race)</h2></summary>

### Overview
The supreme apex of the Skeleton Mage line. Overlords are highest-tier undead magic casters who have transcended standard system limits, becoming absolute rulers of death.

* **Class Cap:** Level 5
* **Stat Pool Multiplier:** +8 Points per level (40 Additional Points at Level 5)
* **Prerequisites:**
    1. Maxed levels in prerequisites: `Skeleton Mage [15]` and `Elder Lich [10]`
    2. Advanced Job Class prerequisites (e.g., `Necromancer [15]`, `Master Work [10]`)
    3. Achievement/Event: Completion of High-Tier Undead Ascension Quest

### Maxed Racial Stat Summary (30 Racial Levels Total = 135.0 Base Points)

| Stat Metric | Base Value | Visual Gauge (0 - 100 Scale) |
| :--- | :---: | :--- |
| **HP** | **8.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **MP** | **48.0** | `[█████████░░░░░░░░░░░]` |
| **Phy. Atk** | **3.5** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Phy. Def** | **8.0** | `[█░░░░░░░░░░░░░░░░░░░]` |
| **Agility** | **11.5** | `[██░░░░░░░░░░░░░░░░░░]` |
| **Mag. Atk** | **38.0** | `[███████░░░░░░░░░░░░░]` |
| **Mag. Def** | **20.0** | `[████░░░░░░░░░░░░░░░░]` |
| **Resistance**| **10.0** | `[██░░░░░░░░░░░░░░░░░░]` |
| **Special** | **10.0** | `[██░░░░░░░░░░░░░░░░░░]` |

> *Note: When combined with 70 Job Levels and Divine Gear, an Overlord's MP and Mag. Atk regularly exceed **100+**, breaking out of the standard graph.*

### Inherent Overlord Passives & Trump Cards
* **High-Tier Physical Immunity III:** Negates all physical attacks from weapons or enemies below level 60.
* **High-Tier Magic Immunity III:** Negates all spell effects Tier 6 and below.
* **Despair Aura V:** Emits an aura capable of causing instant death to low-level entities or severe stat degradation to equal-level entities.
* **Create High Undead:** Ability to spawn high-tier minion entities (e.g., *Eyeball Corps*, *Grim Reaper Thanatos*) multiple times per day.

### Overlord Specialization Branches
Upon achieving the Overlord class, players select one specialization archetype:

1. **Overlord Wiseman:** Prioritizes spell repertoire size, MP expansion, and meta-magic enhancements (e.g., *Ainz Ooal Gown*).
2. **Overlord Cronos Master:** Prioritizes time manipulation skills, temporal delay, and cooldown manipulation.
3. **Overlord General:** Prioritizes minion buffing, large-scale army command limits, and battlefield tactical auras.

</details>

---

<details>
<summary><h2>📜 Sample Level 100 Endgame Build: Ainz-Style Caster</h2></summary>

Below is a complete Level 100 character allocation combining 30 Racial Levels with 70 Magic Job Levels:

```
================================================================================
                          LEVEL 100 CLASS ALLOCATION
================================================================================
RACIAL CLASSES (30 Levels Total)
  • Skeleton Mage .............. Level 15 / 15  [Basic Race]
  • Elder Lich ................. Level 10 / 10  [High Race]
  • Overlord ................... Level 05 / 05  [Rare Race]

JOB CLASSES (70 Levels Total)
  • Necromancer ................ Level 15 / 15  [Basic Job]
  • Academic Wizard ............ Level 15 / 15  [Basic Job]
  • Master Work ................ Level 10 / 10  [High Job]
  • Ruler of Death ............. Level 10 / 10  [High Job]
  • Eclipse .................... Level 05 / 05  [Rare Job - Special]
  • Mixed Arcane Jobs .......... Level 15 / 15  [Basic/High Jobs]
================================================================================
```

### Key Synergy Notes
* **Eclipse Class Requirements:** Requires maxed `Overlord` and specialization in Necromancy. Unlocks the trump card skill **[The Goal of All Life is Death]**, which bypasses all enemy instant-death immunities after a 12-second delay.

</details>