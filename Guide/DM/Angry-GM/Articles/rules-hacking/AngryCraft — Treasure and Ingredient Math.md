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
# More Accounting for Magical Items — AngryCraft Treasure & Ingredient Math

**Source:** [The Angry GM – More Accounting for Magical Items](https://theangrygm.com/more-accounting-for-magical-items/)
**Date:** April 17, 2019
**Series:** Hacking Rules / Crafting System (AngryCraft)

---

## Project Goals (Recap)

> Players acquire consumable raw materials (ingredients) incidentally during adventures, in limited quantities outside adventures, or through conversion. These can be converted into mundane or magical objects. Conversion normally happens outside the game. Nothing in this system distracts from core adventuring gameplay. The system cannot let players acquire more magical items than the core rules assume, nor earn a profit.

## Ingredient Classification

Every ingredient has three properties:

1. **Rarity:** Common, Uncommon, Rare, Very Rare, Legendary
2. **Type:** Metal, Precious Metal, Wood, Herb, Hide, Bone, Fluid, Mineral, Gem, Essence
3. **Trait** (optional): A magical property (e.g., fiery, healing, necrotic, reality-warping) — list TBD

**GP** (capital letters) = the abstract worth/conversion factor of items and ingredients. Roughly equal to in-game gold piece price, but not always (e.g., a longsword is worth 15 GP but sells for 7 gp 5 sp).

## Key Findings from RAW Treasure Analysis

### Treasure Progression by Tier

| Tier | Levels | Treasure per Level | Best Magic Item Cost | Ratio |
|---|---|---|---|---|
| 1 | 1–2 | ~500 GP | 500 GP (Common) | ~1:1 |
| 2 | 3–10 | ~5,000 GP | 5,000 GP (Uncommon/Rare) | ~1:1 |
| 3 | 11–16 | ~50,000 GP | 50,000 GP (Very Rare) | ~1:1 |
| 4 | 17–20 | ~500,000 GP | 500,000 GP (Legendary) | ~1:1 |

**Pattern:** Each rarity jump = 10× value increase. Treasure progression follows in lockstep. A party pooling all gold can afford exactly **one** best-rarity magic item per level. Over 20 levels, that's ~20 extra items if they buy/craft instead of spending gold on anything else.

### XP Progression Rates

Three distinct speeds exist in the game:

- **Levels 1–2:** Race through them (barely any treasure time)
- **Levels 3–10:** Slower progression — the sweet spot where 55% of game time is spent on 40% of levels
- **Levels 11–20:** Steady rate (10 encounters/level, 2 hoards/level)

Any crafting system **must** work well in the 3–10 sweet spot.

## Where Ingredients Come From

### 1. Creature Harvest (Individual Treasure Replacement)
Every defeated creature can potentially yield ingredients instead of pocket change. A wolf has a pelt; skeletons are made of bone. This replaces the awkward fiction of wolves carrying 10 GP in coins.

- **Assumption:** On average, each creature yields **1 ingredient**.
- Ingredient rarity matches creature CR tier (CR 4–8 → Uncommon, etc.).
- Creature type determines ingredient type (Beasts → Hide/Bone, etc.).
- **Humanoids yield no ingredients** (thin hides, brittle bones — and to avoid a system that supports skinning sentient races).

### 2. Placed Treasure (Hoard Replacement)
Ingredients found in the environment — ingots in a storeroom, herb growths, mineral veins. Replaces the fiction of random gold chests in vermin caves.

- **Assumption:** ~3 ingredients per treasure hoard.

### 3. Salvage (Equipment Breakdown)
Looted equipment (swords, armor) can be broken down into base ingredients. Also allows magic items to be deconstructed.

- **Assumption:** Any item salvages into **1 ingredient unit** (~25% of its GP value).

## Recipe Framework

### Ingredient Counts per Item

| Item Complexity | Ingredients Required |
|---|---|
| Simple mundane item (e.g., shortsword) | 3 (can be 3× same type) |
| Consumable magic item | 3–4 |
| Standard magic item | 5–7 |
| Complex/powerful magic item | 8–10 |

- **Minimum for any magic item:** 5 ingredients
- **Maximum for any item:** 10 ingredients
- **Max distinct types per recipe:** 3–5 (to keep complexity manageable)

### Projected Item Yields (Pure Crafting World)

If all treasure were ingredients and all ingredients went to crafting:

| Ingredients per Item | Total Items over 20 Levels |
|---|---|
| 3 | 198 |
| 5 | 119 |
| 7 | 85 |
| 10 | 60 |

The base game assumes ~100 found items + ~20 purchasable. The crafting-only numbers bracket this range, confirming the systems can coexist.

### The Tradeoff Ratio

Removing **1 magic item** from treasure tables creates room for enough ingredients to craft **2 magic items** (in the perfect case). Real-world efficiency will be 50–75% of perfect due to ingredient mismatches, selling, and waste.

## Design Constraints & Decisions

- **Harvesting mechanics** are still TBD — tension between requiring skill checks (adds character skill) vs. using treasure tables (easier for GMs, works for published adventures).
- **Corpse quality is variable** — mange, combat damage, disease, age, and field harvesting conditions all justify why not every creature yields usable material.
- **Encumbrance** is a real concern — ingredients are physical objects with weight.
- **Tool proficiencies** should matter — this is a golden opportunity to make Woodcarver's Tools and similar proficiencies actually useful.
- **Recipes should be intuitive** — players should be able to guess reasonable recipes, not memorize arbitrary lists.
