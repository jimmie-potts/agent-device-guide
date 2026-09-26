# Agent device work guide and B.U.N.N.Y. atlas

[Open the work guide](https://jimmie-potts.github.io/agent-device-guide/) or
[open the system design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/).

GitHub Pages serves the reviewed output from `jimmie-potts/agent-device-hub`.
The guide is at the site root, nine interactive architecture viewers are under
`architecture/`, and the complete atlas is under `atlas/`.

This edition uses Hub revision `0eb7474ce9d76bc0c928a17da0c5fd23288f9f7b`, from
[Hub PR #440](https://github.com/jimmie-potts/agent-device-hub/pull/440) and its
[guide completion PR #447](https://github.com/jimmie-potts/agent-device-hub/pull/447).
The playback atlas now describes the installed Sony HT-A9 and Sonos Move sources,
source ranking, paused-track metadata lag and command boundaries. Its other
baseline sections remain explicitly dated; publication does not claim that every
planned component is installed.

The guide snapshot was refreshed at `2026-09-26T05:57:06.140671+00:00` and contains
236 open issues across 12 topics. History was read at
`2026-09-26T05:51:58.138474+00:00`. Live GitHub reads can update issue lists,
status and topic placement, with a dated fallback for each repository. Editorial
prose, history and the roadmap remain dated. Recent source deliveries and their
installation follow-ups are separate. The nine viewers retain Google Fonts links
with offline fallbacks.

## Source and updates

The Hub owns the generators, authored atlas, saved guide inputs and checks.
Publish an export of a reviewed Hub revision through a public PR, then verify
Pages deployment and every served file against the reviewed hashes. Do not edit
generated files here or refresh data in this repository.

The public allowlist is `index.html`, nine `architecture/*.html` viewers,
`atlas/manifest.json`, every file it names, `.nojekyll` and this README. It excludes
authoring scripts, fixtures, installation state and private databases.

- Public `index.html` SHA-256: `1abae8be624af21f791eb7bbe4466fbe8cb0e09dc7fe80d6bcd93f96c223f394`
- `atlas/manifest.json` SHA-256: `d37d86a02ed2ba304612082698db8a762a304ad5ee87dcf672238596e4d14c41`
- Atlas entry point: [System design atlas](https://jimmie-potts.github.io/agent-device-guide/atlas/)
