---
source: "https://theangrygm.com/theorycrafting-an-unsummary/"
author: The Angry GM
date: 2019-03-04
tags:
  - game-theory
  - system-design
  - crafting
  - design-methodology
---

# Theorycrafting an Unsummary

## The Design Technique: Unsummarizing

Once you can summarize how a system will play out, write that summary down. Then **question every single word and phrase** — expand, define, and challenge each piece. This reveals the questions you need to answer and the systems you need to build.

### Starting Summary
> The players will acquire raw materials during their adventures. Outside of play, they can combine those raw materials into mundane or magical objects.

### The Unsummary Process

Walk through each phrase:

1. **"Raw materials"** — What are they? Consumable items with rarity, type, and optional quality descriptors. (Already defined.)
2. **"During their adventures"** — How? Don't assume it's only monster harvesting. Must be incidental to adventure, not a distraction from it.
3. **"Can they acquire materials outside adventures?"** — Yes. You don't want a fire sword blocked by lack of common iron. But this must be limited and controlled.
4. **"Outside of play"** — No stopping the game for one player to do paperwork. System must work without GM adjudication. But "outside of play" doesn't mean unconditional — crafting should require fictional downtime.
5. **"Can they craft during play?"** — Yes, for problem-solving (e.g., making fire potions when you discover trolls). But must be limited to prevent optimization-paralysis mid-session.
6. **"Mundane or magical objects"** — Massive design space. What's the procedure? Prerequisites? Can they make everything?
7. **The unstated clause: "…to use during their adventures"** — Must prevent for-profit crafting. No magic item shops.

## Scope Expansion: The Conversion Problem

The unsummary process revealed the system is bigger than just crafting:

- **Unwanted materials**: What if the party finds materials no one can use? Same problem as finding magic plate armor when no one wears heavy armor.
- **Conversion needed**: Players must be able to convert unwanted items/materials into wanted ones (sell, break down, trade).
- **Non-crafters**: Can a party without a craftsman still benefit? Yes — pay an NPC craftsman, buy/sell materials.

### Expanded Summary
> The players will acquire consumable raw materials incidentally during their adventures, in limited quantities outside of their adventures, or through the conversion of items or other raw materials. These raw materials can be converted into mundane or magical objects for use by the players. Such conversion normally takes place outside the game but can take place during the game in a limited fashion. Nothing in this system can distract from the core gameplay engagement of adventuring, though it can provide the occasional motivation for adventure. And this system cannot allow the players to unbalance the game by acquiring more magical items than they would be able to obtain under the core rules, nor to earn a profit.

## The GP Medium of Exchange

**GP (capital)** is a game concept — a measure of relative value, not just coins. Every item in the game has a GP value. The existing system already handles conversion:

- Treasure → Equipment: perfectly efficient (1:1)
- Equipment → Coins: inefficient (sell at half value)
- Magic items → Coins: very inefficient or impossible (DMG 129-130)

The crafting system hooks into this by setting GP values on raw materials and finished goods, then controlling the **efficiency of conversion** to prevent profit.

## Design Checklist (from the Unsummary)

Things to figure out:
- [x] What are raw materials? (Consumable; rarity + type + quality)
- [ ] How are they acquired during adventures?
- [ ] How are they acquired outside adventures?
- [ ] How are items converted to raw materials?
- [ ] How are raw materials converted to finished items?

Constraints:
- Materials mostly acquired during play
- Conversion mostly outside play
- Limits on finding materials outside play
- Limits on crafting during play
- Cannot distract from gameplay
- Cannot generate profit

## Meta-Lesson: Design Process

> Stating the problem and analyzing what the solution has to look like is the hardest part of design.

The unsummary technique prevents:
- Missing important requirements
- Missing opportunities for better design
- Baking in unexamined assumptions

What started as a crafting system is actually a **revamp of the entire treasure and magical item system** in D&D.
