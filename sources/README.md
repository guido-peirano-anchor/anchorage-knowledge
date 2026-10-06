# Sources

| Source | What it is | Snapshot |
|---|---|---|
| Stablecoins Systems Atlas | An interactive map of the stablecoin systems: topology, workflows, journeys, glossary, gaps. https://claude.ai/artifact/FDaQoyAjpACZZudGBw8x9s | `stablecoins-atlas-2026-09-02.json` (generated 2026-09-02, monorepo commit `c743dbd7fe28`). Draft: the facts are still waiting for team review. |

## Reading the atlas snapshot

The JSON has these top-level keys: `systems`, `workflows`, `journeys`, `glossary`, `gaps`, `externals`, `edges`, `environments`, `frontends`, `libraries`.

The best entry points for business readers are `journeys`, which give end-to-end stories, and `systems[].purpose`.
