## Grasshopper Bootstrap

![Build Action](https://github.com/philipbelesky/GrasshopperBootstrap/workflows/dotnet-grasshopper/badge.svg)

A slightly opinionated starter template for Grasshopper plugin development with a variety of development aids.

#### Features

- [X] Grasshopper/RhinoCommon bundled with Nuget
  - *Ensures reference paths are maintained across local environments*
- [X] Separate out a `release` folder for non-debug builds
  - *Makes working with Fody and bundling files (e.g. a README) easier*
- [X] A shared class for all component files to inherent
  - *Allows for shared functionality and/or easy implementation of error reporting*
- [X] Linting using FxCop, StyleCop, and a (relatively?) sane set of defaults
- [X] GitHub Pages setup for documentation
  - *See the `docs` folder and the README there*
- [X] Icons Illustrator template with original Grasshopper icons as references
  - *See the `assets` folder*
- [X] CD/CI using GitHub Actions
  - *See the steps in .github/workflows; currently the action will build the application and then upload the gha file from the Release build as an artefact. Build or linting failures will trigger a failed check.*
- [ ] Cross-compatibility between MacOS and Windows versions of Visual Studio
- [ ] Unit tests
- [ ] Performance tests
- [ ] Fody bundling of reference dlls
- [ ] Sentry setup for error reporting?
- [ ] Bash script for easily generating Yak releases
- [ ] Extracting component input/output parmas for doc files?
- [ ] Extracting GHX metadata for doc files?
-

#### Requirements

- Visual Studio (2017+?)
- Rhinoceros 6 or higher (no support for Rhinoceros 5 development OOTB)

#### Setup

- What to rename
- How to activate services
