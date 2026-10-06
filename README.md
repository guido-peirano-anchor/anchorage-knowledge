# Anchorage Knowledge

A layered knowledge base on Anchorage's stablecoin business. Each layer starts from the business and goes one level closer to the systems:

| Layer | Folder | Question it answers |
|---|---|---|
| 1 | `01-business/` | What is the business, who are the parties, and how does value move? |
| 2 | `02-operations/` *(not started)* | Who does what day to day: approvals, reserves, reconciliation, incidents. |
| 3 | `03-systems/` *(not started)* | Which services implement it and how they talk to each other. |
| 4 | `04-deep-dives/` *(not started)* | Workflows, security model, failure modes. |

Start at [01-business/01-fiat-backed-stablecoin-issuance.md](01-business/01-fiat-backed-stablecoin-issuance.md).

## Conventions

- **One topic per file.** The number prefix sets the reading order inside a layer.
- **Every claim has a provenance tag:**
  - `[atlas]`: from the Stablecoins Systems Atlas snapshot in `sources/`. This is what the code showed on 2026-09-02, and it is a draft that the team has not reviewed yet.
  - `[industry]`: general stablecoin or regulatory knowledge, not specific to Anchorage.
  - `[verify]`: plausible but not confirmed. Each one appears in that page's open questions.
- **Business language first.** A system name (for example `mintburn`) appears only to point to the layer where it is explained.
- The [glossary](glossary.md) uses business definitions. Engineering terms live in the atlas glossary until layer 3 exists.

## Sources

See [sources/README.md](sources/README.md).
