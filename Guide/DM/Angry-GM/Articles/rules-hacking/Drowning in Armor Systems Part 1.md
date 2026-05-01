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
# Drowning in Armor Systems — Part 1

**Source:** [The Angry GM – Drowning in Armor Systems (Part 1)](https://theangrygm.com/drowning-in-armor-systems-part-1/)
**Date:** January 17, 2018
**Topic:** Redesigning the 5E armor table — analysis, baselines, and a rank-based upgrade system

---

## Core Idea

The 5E armor table offers no meaningful choices, no upgrade path, and no way to unify mundane and magical equipment. Starting from a practical problem (armor + swimming in a seafaring campaign), Angry reverse-engineers the design principles behind armor and builds a ranked, extensible system from scratch.

## The Problem with 5E Armor

### No Real Choices
- Light armor: everyone buys Studded Leather (AC 12 + Dex, no penalty). Done.
- Medium armor: Scale Mail (AC 14, Stealth disadvantage) or Chain Shirt (AC 13, no penalty). Done by level 1.
- Heavy armor: Plate (AC 18). Done by level 5.
- The Dexterity modifier mechanic *looks* like a choice driver but is really just a math problem.

### No Upgrade Path
- Once you have your best armor, you never think about equipment again (unless you're a fighter/paladin saving for Plate).
- Money becomes worthless — there's nothing to spend it on.
- Magic items are a separate, disconnected system entirely in the GM's hands. Players have zero agency.

### The Magic Item Problem
- Boring +1/+2/+3 armor is mechanically identical to better mundane armor — there's no reason they need to be "magical."
- Interesting magic items (fire resistance, etc.) get lumped with boring numerical bonuses on the same rarity scale.
- GMs either over-give or under-give magic items because there's no coherent framework.

## The Design Process

### Step 1: Identify Properties
For a seafaring campaign, armor needs to interact with more than just Stealth:
- **AC** (with Dex modifier rules by weight class)
- **Stealth** — disadvantage on Dexterity (Stealth) checks
- **Athletics/Acrobatics** — disadvantage on physical skill checks
- **Swimming** — disadvantage on swim checks, or makes swimming impossible
- **Cuttable** — can be cut off with an action (for emergency water situations)
- **Layerable** — can be worn over/under another suit

### Step 2: Establish Baselines (Rank 0)
Determine what starting armor looks like for each weight class:

| Type | AC | Key Tradeoff |
|---|---|---|
| Light (stealthy) | 11 + Dex | No penalties |
| Light (protective) | 12 + Dex | Disadvantage on Stealth |
| Medium (stealthy) | 13 + Dex (max 2) | No penalties |
| Medium (protective) | 14 + Dex (max 2) | Disadvantage on Stealth |
| Heavy | 16 | Str 13, disadvantage on Stealth/Athletics/Acrobatics, no swimming |

The core tradeoff: **1 point of AC ≈ 1 negative trait** (approximately).

### Step 3: Create Variants via Trait Trading
- Remove a negative trait → reduce AC by 1 (armor is "equivalent" but different)
- Add a negative trait → increase AC by 1 (or make it cheaper)
- This creates armor that isn't strictly better or worse — just *different*

### Step 4: Build Ranks
- **Rank 0** = starting/mundane armor
- **Rank 1** = +1 AC equivalent (≈ magic armor +1)
- **Rank 2** = +2 AC equivalent
- **Rank 3** = +3 AC equivalent

Each rank is just the baseline with AC increased by 1. But **don't fill every slot** — leave gaps and holes to create interesting upgrade decisions.

## Key Design Principles

### Gaps Make Things Interesting
- If every rank has every option, players just do math and pick the best. No choice.
- Missing options force players to decide: upgrade now with a tradeoff, or save for the perfect piece?
- Example: Medium armor above Rank 1 all impede Stealth → stealthy rangers might trade *down* to magical Light armor

### Some Options Should Be Strictly Worse (or Better)
- A few "crappy" options are fine — they might be cheaper or available earlier
- A few options that are just flat-out better than alternatives at the same rank are also fine
- Perfect balance is the enemy of interesting choices — **fuzzy comparisons drive real decisions**

### Trust Your Gut Over the Math
- The formula (1 AC ≈ 1 trait) is a guideline, not a law
- D&D's numbers aren't precise enough for perfect balance
- Leave "wobble" in the system — if players can calculate the optimal choice, it's not a choice

### Names Come Last
- Design the stats first, then invent names and descriptions to match
- Starting from "what should chain mail do?" is backwards — start from "what stats create an interesting option?"

## What's Still Missing

The table works but is **kludge** — too many specific columns (Stealth, Athletics, Acrobatics, Swimming) that are hard to record and don't generalize. Part 2 will clean this up using a keyword system borrowed from weapons, making the table simpler *and* more extensible.
