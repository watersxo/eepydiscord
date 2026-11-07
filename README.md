# eepydiscord

eepydiscord is a pure black Discord theme with calm, restrained purple accents. It supports BetterDiscord and Vencord.

## Install

Place the matching file from this repository's releases or root directory in your client theme folder:

- BetterDiscord: `eepydiscord-BetterDiscord.theme.css`
- Vencord: `eepydiscord-Vencord.css`

The generic `eepydiscord.theme.css` file includes support for both clients.

## Build

```powershell
corepack pnpm install --ignore-scripts
corepack pnpm run build
```

The build produces optimized CSS in `public/`, expanded CSS in `public-unminified/`, and distributable theme files in the repository root.

## Credits

eepydiscord is built on the ClearVision v7 codebase and remains available under its Apache-2.0 license.
