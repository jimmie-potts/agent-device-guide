# Agent device work guide and BUNNY atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the BUNNY system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide is a dated snapshot. Its issue backlog was refreshed on
2026-09-23 at 21:15 UTC, and its merged-work history was fetched at 21:15 UTC.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. Links to private source issues, PRs and files require repository
access, while the published reading pages and bundled references work without it.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`b575fbe1e962d1935b0d592a8d40dc1ee9f6799b`, delivered by
[Hub PR #206](https://github.com/jimmie-potts/agent-device-hub/pull/206).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `db35a18e0e3562c8c434453af0b7e48a189971a5e157239e567dc01e4b59d2e4`
- `atlas/manifest.json` SHA-256:
  `44e0596bc81e1b63c313a8369068f440570444a6654c56a453070f81835897f1`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
