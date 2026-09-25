# Agent device work guide and B.U.N.N.Y. atlas

- [Open the work guide](https://jimmie-potts.github.io/agent-device-guide/).
- [Open the B.U.N.N.Y. system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

This repository publishes reviewed output from the source
`jimmie-potts/agent-device-hub` repository. GitHub Pages serves `main` from `/`.
The guide stays at the site root, its nine interactive architecture viewers stay
under `/architecture/`, and the complete atlas stays under `/atlas/`.

The guide's topic assignments and totals are a dated snapshot, refreshed at
2026-09-25T05:35:31.046239+00:00. The opening lists show current work, newly added
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
`9009ce3e3164e8470c05e7d5417866186cdc6452`, delivered by
[Hub PR #266](https://github.com/jimmie-potts/agent-device-hub/pull/266), which
records a starting-session recommendation (session type, model and thinking
level for Claude Code and Codex, and the prompts to paste) in every open story
and refreshes the guide snapshot. It builds on the recommendation display from
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
  `2c7f3ffa119c7ac8c421e11798b299d600f447c8e5b398fddf9c4e52a8a4c2e5`
- `atlas/manifest.json` SHA-256:
  `044bbb4fffdae28a9e54fd14abf56136b804e530de657523c6b64bde0ac56366`
- Atlas entry point: <https://jimmie-potts.github.io/agent-device-guide/atlas/>
