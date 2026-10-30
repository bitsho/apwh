# AP World History — Source Archive

This repository collects the recoverable source artifacts from the AP World History projects developed in prior ChatGPT work sessions.

## Repository layout

- `apps/chronos-timeline/archive/2026-08-09-timeline-game.html` — earlier standalone timeline-ordering game snapshot.
- `apps/chronos-causal/index.html` — CHRONOS v26 causal-investigation module snapshot (2026-08-14).
- `apps/histography/index.html` — AP World Histography V3 bilingual interactive timeline snapshot (2026-09-07).
- `docs/CHRONOS-PRD.md` — product requirements archive covering the broader CHRONOS platform, account flows, analytics, timeline game, and causal investigation.
- `docs/histography/project-config.example.json` — Histography course configuration.
- `docs/source-inventory.md` — provenance and recovery notes.

## Important source-status note

The HTML files above are independently recovered source snapshots. They are kept in separate directories because they represent different iterations and modules.

The CHRONOS PRD describes a wider integrated product, including the homepage, account/authentication flows, personal analytics, and a 400-event timeline game. The complete live Sites wrapper and its backend/database implementation were not present as standalone source files in the recovered project artifacts. The repository therefore preserves the available implementation snapshots and documentation without pretending that the snapshots alone reproduce every hosted integration.

## Running the standalone HTML snapshots

Open the relevant HTML file directly in a modern browser. Some features retrieve Wikipedia summaries/images or load external libraries at runtime and therefore require an internet connection.

## Source-of-truth guidance

For future development, use the current explicit product requirements and verify the intended module before replacing an archived snapshot. Do not merge the three HTML snapshots into one page without reconciling their different data models and application scopes.
