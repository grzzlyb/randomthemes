# Random Theme Generator Plugin for Adobe Illustrator

![paletizer](https://github.com/grzzlyb/randomthemes/assets/123747958/c4c224f5-dbab-403b-bdb1-d1581daf2ae1)

This plugin is tailored for Adobe Illustrator, enabling seamless generation of diverse and aesthetic color palettes directly within your compositions. It provides multiple palette modes, enhancing your creative workflow.

## Key Features

- **Versatile Color Palette Generation:**
  - Create Single Color Palettes
  - Generate Random Palettes
  - Craft Theme-Based Palettes
  - Derive Palettes from Images

- **Effortless Illustrator Integration:**
  - Fill selected objects with palette colors and seamlessly add them to swatches
  - Import entire palettes as groups, swiftly integrating all colors into swatches

- **Convenience and Customization:**
  - Save and load preset palettes for efficient usage
  - Customize hue and saturation in Single Color Mode

- **Cutting-Edge Technology Stack:**
  - Developed using React, Typescript, and bolt-cep for a modern and robust solution

## Development Requirements

- Node.js 16 or later

## Compatibility

- Adobe Illustrator CC version 2020 or later
- Windows

## Usage Instructions

1. Ensure your Adobe Illustrator version is CC 2021 or newer.
2. Download the ZXP/UXP Installer provided by AEScripts
3. Install the .zxp file from `dist/zxp/` using the ZXP Installer.
4. In Illustrator, navigate to `Window` -> `Extension` -> `Random Theme Generator v1.0`

## Quick Start Guide for Developers

```bash
git clone [repository]
cd [directory]
npm install
npm run build
npm run dev
npm run serve
npm run zxp
npm run zip
```

## Configuration and Code Structure
- Typescript/application code in src/js/main/index.tsx
- ExtendScript code can be found in src/jsx/main.ts
