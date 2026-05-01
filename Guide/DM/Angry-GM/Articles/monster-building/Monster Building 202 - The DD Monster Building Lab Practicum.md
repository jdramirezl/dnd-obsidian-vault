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
# Monster Building 202: The D&D Monster Building Lab Practicum

**Source:** [The Angry GM](https://theangrygm.com/monster-building-202/)
**Date:** October 23, 2015
**Series:** Custom Monster Building 101

---

In 4E, monsters had **roles** (defensive, ambush, damage-dealer, support) that told the GM how to use them and cued designers on what to build. Every monster was built to do something specific. 5E dropped this, but **5E has everything you need to build monsters to specific combat roles and tactics** if you know how.

---

## What the Hell is this Monster For?

The backstory/fluff is secondary. You don't HAVE TO have a compelling concept. But you absolutely DO need to know what you're using this monster for. Three things:

1. **What Challenge Rating?** Not approximately — the exact final CR.
2. **How does the monster fight?** Aggressive? Defensive? Fast? Group fighter? Loner?
3. **What role does it fill?** Skirmisher, ranged attacker, protector, etc.

---

## Step 1: Challenge Rating

Challenge is made up of **Offensive CR** and **Defensive CR**. The final CR is their average. This is EVERYTHING.

A CR 4 monster could be:
- Off 4 / Def 4 (balanced)
- Off 5 / Def 3 (aggressive damage dealer, easy to hit)
- Off 3 / Def 5 (tanky, hard to bring down)
- Even Off 6 / Def 2 (extreme glass cannon)

A small variation goes a long way. Keep within one or two steps. Too divergent gets messy — high offense turns PCs into chunky salsa.

---

## Step 2: Traits (and Other Things)

Every creature needs at least one cool Trait. This is where you deviate from the DMG's process. **Figure out Traits early because they affect Challenge.**

Check DMG 280–281 for sample Traits. Each changes some stat for CR calculation purposes. Example: Nimble Escape effectively increases AC and attack by 4 points each → +2 Defensive CR and +2 Offensive CR.

**If you give a creature Nimble Escape and want it to be CR 2, you need to LEAVE ROOM for that +4 in the stats.**

### How Many Traits?

- No more than 2–3 Traits generally
- The more Traits, the simpler each should be
- Even complicated Traits shouldn't exceed ~10 lines of text

### Racial Traits vs Member Traits

**Racial Traits** = shared by all members of a race (e.g., every goblin has Nimble Escape). Creates consistency — players learn what to expect.

**Member Traits** = specific to a variant (e.g., the Darter's Scurry ability). Defines the tactical role.

If a racial trait doesn't apply to a variant (e.g., Bugbear Brute on a spellcaster), invent a similar trait that keeps the same flavor but works for the role.

### Example: Lemurian Racial Traits

> ***Cat-Like Acrobatics.*** Lemurians do not suffer damage from falls of 20 feet. If a Lemurian falls more than 20 feet, it suffers damage as normal but does not land prone.

> ***Standing Leap.*** Long jump up to 20 feet, high jump up to 10 feet, with or without a running start.

> ***Spider Climb.*** Can climb difficult surfaces, including upside down on ceilings, without ability checks.

**Lemurian Darter Member Trait:**
> ***Scurry.*** Can take the Dash or Disengage action as a bonus action on each of its turns.

**Lemurian Behemoth Member Trait:**
> ***Pounce.*** If the behemoth moves at least 20 feet straight toward a creature and hits with a Kick attack, target must succeed on a DC XX Strength save or be knocked prone. If prone, behemoth can make one Bite attack as a bonus action.

### How Traits Affect Challenge

- **Pounce:** Assume one extra attack every 3 rounds → increase effective damage by 33%
- **Spider Climb / Standing Leap:** No CR impact (DMG 281)
- **Scurry (Dash half):** Same as Aggressive → +2 effective damage/round
- **Scurry (Disengage half):** Same as Flyby → no CR impact
- **Combined racial traits on a ranged creature:** Effectively creates a flying ranged creature → +2 Effective AC

**Key insight:** Sometimes things are more than the sum of their parts. The Lemurian Darter's traits are fine individually, but a ranged Lemurian Pelter with the same racial traits is effectively a flying ranged creature.

### Spellcasting

Spellcasting is a giant pile of extra traits/actions/stats. Think through each spell's impact. Focus on the most damaging and most defensive spells — those have the biggest effect. Spells of the same level are roughly balanced against each other.

---

## Step 3: Picking Your Numbers

Five numbers determine challenge: **HP, AC, Damage, Attack, Save DC.**

HP determines Defensive CR, modified by AC. Damage determines Offensive CR, modified by Attack/Save DC.

### Lemurian Darter (CR 1/2)

Target: Def 1/4, Off 1 (averages to ~1/2).

**Defense:** 7–35 HP with AC 15 → Def CR 1/4.
- HP 14 (4d6), Con 10 (+0)
- AC 15 (natural armor) — needs Dex +3 minimum so hide is only worth 12 + Dex

**Offense:** 9–14 damage with +3 attack expected. But Dex +3 + Prof +2 = +5 attack (2 too high). Trade: bump damage down one row → target 6–8 damage.
- Scurry adds +2 effective damage → actual damage needs to be 4–6
- 1d6+3 = 6 average damage, +5 to hit ✓

**Final Darter:**
- AC 15, HP 14 (4d6), Dex 16 (+3), Con 10 (+0)
- Attack +5, 6 (1d6+3) damage

### Lemurian Behemoth (CR 4)

Target: Def 3, Off 5.

**Offense first** (where trouble lives). Need 33–38 damage/round with +6 attack.
- Prof +2, so Str must be +4 (Str 19)
- Can't use Multiattack + Pounce together (they interact badly)
- Solution: Slam (fists) for Multiattack, Kick for Pounce, Bite for bonus

**Damage split over 3 rounds** (target ~100 total):
- Round 1 (Pounce): Kick 30 (4d12+4) + Bite 11 (2d6+4) = ~40
- Rounds 2-3 (Multiattack): 2× Slam 15 (2d10+4) = 30 each
- Total: 40+30+30 = 100. Average: ~33/round ✓

**Dice choice matters:** d12 for kick (most dangerous), d10 for fists (baseline), d6 for bite (weakest). Number of dice signals power — 4 dice for the kick nova vs 2 dice for normal attacks.

**Defense:** Target 116–130 HP with AC 11.
- Lemurian hide = 12 + Dex. Dex -1 → AC 11
- Con +2, Large (d10). Target ~130: 130 ÷ 8.5 ≈ 15 → actually 17d10+34 = 127

**Final Behemoth:**
- AC 11, HP 127 (17d10+34), Str 19 (+4), Dex 9 (-1), Con 15 (+2)
- Multiattack: Two Slams. Slam +6, 15 (2d10+4)
- Kick +6, 30 (4d12+4). Bite +6, 11 (2d6+4)
- Pounce DC 14 Strength save (8 + 2 prof + 4 Str)

---

## Step 4: Finish the Damn Monster

You're done with everything that affects Challenge. Fill in remaining stats for flavor — Intelligence, Wisdom, Charisma, senses, languages, skills. Leaf through the MM for similar creatures as reference.

---

## Making Friends: Variant Creatures

Start with "the skirmisher" — the most generic version. Keep it balanced, note its tactical trait. Then copy-paste and fiddle to create variants.

### Lemurian Pelter (Ranged Variant, CR 1/2)

Replace Scurry with Sneak Attack-like abilities. Racial traits make it effectively a flying ranged creature → +2 Effective AC.

- Defensive CR bumps to 1/2 (from the effective AC increase)
- Must keep Offensive CR at exactly 1 to maintain CR 1/2 overall
- Damage: 1d4+3 (rock) + 1d6 (sneak attack) = 8/round
- Dropped the first-round crit effect to keep damage in range

### Lemurian Protector (Defensive Variant, CR 1/2)

Shield (+2 AC) + Leadership ability + Shield Interposition reaction.

- AC 17 with shield, HP 14 → Def CR 1/2
- Punches with shield: +3 attack, 4 (1d6+1) damage → Off CR 1/4
- Average ≈ CR 1/2. Gave extra HP (up to 35) for comfort.

---

## Key Process Summary

1. **Set Challenge Rating** (with Offensive/Defensive split)
2. **Design Traits** (figure CR impact, leave room in stats)
3. **Pick Numbers** (HP, AC, Damage, Attack — working backwards from CR targets)
4. **Finish flavor** (ability scores, senses, skills, languages)

Think in terms of connections: Off/Def CR, AC↔HP tradeoffs, Attack↔Damage dependencies, and how Traits ripple through everything.
