# Silvernium iOS 26 Liquid Glass (Vencord)

Now tuned to be much closer to **ClearVision-style transparency/translucency**, while staying fully local and modular.

## Structure

- `MidnightNebula.theme.css` → main modular entrypoint
- `css/00-settings.css` → ClearVision-like tokens and theme shading variables
- `css/10-layout.css` → transparent/translucent app/layout surfaces
- `css/20-interactions.css` → channel/button behavior + Vencord UI styling
- `css/30-branding.css` → Silvernium branding/nameplate overrides
- `css/40-accessibility.css` → reduced-motion accessibility
- `Silvernium.bundle.css` → merged single-file fallback

## Usage

1. Try `MidnightNebula.theme.css` first.
2. If local imports fail, use `Silvernium.bundle.css`.
