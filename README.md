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

Published source revision: `f11334de55b700f8723387dfc15157f57ecd7388`.

`index.html` SHA-256:
`185bf88047b9a5f9c7ebaaf8c7b35465cade8c4840e81f91bda27667d810e280`.

Source publication: [Hub PR #149](https://github.com/jimmie-potts/agent-device-hub/pull/149) adds clear story status and next steps; [Hub PR #150](https://github.com/jimmie-potts/agent-device-hub/pull/150) records completed delivery in the snapshot.

The standalone viewers can request Google Fonts and include offline fallbacks.
