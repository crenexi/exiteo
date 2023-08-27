# Exiteo

![][urlCrenexiFav]

**[www.exiteo.com][urlExiteoProd]** | [stage.exiteo.com][urlExiteoStage]

Exiteo, a wayfinding platform.

# Setup

## Dependencies

- NodeJS/NPM
- Font Awesome Pro

## Installation

1. **Configure**: `npm run configure`
2. **Install**: `npm run install`
3. **Start**: `npm start`

# Tooling

## Lint

- **Lint**: `npm run lint`
- **Lint & fix**: `npm run lint:fix`

## Build

- **Build plainly**: `npm run build`
- **Build development**: `npm run build:dev`
- **Build production**: `npm run build:prod`

## Maintain

- **Analyze bundle stats**: `npm run stats`
- **Cleanup** (removes `dist`): `npm run cleanup`

# Development

## Assets

- **Test**: use `cxa-upload.sh` from any local dir
- **Stage**: releases as step in stage pipeline
  - `npm run deploy:assets stage` within `build.stage.yml`
- **Prod**: releases as step in prod pipeline
  - `npm run deploy:assets prod` within `build.prod.yml`

# Footnotes

## License

- MIT License

## Authors

* **James Blume** - [Crenexi](https://github.com/crenexi)

[urlExiteoProd]: https://www.exiteo.com
[urlExiteoStage]: https://stage.exiteo.com
[urlCrenexiFav]: https://www.crenexi.com/assets/brand/fav_48x48.png
