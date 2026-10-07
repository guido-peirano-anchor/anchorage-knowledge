# Anchorage Knowledge

A knowledge base on Anchorage's stablecoin business, built one small concept at a time. It starts with business basics and goes deeper toward operations and systems.

Start at the [glossary](glossary.md), which lists every concept.

## How it is organized

- **One concept per file** in `concepts/`, named by its id (`mint.md`, `reserves.md`). A concept file is short: a one-line definition in bold, why it matters, how it works at Anchorage, open questions, and related concepts.
- **Each file starts with frontmatter:**
  ```yaml
  id: mint                      # same as the file name
  title: Mint (issue)
  layer: business               # business | operations | systems
  related: [burn, issuer]       # sideways links to other concept ids
  implemented_by: [mintburn]    # optional: the system that does it (systems layer)
  sources: [industry, atlas]
  ```
- **Links in the text** are relative Markdown links (`[burn](burn.md)`), so they work on GitHub.
- **The glossary is an index, not content.** Add one line for each new concept.

## Provenance tags

Each claim says where it came from:

- `[atlas]`: the [Stablecoins Systems Atlas](sources/README.md). It is a draft generated from the monorepo on 2026-09-02 and not yet reviewed by the team.
- `[industry]`: general stablecoin or regulatory knowledge, not specific to Anchorage.
- `[verify]`: not yet confirmed. It is also listed in that file's open questions.
