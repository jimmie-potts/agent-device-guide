# Agent device work guide and B.U.N.N.Y. atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the B.U.N.N.Y. system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide's topic assignments and totals are a dated snapshot, refreshed at
2026-09-25T06:57:15.265218+00:00. The opening lists show current work, newly added
issues, open defects, selected next steps, blockers and later work. They refresh
from public GitHub on page load, with a dated per-repository fallback. Eleven
topic guides retain unique issue ownership; completed evidence is expandable.
The merged-work history was read separately at 2026-09-24T23:42 UTC.
The atlas documents carry a September 19, 2026 baseline; the overview map pins
September 23 sources. Publication does not claim that every planned component
is running. The three source repositories are public, so issue, PR and source
links open without a GitHub sign-in.
The nine architecture viewers include Google Fonts links with offline fallbacks.

## Source and updates

The Hub repository maintains the generators, atlas sources, guide inputs and
validation. This edition comes from Hub revision
`47210ddfe69ae961561aa2e5f7b8ca8d513a8123`, delivered by
[Hub PR #300](https://github.com/jimmie-potts/agent-device-hub/pull/300), which
adds a dated Direction section (where B.U.N.N.Y. stands, what it is becoming,
what to build next, and a computed "Least work, most unblocked" table from the
recorded GitHub prerequisites), and
[Hub PR #281](https://github.com/jimmie-potts/agent-device-hub/pull/281), which
reads each story's topic placement, note and highlight from the story's own
Guide section, live from public GitHub when the read succeeds. It builds on the
starting-session recommendations from
[Hub PR #266](https://github.com/jimmie-potts/agent-device-hub/pull/266) and
[Hub PR #260](https://github.com/jimmie-potts/agent-device-hub/pull/260), the
one-shot circuit trace from
[Hub PR #265](https://github.com/jimmie-potts/agent-device-hub/pull/265) and the
Neon Geometry Wars presentation from
[Hub PR #251](https://github.com/jimmie-potts/agent-device-hub/pull/251).
The reviewed export stages the guide as `index.html`, the nine viewer files under
`architecture/`, and the atlas under `atlas/`. Do not edit those generated files
in this repository. Publish a new Hub revision through a reviewed public PR and
verify the bytes served by Pages after merge.

The public file allowlist is `index.html`, nine `architecture/*.html` viewers,
the files named in `atlas/manifest.json`, that manifest, `.nojekyll` and this
README. No authoring scripts, fixtures, installation state or private databases
belong here.

- Public `index.html` SHA-256:
  `f02756cf8c3c25ac2fbb7b401794f4844391a8291f3841849932da3633c453bf`
- `atlas/manifest.json` SHA-256:
  `044bbb4fffdae28a9e54fd14abf56136b804e530de657523c6b64bde0ac56366`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
