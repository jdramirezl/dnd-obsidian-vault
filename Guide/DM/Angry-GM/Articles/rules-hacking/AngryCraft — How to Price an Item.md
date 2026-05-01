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
# AngryCraft — How to Price an Item

**Source:** [The Angry GM – The Great Magic Item Analysis: How to Price an Item](https://theangrygm.com/how-to-price-an-item/)
**Date:** March 25, 2020
**Series:** Crafting a Crafting System / AngryCraft

---

## The Problem

D&D's DMG assigns magic items a rarity and a broad price range, but items within the same rarity vary wildly in power and utility. Comparing a +2 weapon to a marble elephant to boots of levitation is inherently subjective. The AngryCraft system needs specific prices to determine material costs, but Angry refuses to do a subjective item-by-item valuation.

## Five Mechanical Traits of Magic Items

Instead of subjective power analysis, Angry identifies five **objective, mechanical traits** every magic item already has:

1. **Rarity** — Common, Uncommon, Rare, Very Rare, Legendary. Sets the broad price tier and level availability.
2. **Category** — Armor, potions, rings, rods, scrolls, staffs, wands, weapons, wondrous items. Determines form, who can use it, and stacking limits.
3. **Attunement** — Whether the item requires attunement (limits: 3 attuned items max, sometimes class-restricted). Signals the item is powerful enough to need a restriction.
4. **Usage** — How many times the item can be used:
   - **Single-use** — One and done (potions, spell scrolls)
   - **Limited-use** — Multiple uses but finite, no recharge (necklace of fireballs, ring of three wishes, magic ammunition batches)
   - **Charged** — Has charges that recharge periodically; small chance of breaking on last charge (most wands/staffs)
   - **Permanent** — Works forever with no usage limit (+1 weapons, most armor)
5. **Impact** — Minor or Major (hidden in DMG treasure tables A–E vs. F–I; revealed in Xanathar's Guide p.135). Major items change the game more significantly.

## The Key Insight: You Don't Need 144 Prices

A weighted-average system using all five traits would produce ~144 unique price points per rarity. But AngryCraft only needs to know **how many materials** (3–8) an item requires. That means only **Impact × Usage** matters — giving 8 tiers:

| Impact | Usage | Materials Required |
|---|---|---|
| Minor | Single-Use | 3 |
| Minor | Limited-Use | 4 |
| Minor | Charged | 5 |
| Minor | Permanent | 6 |
| Major | Single-Use | 5 |
| Major | Limited-Use | 6 |
| Major | Charged | 7 |
| Major | Permanent | 8 |

## Pricing the Materials

Using Xanathar's revised item values (20% lower than DMG) as the **material cost**, with the DMG's original values as the **total cost** (materials + labor):

| Rarity | Material Cost (per unit) | Total Materials Cost (8 units) | Labor Cost | Total Item Value |
|---|---|---|---|---|
| Common | 10 gp | 80 gp | 20 gp | 100 gp |
| Uncommon | 50 gp | 400 gp | 100 gp | 500 gp |
| Rare | 500 gp | 4,000 gp | 1,000 gp | 5,000 gp |
| Very Rare | 5,000 gp | 40,000 gp | 10,000 gp | 50,000 gp |
| Legendary | 25,000 gp | 200,000 gp | 50,000 gp | 250,000 gp |

- **Material cost** = what the raw ingredients are worth (XGE values)
- **Labor cost** = the 20% premium an NPC craftsman charges (difference between DMG and XGE values)
- A PC with the right proficiency skips the labor cost

## Why Not Use Sane Magical Item Prices?

Same reasons as the Pregame article: SMIP prices often fall outside DMG ranges, some legendary items are priced under 500 gp, and the list assumes a savvy GM gatekeeping purchases. AngryCraft must work for any table, including ones that let players freely buy/sell, so it must stay within the DMG's existing balance assumptions.

## What This Enables

- Any GM can look at a magic item, classify it by Impact and Usage, and instantly know how many materials it requires and what those materials cost
- Material values are clean, round numbers that divide evenly
- The system is self-consistent with the DMG's treasure tables — materials replace some gold/gems/art in hoards at equivalent value
- Consumables (potions, scrolls) naturally cost less because they need fewer materials (3 instead of 8)
