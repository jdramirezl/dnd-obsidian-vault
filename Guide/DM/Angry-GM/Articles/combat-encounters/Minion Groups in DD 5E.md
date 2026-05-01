---
title: "More Grist For the Mill: Minion Groups in D&D 5E"
author: The Angry GM
date: 2015-09-09
url: https://theangrygm.com/more-grist-for-the-mill-minion-groups-in-dd-5e/
series: Boss Fights for 5E
tags:
  - angry-gm
  - boss-fights
  - minions
  - action-economy
  - encounter-building
  - combat-encounters
  - 5e-mechanics
  - paragon-system
related_articles:
  - "Return of the Son of the D&D Boss Fight: Now in 5E"
  - "Oh No, More Bosses: Oozes, Slimes, and a Duplicating Wizard"
concepts:
  - minion groups
  - action economy (inverse paragon)
  - phantom XP problem
  - multiattack as damage balancer
  - shared movement pool
  - minion group trait template
---

# More Grist For the Mill: Minion Groups in D&D 5E

## Summary

This article inverts the Paragon system: instead of cramming multiple monsters into one body to make a boss, it smears one monster across four bodies to create minions. A group of four minions shares one turn, one pool of movement, and one set of actions (including multiattack), but each member occupies its own space and tracks its own hit points (1/4 of the base creature's total). This solves the "phantom XP" problem in 5E's encounter math, where large groups of weak monsters cost far more difficulty than the XP they award, and keeps bookkeeping manageable for hordes of 15–20 creatures.

## Key Advice

### The Problem with Hordes in 5E

- 5E's encounter multiplier punishes large groups: 20 CR 1/8 creatures = 500 XP earned but 2,000 XP difficulty.
- The "phantom XP" gap grows worse at higher levels (20 CR 1 creatures = 4,000 XP earned, 16,000 XP difficulty).
- Bounded accuracy keeps low-CR monsters accurate enough to hit, but their damage output doesn't scale.

### Why Not 1 HP Minions (4E Style)?

- 1 HP minions are too fragile — AoE spells become guaranteed kills regardless of save results.
- Any hit-that-deals-damage is a kill, making area spells a no-brainer resource expenditure.
- Condition-imposing effects become 1/4 as effective (only affect one body instead of the whole creature).
- Divvying up real HP preserves interaction with the existing hit point system and avoids weird edge cases with resistance/vulnerability.

### The Minion Group System

Each minion group = 4 members sharing one creature's stats:

| Element | Rule |
|---|---|
| **Hit Points** | Total HP ÷ 4 per member; each tracks separately; damage doesn't spill between members |
| **Initiative** | One roll for the group; one turn per round |
| **Movement** | Total speed shared among all members (e.g., speed 30 = one moves 30, or two move 15 each, etc.) |
| **Actions** | One action per turn; multiattack attacks can be split among members |
| **Reactions** | One reaction between turns; any member can take it |
| **Bonus Actions** | May need rewording to allow group-wide use (see Goblin Nimble Escape) |
| **Conditions** | Each member affected separately |

### Multiattack as Damage Balancer

- Many MM creatures already use multiattack to reach expected damage output for their CR.
- Minion groups use the same trick: give the group multiattack so multiple members can swing per turn.
- At very low CRs, you can't always squeeze in 4 attacks (goblins only get 2).

### Multiple Groups Are Interchangeable

- If you field 5 groups of 4 identical minions (20 total), you don't need to track which minion belongs to which group.
- Any minion can act on any group's turn, as long as total actions per turn aren't exceeded.
- Remove one group from the initiative for every 4 minions killed, regardless of original group membership.

### Naming Convention

Format: **[Collective] of [Species] [Descriptive Noun]**
- Gang of Goblin Minions
- Horde of Zombie Shamblers
- Squad of Hobgoblin Soldiers

### The Minion Group Trait Template

> ***Minion Group.*** The [creature group] is a group of four [members] with identical statistics. Each [member] has its own space and tracks its own hit points separately. Each [member] is affected by conditions separately and constitutes a single target. The [creature group] rolls for initiative and takes one turn per round. During the turn, any or all [members] may move, provided total movement doesn't exceed the group's speed. Any [member] may take the group's action; if entitled to multiple attacks, those may be divided between [members]. The group may take one reaction between turns. If multiple identical groups exist, any member of any group may act on any group's turn provided totals aren't exceeded.

### Example Stat Blocks

- **Gang of Goblin Minions** — CR 1/8, 7 HP each, 2 attacks/turn, group Nimble Escape
- **Horde of Zombie Shamblers** — CR 1/2, 11 HP each, 4 attacks/turn, high damage but low AC
- **Squad of Hobgoblin Soldiers** — CR 1/2, scaled-down Martial Advantage on every hit (always-on, reduced damage)

## Key Takeaways

1. Minion groups are the inverse of Paragon monsters: one creature's stats spread across four bodies.
2. Real HP (not 1 HP) preserves compatibility with the existing 5E hit point system.
3. Shared movement and actions keep the action economy correct while allowing 15–20 creatures on the field.
4. The system eliminates phantom XP — 5 minion groups = 5 creatures for encounter math, not 20.
5. Multiple identical groups are interchangeable; don't bother tracking which minion belongs to which group.
6. AoE spells are naturally more effective against minions (more targets) — this is a feature, not a bug.
