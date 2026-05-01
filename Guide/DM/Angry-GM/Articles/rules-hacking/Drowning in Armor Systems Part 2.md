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
# Drowning in Armor Systems — Part 2

**Source:** [The Angry GM – Drowning in Armor Systems (Part 2)](https://theangrygm.com/drowning-in-armor-systems-part-2/)
**Date:** February 7, 2018
**Topic:** Cleaning up the armor table with keywords — elegance, extensibility, and unifying mundane + magical items

---

## Core Idea

The Part 1 armor table worked but was ugly kludge — too many columns for specific skills. The fix: replace all those columns with a **keyword system** (like weapons have), making the table simpler to read, easier to record, and infinitely extensible. This also allows mundane and magical armor to exist on the same scale.

## Design Concepts

### Complexity vs. Depth
- **Complexity** = how much a player must learn/remember/track (bad — steeper learning curve)
- **Depth** = how many different ways the game can go based on decisions (good — keeps the game interesting)
- Goal: maximize depth while minimizing complexity

### Elegance
A mechanic is **elegant** when it adds depth without adding much complexity. Example: the d20 Core Mechanic — one rule (roll d20 + modifier vs. DC) handles attacks, saves, skills, and everything else.

### Extensibility
A mechanic is **extensible** when new stuff can be added to it easily. The d20 mechanic is extensible: add a new ability score, new modifiers, require multiple rolls, assign meaning to the margin of success, etc.

### Loaded Mechanics
When a mechanic is both elegant AND extensible = **loaded**. Like a fully-loaded pizza. You get maximum value from the design work. The keyword system is a loaded mechanic.

## The Keyword Solution

### The Problem
The Part 1 table had separate columns for Stealth, Athletics, Acrobatics, Swimming, Cuttable, Layerable. That's six extra columns — hard to record, hard to extend, and campaign-specific.

### The Fix: Impeding (Skill)
Replace ALL skill-penalty columns with one keyword:

> **Impeding (Skill).** While wearing this armor, you have disadvantage on ability checks related to the listed skill.

So "Disadvantage on Stealth" becomes `Impeding (Stealth)`. "Disadvantage on Athletics and Acrobatics" becomes `Impeding (Athletics), Impeding (Acrobatics)`.

### Other Keywords

> **Cuttable.** The armor is held together with cords or straps. As an action, use a knife or light slashing weapon to cut it off. Cannot be worn again until repaired.

> **Layer (Under/Over).** You can wear a Layer (Under) suit simultaneously with a Layer (Over) suit. You benefit from the AC of only one, but suffer/benefit from the traits of both.

> **Leaden.** You cannot swim while wearing this armor and sink in water. If you have a swim speed, it is reduced to 0.

### Result
The table goes from 6+ extra columns down to **one column: Properties** — a list of keywords. Cleaner, easier to record on a character sheet, and infinitely extensible.

## Extending the System

### Campaign-Specific Keywords
The keyword system isn't locked to seafaring. Any campaign can invent its own:
- **Courtly intrigue:** `Imposing` (bonus to Intimidation), `Uncouth` (penalty to Persuasion)
- **Lawful setting:** `Conspicuous` (draws attention from authorities)
- **Cold climate:** `Insulating` (resistance to cold damage)

### Unifying Mundane and Magical Armor
The rank system + keywords means there's **no mechanical difference** between:
- Trading from Bronze Plate (AC 16) → Steel Plate (AC 17) → Adamantine Plate (AC 18)
- Trading from Bronze Plate → Bronze Plate +1 → Bronze Plate +2

This allows magical properties to be just more keywords:
- `Magic` — the item is magical (detectable, etc.)
- `Exceptional (+1)` — +1 to AC beyond the base
- `Enhancing (Stealth)` — advantage on Stealth checks
- `Resistant (Fire)` — resistance to fire damage
- `Vulnerable (Lightning)` — vulnerability to lightning damage
- `Attunement` — requires attunement to function
- `Masterwork` — superior craftsmanship

### What This Enables
- Players can **buy upgrades** on a clear progression instead of waiting for GM handouts
- GMs can **compare** mundane and magical armor on the same scale
- **Crafting systems** have a natural framework — add/remove keywords
- **Low-magic campaigns** work fine — players just buy higher-rank mundane armor instead of finding magic items
- **High-magic campaigns** also work — magic keywords layer on top of the same system
- A +1 Elven Gambeson with Enhancing (Stealth) is directly comparable to a mundane manta-skin jerkin of the same rank

## Pricing Guidelines (Rough)

| Rank | Availability | Approximate Cost |
|---|---|---|
| 0 | Starting equipment | Under 50 gp |
| 1 | 5th level+ | ~500–2,000 gp |
| 2 | 11th level+ | ~10,000–20,000 gp |
| 3 | 17th level+ | ~100,000+ gp |

Wealth progression per level (from DMG treasure tables, per party):
- Levels 1–2: ~375 gp/level
- Level 3: ~750 gp/level
- Level 4: ~1,100 gp/level
- Levels 5–10: ~13,700 gp/level
- Levels 11–16: ~73,000 gp/level
- Levels 17+: ~675,000 gp/level

## Key Takeaways

- **Keywords > columns** — self-contained rule chunks are more elegant and extensible than dedicated table columns
- **Loaded mechanics** (elegant + extensible) pay dividends far beyond the original design problem
- **Unify mundane and magical items** on the same scale — boring +1 bonuses become mundane upgrades; magic items become the *interesting* stuff
- **The character sheet matters** — if a mechanic can't be easily recorded, it will be forgotten
- A "Clumsy" keyword (disadvantage on all Str/Dex checks) could replace Athletics, Acrobatics, AND Stealth penalties in a single word for non-seafaring campaigns
