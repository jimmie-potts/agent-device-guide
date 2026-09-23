# Agent device work guide and BUNNY atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the BUNNY system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the private
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide is a dated snapshot. Its issue backlog was refreshed on
2026-09-23 at 19:04 UTC, and its merged-work history was fetched at 19:02 UTC.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. Links to private source issues, PRs and files require repository
access, while the published reading pages and bundled references work without it.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`1aeafb699843075b0928824cfe787ad1ac2f0c14`, delivered by
[Hub PR #188](https://github.com/jimmie-potts/agent-device-hub/pull/188).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `278b5e2d460c44eddd3b229d9997ac91b2f37edb13200f5fd740e0aa5d4ac5b1`
- `atlas/manifest.json` SHA-256:
  `44e0596bc81e1b63c313a8369068f440570444a6654c56a453070f81835897f1`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
