# chutvrc Spoke

[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

The editor-side code for [chutvrc](https://github.com/pf-hubs/chutvrc-spoke), forked from [Spoke](https://github.com/mozilla/Spoke), to easily create custom 3D environments.

## chutvrc features

Currently this repository does not have anything specific customization for chutvrc.

Some notable features for chutvrc are,

- Full-body avatar (ReadyPlayerMe, VRoid)
- BitECS implementation
- Alternative WebRTC SFU (selection for Third-Pary WebRTC)
- Synchronizing avatar transform with WebRTC DataChannel

For more details, please see the [client-side code for chutvr](https://github.com/pf-hubs/chutvrc-hubs).

## Funding and Sponsor

<div align="center">
    <img src=".github/media/vrcenter-logo.png" width="320">
    <img src=".github/media/change-logo.png" width="320">
</div>

- chutvrc is sponsored and developed for [CHANGE Project](https://change.kawasaki-net.ne.jp/en/), by a research team at the [Virtual Reality Educational Research Center](https://vr.u-tokyo.ac.jp/), The University of Tokyo.
- You can support this development through the GitHub Sponsor button which is linked to the [UTokyo Foundation](https://utf.u-tokyo.ac.jp/en).
- If you want to support this project only, please write in the donation purpose "For Virtual Reality Educational Research Center, chutvrc related research/educational purpose."
  - Please be aware that 30% of the amount of donation will be used by the university administration office even if you write the donation purpose.

---

Below is the original README for Mozilla Spoke, which most information are also useful for chutvrc.

It will be updated to migration information considering the current status of Mozilla Hubs, which is planned to shutdown at the end of May 2024.

---

<p align="center"><a href="https://hubs.mozilla.com/spoke" target="_blank"><img width="480" alt="Spoke" src="https://user-images.githubusercontent.com/21111451/66261819-ffd9ff00-e799-11e9-88bf-981d238b4f20.gif"></a></p>

[![CircleCI](https://circleci.com/gh/mozilla/Spoke.svg?style=svg)](https://circleci.com/gh/mozilla/Spoke)


  **Easily create custom 3D environments for [Mozilla Hubs](https://hubs.mozilla.com).**

**[Launch Spoke](https://hubs.mozilla.com/spoke)**

**[Spoke Documentation](https://hubs.mozilla.com/docs/spoke-creating-projects.html)**

## Features

:telescope: **Discover**: Explore images, videos, and 3D models from around the web, all without opening up a new tab. With media integrations from Sketchfab and Google Poly, you'll be on your way to creating a scene in no time.

:pencil2: **Create**: No external software or 3D modeling experience required - build 3D scenes using the Spoke web editor so you can have a space that's entirely custom to your needs. From a board room to outer space and beyond, your space is in your control.

:tada: **Share**: Invite people to meet in your new space by publishing your content to Hubs immediately. With just a few clicks, you'll have a world of your own to experience and share - all from your browser.

## Contributing

Info on contributing to Spoke and general Spoke development can be found in the [CONTRIBUTING.md](./CONTRIBUTING.md) doc.

Additional developer documentation can be found in the [docs](./docs/README.md) folder.

## Credits

Parts of this project are derived from the [three.js editor](https://threejs.org/editor/)
with thanks to [Mr.doob](https://github.com/mrdoob) and three.js' many contributors.

Navigation mesh generation via recast.wasm, thanks to [Recast](https://github.com/recastnavigation/recastnavigation) and but0n's [RecastCLI wrapper](https://github.com/but0n/recastCLI.js).

See the [LICENSE](LICENSE) for details.
