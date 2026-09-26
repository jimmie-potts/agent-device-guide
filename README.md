# Agent device work guide and B.U.N.N.Y. atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the B.U.N.N.Y. system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide's topic assignments and totals are a dated snapshot, refreshed at
2026-09-26T00:32:30.698878+00:00. The opening lists show current work, newly added
issues, open defects, selected next steps, blockers and later work. They refresh
from public GitHub on page load, with a dated per-repository fallback. Twelve
topic guides retain unique issue ownership; completed evidence is expandable.
The merged-work history was read in the same second as the snapshot.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. The three source repositories are public, so issue, PR and source
links open without a GitHub sign-in.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`5d68ab47a68512c10e391f218fae7fc4d376071b`, delivered by
[Hub PR #394](https://github.com/jimmie-potts/agent-device-hub/pull/394), which
re-renders the architecture viewers for ADR 0007 (B.U.N.N.Y. is the shell),
ADR 0008 (runtime hosting) and the retired Windows Nanoleaf runtime, re-pins
the guide views to current main and updates the system map the atlas embeds.
It follows [Hub PR #393](https://github.com/jimmie-potts/agent-device-hub/pull/393), which
adds a twelfth topic guide, Steam Deck, for the seven stories filed on
2026-09-25, places the stories filed since the previous snapshot on the roadmap
and refreshes the snapshot and history after
[Hub PR #375](https://github.com/jimmie-potts/agent-device-hub/pull/375), the
guide refresh for ADR 0007 and ADR 0008 that rewrote the Direction section and
every topic's text. Earlier
editions added the Direction section
([Hub PR #300](https://github.com/jimmie-potts/agent-device-hub/pull/300)),
story-owned topic placement
([Hub PR #281](https://github.com/jimmie-potts/agent-device-hub/pull/281)),
starting-session recommendations
([Hub PR #266](https://github.com/jimmie-potts/agent-device-hub/pull/266) and
[Hub PR #260](https://github.com/jimmie-potts/agent-device-hub/pull/260)), the
one-shot circuit trace
([Hub PR #265](https://github.com/jimmie-potts/agent-device-hub/pull/265)) and the
Neon Geometry Wars presentation
([Hub PR #251](https://github.com/jimmie-potts/agent-device-hub/pull/251)).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `493039eacb7e073cb4bf40bcf814439ef488ee4b2701f10a839c701a7a51b217`
- `atlas/manifest.json` SHA-256:
  `227114f62046d35f321457db5563206253cddc9cae4444bcd26087bc61011022`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
