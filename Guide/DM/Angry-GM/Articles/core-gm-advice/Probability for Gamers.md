---
lastSync: Mon Apr 27 2026 22:52:52 GMT-0600 (Central Standard Time)
type: dm-advice
source: The Angry GM
category: core-gm-advice
tags:
  - dm-advice
  - angry-gm
  - core-gm-advice
---
# Probability for Dumm… for Gamers

**Source:** [The Angry GM](https://theangrygm.com/probability-for-gamers/)
**Date:** August 31, 2016
**Category:** Random Bulls$&%

---

## Overview

A technical deep-dive into probability math for RPG game masters and designers. Covers how dice mechanics work, how advantage/disadvantage affect outcomes, what happens if you swap d20 for 3d6, and why understanding probability empowers you to tinker under the hood of your game.

---

## Key Concepts

### Basic Probability

Probability = (number of desired outcomes) ÷ (total possible outcomes). Multiply by 100 for a percentage.

- **d6 rolling a 6:** 1/6 = 16.7%
- **d8 rolling 4+:** 5/8 = 62.5%
- Because RPGs use "this number OR HIGHER," probabilities run slightly higher than intuitive guesses. Always count outcomes carefully.

### Expected Value and the Law of Averages

- The **expected value** is the average result over infinity rolls. d6 = 3.5, d8 = 4.5.
- The **law of averages**: the more times you roll, the closer the average approaches the expected value.
- Any individual result is still random. You can roll three 1s in a row despite a 95% hit chance.

### Complements

If you know the chance of something happening, subtract from 100% to get the chance of it NOT happening. Sometimes easier to calculate.

### Weighted Averages

Multiply probability of an outcome by its expected result to get a weighted average. Essential for calculating expected damage per round.

**Example (D&D 5E, 1st level fighter, longsword):**
- +5 to hit vs AC 13 = 65% hit chance
- Average damage per hit: 4.5 (d8) + 3 = 7.5
- Miss (35%): 0 damage. Normal hit (60%): 7.5 damage. Crit (5%): 12 damage.
- **Weighted total: 5.1 damage per round**

### Combining Probabilities

- **Both (AND):** Multiply probabilities.
- **Either (OR):** Add probabilities, then subtract the probability of both (to avoid double-counting).
- **Formula:** P(A or B) = P(A) + P(B) − [P(A) × P(B)]

---

## How Advantage Works

Roll 2d20, keep the best. What's the probability of rolling X+ on die A OR die B?

**Example — need 8+ (65% base):**
> 65% + 65% − (65% × 65%) = 87.75%

Improvement of 22.75% ≈ +4 to +5.

**Key insight:** Advantage/disadvantage have the greatest effect in the middle range (need 8–14). At extremes (need 2 or 19), the effect is minimal.

- Need a 10: Advantage ≈ +5
- Need a 17: Advantage ≈ +3
- Need a 2 or 20: Advantage ≈ negligible

The effect is **non-linear**, unlike flat modifiers which always shift probability by 5% per +1.

---

## d20 vs 3d6

### Linear vs Bell Curve

- **d20:** Every result has 5% chance. Each +1 = exactly +5%. Linear.
- **3d6:** Bell curve. Only 1 way to roll 3 (1,1,1) but 27 ways to roll 10 or 11. Results clump in the middle.

Both have the same average (10.5), but very different spreads.

### Standard Deviation

- **d20:** 5.77 — 68% of rolls fall between 4 and 16
- **3d6:** 2.96 — 68% of rolls fall between 7 and 13

### Implications of 3d6

- Crits on 18 become extremely rare (0.46%). Need 16–18 to maintain ~5% crit rate.
- Modifiers become non-uniform: +1 is worth more in the middle, less at extremes.
- Extreme results are dramatically less likely.

---

## 4d6 Drop Lowest vs 3d6

- **3d6 average:** 10.5, SD 2.96
- **4d6 drop lowest average:** 12.24, SD 2.85

The 4d6 method shifts average up by ~2 and is slightly tighter. Results skew upward asymmetrically — 6 ways to get 18 but only 1 way to get 3.

The standard array (15, 14, 13, 12, 10, 8) closely approximates 4d6-drop-lowest. ~10% chance of doing better, ~5% chance of doing worse.

---

## D&D 5E Design Assumptions

5E appears designed around ~70% success rate for moderate tasks:
- Average DC: 15. Typical PC modifier: +4 to +5.
- Converges on roughly 70% success rate across levels.

---

## Practical Takeaways

1. **Every +1 on a d20 = 5% change.** Simple and linear.
2. **Advantage ≈ +3 to +5** depending on target number, peak in the middle.
3. **Bell curves clump results toward the middle** — modifiers matter more for average tasks.
4. **Weighted averages** let you calculate expected damage, rounds to kill, etc.
5. **Law of averages only kicks in over many rolls.** Individual sessions will be swingy.
6. **Don't go too crazy.** Math is a tool, not a substitute for what feels fun.

**Tool:** [AnyDice](http://anydice.com/) — input any dice combination for probabilities, averages, and standard deviations.

---

*"Part of the reason we LIKE randomness in games is because we like unexpected and crazy results."*
