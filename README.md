# Agent device work guide

[Open the guide](https://jimmie-potts.github.io/agent-device-guide/).

This repository publishes the generated cross-project work guide for Agent
Device Hub, Nanoleaf and Pixoo. It includes the guide and nine interactive
architecture viewers. GitHub Pages serves `main` from `/`.

The guide is a dated snapshot. Its issue, history and architecture timestamps
describe separate evidence. Links to private GitHub repositories require access.

## Source and updates

The private `jimmie-potts/agent-device-hub` repository maintains the generator,
inputs and validation. Publish its reviewed output here through a pull request
after source review and CI. Do not edit generated HTML here. Each publication
contains only `index.html`, the nine `architecture/*.html` viewers, `.nojekyll`
and this README. A merge here triggers GitHub Pages; hub changes require a new
publication PR before they appear online.

Published source revision: `133cd145cec0b623afcbf8d193242037f4e37e06`.

`index.html` SHA-256:
`260c789a154a21f6d0f00ae1d47619dac71248466490389625bdeaabaf1d8aaf`.

Source publication: the latest guide changes come from [Hub PR #143](https://github.com/jimmie-potts/agent-device-hub/pull/143), [#177](https://github.com/jimmie-potts/agent-device-hub/pull/177) and [#183](https://github.com/jimmie-potts/agent-device-hub/pull/183). They record the N30 input qualification and the new BUNNY atlas system map and walkthrough. They also refresh every guide to the 23 September 2026 issue state: Tidbyt cloud controller source, the iPhone AirPlay qualification, Nanoleaf panel effects and external-scene findings, the BUNNY owner launcher, and no stale blockers or statuses.

The standalone viewers can request Google Fonts and include offline fallbacks.
