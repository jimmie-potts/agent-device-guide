# Agent device work guide

[Open the guide](https://jimmie-potts.github.io/agent-device-guide/).

This repository publishes the generated cross-project work guide for Agent
Device Hub, Nanoleaf and Pixoo. It includes the guide and eight interactive
architecture viewers. GitHub Pages serves `main` from `/`.

The guide is a dated snapshot. Its issue, history and architecture timestamps
describe separate evidence. Links to private GitHub repositories require access.

## Source and updates

The private `jimmie-potts/agent-device-hub` repository maintains the generator,
inputs and validation. Publish its reviewed output here through a pull request
after source review and CI. Do not edit generated HTML here. Each publication
contains only `index.html`, the eight `architecture/*.html` viewers, `.nojekyll`
and this README. A merge here triggers GitHub Pages; hub changes require a new
publication PR before they appear online.

Published source revision: `8064537639d7a91a66657cdbce9a63654e41b80c`.

`index.html` SHA-256:
`3004c48ff75f3cc54b59735da3bd71071d2c178f41ef6d15b4d898229473c7c3`.

The standalone viewers can request Google Fonts and include offline fallbacks.
