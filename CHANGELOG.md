# Changelog

## [1.0.0] - 2026-11-15

Initial release. Evaluate, compare and plan Warframe riven mods.

### Features
- **Per-stat grades** — each value's position in the weapon-wide range
- **Riven score (0–100)** — DPS gain normalized to godroll, with labels (Godroll / Great / Usable / Roll for kuva / Trash)
- **Weapon insights** — stat ranking, least harmful curses, godroll, community picks
- **Cycle & splice simulator** — kuva costs (doubled with trait lock), Riven Splicer recipes (U44.1)
- **Kuva planner** — exact odds, expected cycles/kuva, 50%/90% percentiles, Monte Carlo verified

### Tech
- React 18 + TypeScript + Vite 6
- Vitest for core logic
- Data from WFCD `warframe-items`