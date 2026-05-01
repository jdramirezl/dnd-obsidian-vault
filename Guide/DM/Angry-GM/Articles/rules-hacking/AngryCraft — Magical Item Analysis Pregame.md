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
# AngryCraft — Magical Item Analysis Pregame

**Source:** [The Angry GM – The Great Magical Item Analysis Pregame Show](https://theangrygm.com/magical-item-analysis-pregame/)
**Date:** March 4, 2020
**Series:** Crafting a Crafting System / AngryCraft

---

## Overview

This article lays out the **project plan** for the AngryCraft system and explains why the design must work backward from D&D's existing magic items rather than forward from arbitrary material definitions.

## The Five Design Components

From the play experience description, Angry isolates five major pieces of work:

1. **Define the materials** — Rarities, forms (metal, plant, fluid, etc.), traits (fire, cold, healing, etc.), and values
2. **Assign mechanics to existing items** — Every DMG item needs a formula, required proficiency, commission price, salvage output, and whether the formula is common knowledge
3. **Materials placement** — How GMs put materials into adventures: treasure hoards, monster corpses, resource nodes, foraging during wilderness exploration. Requires rewriting treasure tables.
4. **Gathering rules** — How players salvage, forage, and collect materials; how the GM adjudicates those actions
5. **Ancillary downtime activities** — Researching material locations, researching new formulae, experimenting with materials

## The Core Constraint: Don't Break D&D

AngryCraft is a **modular overlay**, not a system overhaul. It must:

- Work for any GM at any table (casual users, inexperienced GMs, heavily homebrewed games)
- Not remove, rewrite, or change existing rules
- Not let players acquire more magic items than the DMG already allows
- Treat existing treasure tables and item costs as sacrosanct

**Key principle:** Materials are just another form of treasure. As long as materials convert to magic items at the same rate as gold converts to magic items (via the DMG's optional buying/crafting rules), balance is preserved.

## Why Not Use Sane Magical Item Prices?

The community-made SMIP list reprices items based on in-world economic logic. It's good work, but:

- Many prices fall outside DMG ranges (some legendary items < 500 gp)
- It assumes a savvy GM gatekeeping purchases
- AngryCraft needs to work even if players freely buy/sell with minimal GM oversight
- AngryCraft's goal isn't to fix the economy — it's to add a crafting layer without breaking existing balance

## The Pricing Problem

DMG price ranges per rarity increase by a factor of 10 at each tier:

| Rarity | DMG Range |
|---|---|
| Common | 50–100 gp |
| Uncommon | 101–500 gp |
| Rare | 501–5,000 gp |
| Very Rare | 5,001–50,000 gp |
| Legendary | 50,001–500,000 gp |

The 10× spread within each rarity is too wide for crafting recipes (cheapest item = 3 materials, most expensive = 30 materials — unmanageable). Angry tightens the low end to roughly 1/3 of the high end:

| Rarity | Tightened Range |
|---|---|
| Common | 50–100 gp |
| Uncommon | 150–500 gp |
| Rare | 1,500–5,000 gp |
| Very Rare | 15,000–50,000 gp |
| Legendary | 150,000–500,000 gp |

## Material Traits Must Be Derived, Not Invented

Materials need **values**, **rarities**, and **traits** (magical qualities like fire, cold, healing). None of these can be arbitrary:

- **Values** must match magic item costs so materials-to-item conversion stays balanced with gold-to-item conversion
- **Rarities** must align with monster CR (so the right materials come from level-appropriate monsters) and treasure table tiers
- **Traits** must cover every magical effect in the game AND every quality a monster might possess, in a manageable, intuitive list (~10–20 traits)

Starting point for traits: D&D's 10 damage types (acid, cold, fire, force, lightning, necrotic, poison, psychic, radiant, thunder) + healing = 11. That leaves room for ~9 more to cover the 8 schools of magic and other concepts.

## The Recipe Puzzle

AngryCraft's play experience involves a **logical optimization puzzle**: the player tries to meet a formula's requirements using the fewest, least-valuable materials from their inventory. Formulae should require **3–8 materials** (absolute ceiling: 10). At ~5 materials average and common items worth ~100 gp, common materials are worth ~20 gp per unit.

## Bottom Line

Everything must be derived from the existing magic item list — work backward from items to materials, not forward from materials to items. The master magic item spreadsheet is the keystone of the entire system.
