---
lastSync: Mon Apr 27 2026 22:52:51 GMT-0600 (Central Standard Time)
type: dm-advice
source: The Angry GM
category: rules-hacking
tags:
  - dm-advice
  - angry-gm
  - rules-hacking
---
# F CR, There's a Better Way (Part 2)

**Source:** [The Angry GM – F$&% CR, There's a Better Way (Part 2)](https://theangrygm.com/f-cr-theres-a-better-way-part-2/)
**Date:** October 28, 2019
**Series:** Rules Hacking / Encounter & Monster Building

---

## The Ideal Encounter Building System

The best encounters pit a group of heroes against a group of foes in **roughly equal numbers** at **roughly equal power**. But the statistical treadmill sucks — players need to sometimes feel advantaged and sometimes disadvantaged, tied directly to advancement.

## Seven Tiers of Advancement

Instead of balancing encounters to exact PC level, balance to the **middle level of a tier**. Each tier spans 3 levels, creating a natural difficulty wobble:

| Tier | Levels | Balance To | Feel |
|---|---|---|---|
| **Apprentice** | 1–2 | 1 | Fragile starter tier |
| **Journeyman** | 3–5 | 4 | 3rd = hard, 4th = balanced, 5th = easy (power jump) |
| **Adventurer** | 6–8 | 7 | 6th = hard, 7th = balanced, 8th = easy |
| **Veteran** | 9–11 | 10 | 9th = hard, 10th = balanced, 11th = easy (power jump) |
| **Champion** | 12–14 | 13 | 12th = hard, 13th = balanced, 14th = easy |
| **Heroic** | 15–17 | 16 | 15th = hard, 16th = balanced, 17th = easy (power jump) |
| **Legendary** | 18–20 | 19 | 18th = hard, 19th = balanced, 20th = easy |

**Key insight:** Power jumps (levels 5, 11, 17) should be the **last** level in their tier — the "easy" level — so players feel their new power immediately. Then the next tier ratchets difficulty back up.

## Encounter Slots and Monster Organization

Every encounter has **3–5 slots** for monsters. Different monster types fill different numbers of slots:

| Organization | Slot Cost | Ratio to PCs | Examples |
|---|---|---|---|
| **Solo** | 4 slots | 1 vs party | Dragons, beholders, liches |
| **Pair** | 2 slots each | ~2 vs party | Witch + ogre, Ornstein & Smough |
| **Group** | 1 slot each | ~equal to party | Orcs, wolves, hobgoblins |
| **Gang** | ½ slot each | ~2× party | Goblins, cultists, thugs |
| **Mob** | ¼ slot each | ~4× party | Giant rats, zombies, spiders |

**Mixing and matching:** You can swap monsters using slot equivalences. Replace one Group orc with two Gang goblins, or replace two Group orcs with one Pair ogre. This makes encounter assembly fast and flexible.

## Custom Monster Building Table

Every monster is defined by **Tier** + **Organization** + stat quality ratings. The five stats are:

- **AC** — armor class
- **HP** — hit points
- **Attack** — attack bonus
- **Save DC** — save difficulty
- **Damage** — average damage per round (over 3 rounds)

Each stat is rated **Good**, **Average**, or **Poor**. Attack and Save DC overlap (use the better one).

### Threat Level

Sum the quality points (Good = +1, Average = 0, Poor = −1):

| Threat | Points | Notes |
|---|---|---|
| Low | −3 to −2 | Insubstantial for average players |
| Medium | −1 to +1 | Best default |
| High | +2 to +3 | Dangerous |

Angry provides a master table (available as PDF) that gives exact target numbers for every combination of Tier × Organization × Quality.

### Traits and Special Abilities

- If a trait meaningfully impacts effective HP, AC, attack, save DC, or damage → count it as **+1 Threat** and adjust accordingly
- Resistances/immunities or flight at low tiers → **halve HP** (per DMG guidance)
- For damage calculation: assume area attacks hit 2 targets, ongoing damage is taken once before save, melee auras hit 2 characters per round

### Design by Organization

- **Solo** monsters need ways to stay dynamic, avoid stun-lock, and hold their own alone
- **Group** monsters need ways to work together and synergize
- **Gang/Mob** monsters should be simple — single attack, passive traits, easy to run in bulk

## Math Behind the Table

The non-obvious adjustment: as monster group size increases, you can't just divide solo HP and damage evenly. Parties focus fire, reducing monster attacks as they kill individuals. To compensate:

- Larger groups get **more total damage output** (~200% of equivalent solo)
- Larger groups get **more total HP** (~150% of equivalent solo)

This prevents the first-round spike problem while ensuring groups remain threatening throughout the fight.

## Key Takeaways

- **Tier + Organization** = the two-word descriptor that tells you everything about how to use a monster in encounters
- The system is deliberately fuzzy — 3–5 slots, not exactly 4; the tier covers 3 levels, not 1
- You'll need to tweak MM monsters or build custom ones — cross out AC/HP/Att/Dmg and write in new values
- [PDF of the master table](https://theangrygm.com/wp-content/uploads/2019/10/Monster-Stats-by-Tier.pdf)
