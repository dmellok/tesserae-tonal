# Tonal — a Tesserae theme pack

Six medium-vivid, feature-colour-led light themes for [Tesserae](https://github.com/dmellok/tesserae). Each theme has a gently tinted off-white canvas and a coherent 6-accent palette led by its namesake colour.

| Theme | Lead colour | Vibe |
|---|---|---|
| `tonal-slate` | steel blue (#4A6580) | cool, considered, infrastructure |
| `tonal-clay` | terracotta (#B85730) | warm, grounded, kitchen |
| `tonal-moss` | sage green (#5F7E45) | calm, outdoor, garden |
| `tonal-plum` | dusty purple (#7F4A6A) | rich, evening, study |
| `tonal-harbour` | deep teal (#2F8A78) | crisp, waterfront, bathroom |
| `tonal-copper` | warm bronze (#A05B30) | aged, autumnal, library |

All six share a complementary accent palette (gold, olive, slate-blue, clay, plum, teal) tuned to feel cohesive across the pack, so swapping between themes doesn't reshuffle every widget's category colours.

## Install

Via the catalog (recommended): **Tesserae → Settings → Widgets → Browse community widgets**, find "Tonal", hit Install. Tesserae downloads this tarball, validates the six theme pairs, and lays them out under `data/themes/community/`.

Requires **Tesserae 0.47.8 or newer** (theme catalog kind shipped then).

## Use

Each theme is an opt-in palette; nothing changes until you pick one. Set a theme:

- **Page-level**: open a dashboard, change "Theme" to e.g. `tonal-slate`.
- **Per-cell override**: any cell can pick its own theme to break out of the page's choice.

If you only ever use a few of these, the per-theme "Show in picker" toggle on the **Settings → Themes** strip hides the rest from your dropdowns without uninstalling the pack.

## What's inside

12 files at the tarball root, named by id:

```
tonal-clay.json    tonal-clay.css
tonal-copper.json  tonal-copper.css
tonal-harbour.json tonal-harbour.css
tonal-moss.json    tonal-moss.css
tonal-plum.json    tonal-plum.css
tonal-slate.json   tonal-slate.css
```

Each `.json` declares the theme's id, name, family, and tagline; each `.css` is a single `[data-theme="<id>"]{ ... }` block that overrides the Spectra colour tokens for that theme. No JavaScript, no Python, no fonts, no external assets.

## License

AGPL-3.0-or-later. See [LICENSE](./LICENSE).
