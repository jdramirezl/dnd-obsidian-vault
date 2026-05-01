# 🎲 D&D 5e Obsidian Vault

Master index for the entire vault. A comprehensive D&D 5e reference built in Obsidian, including player rules, DM resources, monster tactics, adventures, and Spanish-language guides for new players.

## 📚 Core References

| Section | Description | Files |
|---------|-------------|-------|
| 📖 [General Rules](Guide/General%20Rules/) | Player's Handbook + Basic Rules (races, classes, spells, combat, equipment, feats) | ~900 |
| 🐉 [Bestiary](Guide/Bestiary/) | Monster Manual stat blocks organized by name, CR, and type | ~240 |
| 🗺️ [DM Resources](Guide/DM/) | Angry GM, Return of the Lazy DM, The Monsters Know What They're Doing | ~850 |
| 🇲🇽 [Guías para Nuevos Jugadores](Guide/Guias-Nuevos-Jugadores/) | Onboarding en español — reglas, combate, magia, razas | ~20 |

## ⚔️ Adventures

| Adventure | Description |
|-----------|-------------|
| [Lost Mines of Phandelver](Adventures/LostMinesofPhandelvir/) | Complete starter adventure with all 4 parts, maps, and appendices |

## 🧬 Spanish Race Guides

Quick-reference guides in Spanish for new players, covering stats, personality, culture, and roleplay tips:

[Enano](Guide/Guias-Nuevos-Jugadores/Razas/Enano.md) · [Elfo](Guide/Guias-Nuevos-Jugadores/Razas/Elfo.md) · [Mediano](Guide/Guias-Nuevos-Jugadores/Razas/Mediano.md) · [Humano](Guide/Guias-Nuevos-Jugadores/Razas/Humano.md) · [Dracónido](Guide/Guias-Nuevos-Jugadores/Razas/Draconido.md) · [Gnomo](Guide/Guias-Nuevos-Jugadores/Razas/Gnomo.md) · [Semielfo](Guide/Guias-Nuevos-Jugadores/Razas/Semielfo.md) · [Semiorco](Guide/Guias-Nuevos-Jugadores/Razas/Semiorco.md) · [Tiefling](Guide/Guias-Nuevos-Jugadores/Razas/Tiefling.md)

## 🗂️ Structure

```
DND/
├── Adventures/              # Campaign modules
│   └── LostMinesofPhandelvir/
├── Guide/
│   ├── General Rules/       # PHB + Basic Rules
│   │   ├── Introduction/
│   │   ├── Part-1-Creating-a-Character/  (Races, Classes, Backgrounds, Equipment, Feats)
│   │   ├── Part-2-Playing-the-Game/      (Ability Scores, Adventuring, Combat)
│   │   ├── Part-3-Rules-of-Magic/        (Spellcasting, Spell Cards)
│   │   ├── Part-4-Dungeon-Masters-Tools/ (Monsters, Encounters, Magic Items)
│   │   └── Appendices/
│   ├── Bestiary/            # Monster Manual
│   │   ├── By-Name/
│   │   ├── By-CR/
│   │   └── By-Type/
│   ├── DM/                  # DM Resources
│   │   ├── Angry-GM/
│   │   ├── return-of-the-lazy-dungeon-master/
│   │   └── The-Monsters-Know/
│   └── Guias-Nuevos-Jugadores/  # Spanish guides
│       └── Razas/
```

## 📝 Notes

- Built for [Obsidian](https://obsidian.md/) — uses `[[wikilinks]]` internally
- PDFs and large extracted files are gitignored
- Each file has YAML frontmatter with tags for Obsidian graph/search
