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

Published source revision: `dd00c7846d6f6da79a09948b925ddda0e9c342b7`.

`index.html` SHA-256:
`0fafa2b15ca5ee830f90e8855d96c865e796fbda5fa6d85c35be1713e395b385`.

Source publication: [Hub PR #156](https://github.com/jimmie-potts/agent-device-hub/pull/156) records the accepted general-control definition and three concurrent closures; [Hub PR #157](https://github.com/jimmie-potts/agent-device-hub/pull/157) records the closed definition and the refreshed backlogs.

The standalone viewers can request Google Fonts and include offline fallbacks.
