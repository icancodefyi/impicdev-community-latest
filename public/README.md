# ImpicDev Community — public assets

All binary assets a page will ever ask for. Everything is web-compressed
(webp where possible); print-ready originals live under `print/`.

```
public/
├── branding/        logos + favicons + print files
│   ├── logo.png             original square wordmark, 1024px
│   ├── logo-full.webp       hero tile, 720px
│   ├── logo-nav.png         navbar sticker, 128px
│   ├── favicon.png          64px
│   ├── apple-touch-icon.png 180px
│   └── print/               print-ready PDFs (stickers sheet, standee)
├── stickers/        die-cut mascot stickers, 800px webp, alpha preserved
│   ├── impi-laptop.webp     Impi coding with coffee
│   ├── impi-peek.webp       Impi peeking over an edge
│   ├── impi-wink.webp       Impi winking, peace sign
│   ├── impi-shades.webp     Impi with sunglasses
│   ├── wordmark-pill.webp   "ImpicDev" pill
│   └── standee-poster.webp  full standee design (mascot + QR)
├── events/          per-event photo libraries
│   └── gen-ai-workshop-2026/   55 photos, see its README.md
└── join/            join-flow assets
    └── join-qr.png          QR → /join
```

## Conventions
- Paths are stable URLs — reference them as `/stickers/impi-laptop.webp` etc.
- New event: create `events/<event-slug>/` + README.md with date/venue/captions.
- Photos keep their camera name (`img_XXXX.jpg.webp`) so the raw folder can be
  matched back if ever needed; hand-picked crowd/speaker shots get readable
  names (`group-photo.webp`, `session-speaker.webp`, `session-audience.webp`).
