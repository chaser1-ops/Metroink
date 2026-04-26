# METRO INK & STITCH — Logo System

Designed by [RISE Studio Labs](https://risestudiolabs.com) for Metro Ink & Stitch (DFW).

---

## What's in this folder

| File | Use this when... |
|---|---|
| `metro-ink-stitch-primary.svg` | Main brand asset on cream/light backgrounds — letterhead, packaging, light-colored merch |
| `metro-ink-stitch-primary-dark.svg` | On black or dark backgrounds — website footer, dark merch |
| `metro-ink-stitch-horizontal.svg` | Nav bars, email signatures, business card backs — wide horizontal layouts |
| `metro-ink-stitch-mark.svg` | Square placements — social avatars, hat patches, app icons |
| `metro-ink-stitch-mono-black.svg` | **Embroidery digitizing source.** Single-color screen prints, invoices, fax letterhead |
| `metro-ink-stitch-mono-cream.svg` | When printing on red or black backgrounds with one ink |
| `metro-ink-stitch-mono-red.svg` | All-red accent uses |
| `favicon.svg` | Browser tabs, app icon source |

> **All `.svg` files have been outlined.** Text has been converted to vector paths, so the logos render identically on any machine, even ones without Archivo Black or JetBrains Mono installed. Safe to hand to any vendor.

---

## File format guide

You'll see the same logo in different formats across this delivery. Use the right format for the job:

| Format | When to use |
|---|---|
| **SVG (outlined)** | Web, scalable print, anywhere modern. The master file. |
| **PDF** | Print vendors. Most sign shops, embroiderers, and screen printers prefer PDF for their RIP software. |
| **EPS** | Older print workflows that don't accept PDF. Adobe Illustrator-friendly. |
| **PNG (300dpi)** | When a vendor only takes raster. Resolution is high enough for medium-size prints. |

If a vendor only asks for "the logo," default to handing them the **PDF**. Universal compatibility, vector-perfect, no font issues.

---

## Color Palette

| Role | Hex | CMYK (estimate) | Use |
|------|-----|---|---|
| Ink (black) | `#0d0d0d` | C0 M0 Y0 K100 | Primary type, skyline, frames |
| Cream (paper) | `#f3ecdb` | C5 M7 Y17 K0 | Background, light type on dark |
| Signal Red | `#e63027` | C0 M85 Y85 K0 (Pantone 485 C close) | Accent, "INK &" wordmark, ink drops |
| Mustard | `#e8b923` | C8 M28 Y90 K0 | Underline accent |

> For embroidery thread matching: **Madeira Polyneon** approximations are 1147 (black), 1759 (cream/ivory), 1838 or 1747 (red), 1238 (mustard yellow). Confirm with your digitizer.

---

## Typography (live SVG only — outlined files don't need these installed)

- **Display**: Archivo Black ([Google Fonts](https://fonts.google.com/specimen/Archivo+Black))
- **Mono**: JetBrains Mono ([JetBrains](https://www.jetbrains.com/lp/mono/))

---

## Usage rules

### Do
- Use primary (cream bg) on light surfaces
- Use primary-dark on black/dark surfaces
- Use horizontal lockup in nav bars and email signatures
- Use mark-only for square placements (avatars, hat patches, favicons)
- Use mono-black for embroidery digitizing
- Maintain at least 30px clear space around the logo

### Don't
- Don't recolor outside the approved palette
- Don't apply drop shadows, glows, or embosses
- Don't stretch or skew
- Don't place on busy/photographic backgrounds without a solid backing shape
- Don't substitute fonts — if you need to edit text, use the **web-svg** versions and have Archivo Black installed

---

## Embroidery production notes

When sending to an embroidery digitizer:

1. **Hand them**: `print-pdf/metro-ink-stitch-mono-black.pdf` or `print-svg-outlined/metro-ink-stitch-mono-black.svg`
2. **Tell them**: target size, garment type, thread spec
3. **Expected stitch count**: ~6,000–10,000 stitches at 4" chest size on a polo or hat
4. **Stitch types to request**:
   - Skyline silhouette → fill stitch
   - Wordmark (METRO, INK&, STITCH) → fill stitch
   - Halftone dots → drop these or convert to small satin dots (digitizer's call)
   - Mustard underline + red drips → satin stitch in their respective colors

Final embroidery file formats your digitizer will produce: `.dst` (Tajima), `.exp` (Melco), `.pes` (Brother). Keep these archived alongside the master logo files.

---

## Screen print production notes

For multi-color screen print separations using the **primary** logo:

| Color | Layer | Notes |
|---|---|---|
| Black plate | Skyline + METRO + STITCH + tagline | Heaviest coverage |
| Red plate | INK & + ink drips + EST·DFW label + corner stamps | Watch trap with black |
| Mustard plate | Underline only | Tightest registration |

For a 1-color spot print, use `mono-black.svg`.

---

## Web integration

The website at `metroinkandstitch.com` (built by RISE Studio Labs) uses these files:

- `logo/metro-ink-stitch-horizontal.svg` → site nav
- `logo/metro-ink-stitch-primary-dark.svg` → site footer
- `logo/favicon.svg` + `favicon-32.png` + `favicon-180.png` → browser tab + iOS home screen

All web-served logos are outlined SVG, so the site renders correctly even if Google Fonts is blocked or slow.

---

## Delivery archive structure

If you received the full delivery zip, this is what's inside:

```
delivery/
├── web-svg/                 Live-text SVG (smallest files, web use)
├── print-svg-outlined/      Outlined SVG (any vendor, any machine)
├── print-pdf/               PDF (vendor default)
├── print-eps/               EPS (Adobe / older workflows)
├── print-png-300dpi/        300 DPI raster (when vendor needs PNG/JPG)
└── favicon-png/             Web/app favicon PNGs (32px, 180px)
```

---

## Questions / new file requests

For brand additions (new mockups, business cards, sign mockups, product packaging) reach out to RISE Studio Labs at chase@risestudiolabs.com.

— RISE Studio Labs · 2026
