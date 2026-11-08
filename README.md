<div align="center">

# MagicBox

**Optimize, organize, and export design assets from one desktop app.**

Minify images, graphics, and design source files. Group them into file sets, assign them to projects, track updates, and export them where they belong.

[![Latest release](https://img.shields.io/github/v/release/pixel-perfectionist/MagicBox?label=release)](https://github.com/pixel-perfectionist/MagicBox/releases/latest)
[![GitHub stars](https://img.shields.io/github/stars/pixel-perfectionist/MagicBox?style=flat)](https://github.com/pixel-perfectionist/MagicBox/stargazers)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg)](LICENSE.md)
[![Built with Electron](https://img.shields.io/badge/Electron-Angular-47848F.svg)](#getting-started)

[**Download for macOS**](https://github.com/pixel-perfectionist/MagicBox/releases/latest) · [Watch the demo](https://vimeo.com/940583258) · [Report a bug](https://github.com/pixel-perfectionist/MagicBox/issues/new)

[![MagicBox demo](https://i.imgur.com/iB1uC9X.jpeg)](https://vimeo.com/940583258 "Watch the MagicBox demo")

</div>

## Features

- **Shrink file size** for SVG, JPEG, PNG, GIF, WebP, TIFF, and Sketch files
- **Organize your workspace** with file sets assigned to projects, with update tracking
- **Icon manager** for browsing and exporting icon sets
- **SVG editor** built in
- **Convert SVG** to:
  - Base64 string
  - CSS background (URI encoded)
  - Serialized CG/UIPaths for iOS and macOS
- **Sketch file optimization**

### Coming soon

- Font manager
- SVG to React component
- PX to REM converter

## Download

Get the latest `.dmg` from the [Releases page](https://github.com/pixel-perfectionist/MagicBox/releases/latest). Windows and Linux builds can be made from source (see below).

## Getting started

Clone the repository:

```bash
git clone https://github.com/pixel-perfectionist/MagicBox.git
cd MagicBox
```

Install dependencies with npm:

```bash
npm install
```

> Use `npm`, not `yarn`. The packager has an issue with `node_modules` created by `yarn`.

Start the app in development mode:

```bash
npm run electron:local
```

### Commands

| Command                              | Description                                           |
| ------------------------------------ | ----------------------------------------------------- |
| `npm start`                          | Run Angular dev server and Electron with live reload  |
| `npm run electron:local`             | Production build, then start Electron                 |
| `npm run electron:build`             | Build an installer for your current operating system  |
| `npm run electron:build -- --mac`    | Build for macOS                                       |
| `npm run electron:build -- --win`    | Build for Windows                                     |
| `npm run electron:build -- --linux`  | Build for Linux                                       |
| `npm test`                           | Run unit tests                                        |
| `npm run lint`                       | Lint the project                                      |

## Contributing

Pull requests are welcome. Before you open one, run `prettier --write` in the project directory.

If MagicBox saves you time, a ⭐ on the repo helps other people find it.

## License

[CC BY-NC 4.0](LICENSE.md). Free to use and modify for non-commercial purposes.

## Author

**Alexander Katrukhin** · [@pixel-perfectionist](https://github.com/pixel-perfectionist) · [ux-engineer.com](https://ux-engineer.com)

[![Donate](https://img.shields.io/badge/Donate-PayPal-brightgreen.svg)](https://paypal.me/katrukhin)
