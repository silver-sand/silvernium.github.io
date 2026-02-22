# ClearVision iOS 26 Liquid Glass (Vencord)

This theme now uses **ClearVision v7** as the base and layers an iOS 26-style Liquid Glass treatment on top.

## What changed

- Uses ClearVision imports (`main.css`, `betterdiscord.css`, `vencord.css`).
- Deep-blue dark backdrop and stronger translucent glass materials.
- Refractive sheen animation on key containers.
- Floating bottom composer treatment (Discord analog to floating tab bar feel).
- Rounded pill controls and liquid popout/modal cards.

## Install

1. Save `MidnightNebula.theme.css`.
2. Open Discord with Vencord.
3. Go to **Settings → Vencord → Themes**.
4. Import/add the file and enable it.

## Customize

Edit `:root` variables:
- `--main-color`, `--hover-color` for primary accents.
- `--background-image` and `--background-filter` for overall atmosphere.
- `--lios-glass-*` for glass/refraction strength.

## Notes

- This depends on ClearVision-hosted imports being reachable.
- Includes `prefers-reduced-motion` and `prefers-reduced-transparency` fallbacks.
