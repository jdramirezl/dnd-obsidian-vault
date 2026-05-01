---
lastSync: Mon Apr 27 2026 22:52:51 GMT-0600 (Central Standard Time)
type: dm-advice
source: The Angry GM
category: monster-building
tags:
  - dm-advice
  - angry-gm
  - monster-building
---
# Monster Building 201: The D&D Monster Dissection Lab

**Source:** [The Angry GM](https://theangrygm.com/monster-building-201-the-dd-monster-dissection-lab/)
**Date:** October 15, 2015
**Series:** Custom Monster Building 101

---

D&D has a really good mathematical system behind its monsters. But the well-documented process in the DMG is utter crap. The steps are in the wrong order and the important bits are buried. The DMG advises starting with Name, Size, Type, Alignment, then Ability Scores, and THEN thinking about what you're going to do with the monster. **Delineating a process is NOT the same as explaining a system.**

---

## Proficiency Bonus

Every monster has a Proficiency Bonus based on its challenge (DMG 274). Added to:
- Attacks with which the monster is proficient
- Saving Throws with which the monster is proficient
- Skills with which the monster is proficient

Some monsters have **expertise** (double proficiency). Example: the Grell (MM 172) — Stealth +6 with Dex +2 and Prof +2. The extra +2 = double proficiency.

Monsters seem to ALWAYS be proficient with their attacks. If you need a lower attack roll, write a trait to explain it.

---

## Attack Bonus

- **Melee:** Proficiency Bonus + Strength modifier
- **Ranged:** Proficiency Bonus + Dexterity modifier

**Manufactured weapons** follow weapon rules (Finesse, Thrown, etc.). **Natural weapons** — you're inventing a weapon. You can designate a natural weapon as Finesse or Thrown freely. Example: flying snake (MM 322) bite is +6 = Dex +4 + Prof +2, so it's a Finesse weapon.

---

## Damage

**Manufactured weapons:** Damage from weapon table. Bonus = same ability modifier as attack bonus.

**Size affects manufactured weapon damage:**
- Large = double damage dice
- Huge = triple damage dice
- Ability score bonus stays the same

**Natural weapons:** Assign any damage die, but follow size conventions. Always add same ability modifier as attack roll. **Special damage types** (lightning, fire, etc.) don't generally add an ability modifier — purely dice-based.

---

## Saving Throw DC

Formula: `8 + Proficiency Bonus + relevant Ability Modifier`

**Patterns:**
- Physical effects (poison, disease, breath weapons) → **Constitution**
- Magical/mental effects → **Charisma** (less consistent pattern)

---

## Hit Points

Always: some multiple of one die + Constitution modifier. For each "level," roll one hit die and add Con mod.

**Number of dice = number of times you add Con modifier. No exceptions.**

| Size | Hit Die |
|------|---------|
| Tiny | d4 |
| Small | d6 |
| Medium | d8 |
| Large | d10 |
| Huge | d12 |
| Gargantuan | d20 |

### Working Backwards from Target HP

Average die roll = half faces + 0.5 (d4=2.5, d6=3.5, d8=4.5, d10=5.5, d12=6.5, d20=10.5)

**Example:** Small creature, Con +1, target ~85 HP.
- 1d6+1 per level, average 4.5
- 85 ÷ 4.5 ≈ 18 → **HP 81 (18d6+18)**

**Example:** Large creature, Con +3, target 160–175 HP.
- d10+3 per level, average 8.5
- 19 levels = 161, 20 levels = 170
- **HP 161 (19d10+57)** to **HP 170 (20d10+60)**

---

## Armor Class

**Manufactured armor:** Use the AC formula for that armor type.

**Natural armor:** You invent the formula freely. Creatures have EITHER natural armor OR manufactured armor — they never stack. You can also invent manufactured armor types (e.g., Armor Scraps on skeleton MM 272 = AC 11 + Dex).

---

## Saving Throws

Most monsters aren't proficient with any. You can grant up to two without drastic impact. **Design philosophy:** A creature's poor ability score SHOULD be kryptonite. Use proficiencies to emphasize something special, not shore up weaknesses.

---

## Challenge Rating

**Baseline:** CR X = medium difficulty for four X-level PCs.

**Challenge = average of Defensive CR and Offensive CR.**

### Defensive Challenge
1. Find HP on table (DMG 274) → starting Defensive CR
2. Compare AC to expected. Every 2 points above/below → adjust one row

### Offensive Challenge
1. Find average damage/round on table → starting Offensive CR
2. Compare Attack/Save DC to expected. Every 2 points above/below → adjust one row

### Final Challenge
Average the two, round up (or normal rounding).

**Example:** AC 17, HP 66 (6d6+12), Shortbow +5, 6 (1d6+3).
- HP 66 → Def CR 1/2. AC 17 vs expected 13 (+4) → bump 2 → **Def CR 2**
- Damage 6 → Off CR 1/2. Attack +5 vs expected +3 (+2) → bump 1 → **Off CR 1**
- Final: (2+1)/2 = 1.5 → **CR 2**

---

## Effective Stats (Where Challenge Gets Crazy)

The DMG uses "Effective" stats for traits/abilities:
- **Flying** (CR ≤10): +2 Effective AC
- **Resistant to many damage types**: multiply Effective HP (×2, ×1.5, ×1.25)
- **3 Saving Throw proficiencies**: +2 Effective AC
- **5 Saving Throw proficiencies**: +4 Effective AC
- **Various Traits** (DMG 280–281): each lists its effect

**Example — Ceramic Guardian Wolf:** AC 14, HP 22, Bite +5, 6 damage. Resistant to piercing/slashing. Pack Tactics. Aggressive.
- Resistances → double Effective HP → 44
- Pack Tactics → +1 effective attack → +6
- Aggressive → +2 effective damage → 8
- Calculate with: AC 14, HP 44, Attack +6, Damage 8 → Def 1/4, Off 1 → **CR ~1/2**

---

## Damage Output per Round

Include ALL damage sources. Always assume best option. Area attacks hit 2 creatures.

### Averaging Over Three Rounds

For limited abilities, figure damage for first three rounds and average:

**Fire Breath (Recharge 5-6):** 10 area → hits 2 = 20 round 1. Other rounds: bite 5. Total 30/3 = **10/round.**

**Eye Laser (1/day):** 14 round 1. Longsword 7 rounds 2-3. Total 28/3 ≈ **9/round.**

Use the most frequently used Attack/Save DC.

**Key insight:** Damage and HP are where most leveling happens. At Levels 5, 11, 17 — damage doubles. Damage and HP are the primary measurements of level.

---

## Levers and Knobs

- **NO control** over Proficiency Bonus (set by Challenge)
- **LEAST control** over Attack Bonus (Prof + Ability, tweaking Ability affects Damage)
- **Challenge has two components** — Offensive and Defensive — this is central
- **Traits, abilities, movement modes** all affect Challenge through Effective stats

Understanding all levers lets you build any monster at any Challenge confidently, and perform mechanical sleight of hand to match mechanics to flavor consistently.
