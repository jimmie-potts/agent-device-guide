# Agent device work guide and BUNNY atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the BUNNY system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide's topic assignments and totals are a dated snapshot, refreshed at
2026-09-24T01:48:03.867879+00:00. The opening lists show current work, newly added
issues, open defects, selected next steps, blockers and later work. They refresh
from public GitHub on page load, with a dated per-repository fallback. Eleven
topic guides retain unique issue ownership; completed evidence is expandable.
The separately dated merged-work history remains unchanged.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. Links to private source issues, PRs and files require repository
access, while the published reading pages and bundled references work without it.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`ddeecd8a4da9d6fc57c9f0506ff36157389bbfd6`, delivered by
[Hub PR #221](https://github.com/jimmie-potts/agent-device-hub/pull/221).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `f1afeaf4f29b66bb2bbbce3c1afde80a827492f14f39d46248cb3e7e4a9efdcc`
- `atlas/manifest.json` SHA-256:
  `44e0596bc81e1b63c313a8369068f440570444a6654c56a453070f81835897f1`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
