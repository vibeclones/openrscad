# openrscad (Vibeclones mirror)

Hosted browser builds of the playground from [OpenRSCAD](https://github.com/matthova/openrscad), a from-scratch Rust reimplementation of the OpenSCAD language, by [matthova](https://github.com/matthova). The code is theirs; this repo only builds and hosts it. The project's own playground is at https://matthova.github.io/openrscad/playground.

- Latest: `/openrscad/latest/`
- A specific version: `/openrscad/v<version>/`, for example `/openrscad/v0.14.0/`
- Version list: `/openrscad/versions.json`

Each version is built from an upstream release tag with the project's own web build. Each version opens straight into the playground (`playground.html`); the project's front page is kept as `home.html`. A scheduled workflow builds new releases.

Upstream is licensed Apache-2.0 OR MIT. Every version folder includes the license files and a `SOURCE.txt` naming the exact upstream tag it was built from.