# Renjin Design

This repository contains many of the design assets shared/used across the Renjin platform.

The icon family currently covers the following:

- Renjin Studio assets
  - "Interface system" icons for the inspector
  - Spatial / transform controls

Canonical icons live under `icons/source/` as simple SVG documents.

## Conventions for Renjin original icons

- `24 x 24` view box
- `#000000` is the replaceable foreground token
- rounded line caps and joins
- no embedded raster images, scripts, external references, or text
- semantic names instead of toolkit-specific names

Inspector preview diagrams under `icons/source/studio/inspector/preview/` use a
`180 x 56` view box. They explain spatial behaviour at a larger scale (for viewing when the mouse is hovered over an item) and
must not be substituted by enlarged button glyphs.

## Attribution

This repository contains a mix of Renjin original work, work inspired by other icon sets where licenses are permissive, and direct third-party icons.
This is to simplify icon distribution across our other proprietary repositories.

Where a third-party icon is used, its source is recorded in `icons/manifest.json` and its licence is retained in `THIRD_PARTY_NOTICES.md`.
