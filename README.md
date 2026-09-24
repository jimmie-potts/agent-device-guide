# Agent device work guide and BUNNY atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the BUNNY system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide's topic assignments and totals are a dated snapshot, refreshed at
2026-09-24T09:36:35.440241+00:00. The opening lists show current work, newly added
issues, open defects, selected next steps, blockers and later work. They refresh
from public GitHub on page load, with a dated per-repository fallback. Eleven
topic guides retain unique issue ownership; completed evidence is expandable.
The merged-work history was read separately at 2026-09-24T09:07 UTC.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. Links to private source issues, PRs and files require repository
access, while the published reading pages and bundled references work without it.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`b3b243805a80b14437198f1454c6398f77800f62`, delivered by
[Hub PR #236](https://github.com/jimmie-potts/agent-device-hub/pull/236).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `902576a59d110d9c93049d0d337c04ef37c317d70cff1eeba3c135c961b1008a`
- `atlas/manifest.json` SHA-256:
  `44e0596bc81e1b63c313a8369068f440570444a6654c56a453070f81835897f1`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
