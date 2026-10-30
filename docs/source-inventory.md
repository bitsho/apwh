# APWH source inventory and recovery status

Last checked: 2026-10-30

## Transferred to this repository

| Repository path | Original artifact | Original date | Notes |
|---|---|---:|---|
| `apps/chronos-timeline/archive/2026-08-09-timeline-game.html` | `de2fbc43-d8c9-4513-9abb-1d7f82404cce.html` | 2026-08-09 | Standalone timeline-ordering game snapshot. |
| `docs/CHRONOS-PRD.md` | `CHRONOS_AP世界史时间线游戏_PRD.md` | 2026-08-13 | Product requirements for the broader CHRONOS product. |
| `docs/histography/project-config.example.json` | `project-config.example.json` | 2026-09-16 | APWH Histography course configuration. |

## Located, but not transferred

| Original artifact | Original date | Size | Identified contents | Transfer status |
|---|---:|---:|---|---|
| `CHRONOS_v26_lobby_sorted_by_unit(1).html` | 2026-08-14 | 6,086,060 bytes | CHRONOS v26 causal-investigation module; 50-case lobby snapshot. | The Library search index exposes code excerpts, but full-file read/materialization is currently unavailable. |
| `APWH_Histography_V3_BILINGUAL_FINAL.html` | 2026-09-07 | 20,082,849 bytes | Bilingual 300-event interactive timeline; region/theme dimension switch; Concise, Classic and Cinema modes; three palettes. | The Library search index exposes code excerpts, but full-file read/materialization is currently unavailable. |
| `4ed3874e-fdba-4d70-97c2-36f2fc624c09.html` | 2026-09-07 | 20,049,893 bytes | Earlier AP World Histography HTML snapshot. | Same export limitation. |

## Scope and version distinctions

- The CHRONOS PRD describes a broader integrated platform: homepage, guest/account flows, personal analytics, timeline sorting and causal investigation. It records a 400-event timeline question bank and difficulty pools of 50/100/200/300/400.
- The APWH Histography V3 configuration targets 300 events and defines bilingual EN/ZH, region as the default grouping dimension, Concise/Classic/Cinema modes, and three palettes.
- These are distinct project generations/modules. They have been kept separate in the inventory to avoid silently treating them as one identical build.
- The older Vercel `apwh-games` / HistoTrivia deployment was not imported because it was not verified as the source of the requested Sites project.

## Reproduction status

The repository currently contains the recovered timeline-game snapshot and the project documentation/configuration listed above. It does **not** yet constitute a complete export of the latest hosted Sites project. The latest CHRONOS v26 and Histography V3 HTML source files, plus the live site's integrated navigation/account/analytics/backend implementation, still need a complete source export before the current hosted product can be reproduced from this repository.
