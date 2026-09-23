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

Published source revision: `ad5aef8fd5e09b828cb3595f23af621bfc41408a`.

`index.html` SHA-256:
`df6cf685dc3e743afe07e791a8f5521ca1f3a6dc1eba46e6fd7937559789a354`.

Source publication: the latest guide changes come from [Hub PR #159](https://github.com/jimmie-potts/agent-device-hub/pull/159), [#160](https://github.com/jimmie-potts/agent-device-hub/pull/160), [#161](https://github.com/jimmie-potts/agent-device-hub/pull/161), [#162](https://github.com/jimmie-potts/agent-device-hub/pull/162), [#163](https://github.com/jimmie-potts/agent-device-hub/pull/163) and [#165](https://github.com/jimmie-potts/agent-device-hub/pull/165). They record the Nanoleaf device-aware state foundation, Nanoleaf native controls, and the completed Pixoo and Nanoleaf general controls.

The standalone viewers can request Google Fonts and include offline fallbacks.
