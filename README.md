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

Published source revision: `260707019b7ff83d57e31d91ae1e1582c3734589`.

`index.html` SHA-256:
`4d8f172a5025252c7b06551dfa862d1abe697fc532a54f75151d231217ed799e`.

Source publication: [Hub PR #122](https://github.com/jimmie-potts/agent-device-hub/pull/122), following the BUNNY UI planning in [Hub PR #120](https://github.com/jimmie-potts/agent-device-hub/pull/120).

The standalone viewers can request Google Fonts and include offline fallbacks.
