---
name: Warm Editorial Gallery
colors:
  surface: '#fbf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fbf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#eae8e2'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c18'
  on-surface-variant: '#494740'
  inverse-surface: '#30312d'
  inverse-on-surface: '#f3f1eb'
  outline: '#7a776f'
  outline-variant: '#cbc6bd'
  surface-tint: '#605e5b'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b19'
  on-primary-container: '#868380'
  inverse-primary: '#cac6c2'
  secondary: '#655d55'
  on-secondary: '#ffffff'
  secondary-container: '#e9ded3'
  on-secondary-container: '#696159'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#9f7e57'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2de'
  primary-fixed-dim: '#cac6c2'
  on-primary-fixed: '#1c1b19'
  on-primary-fixed-variant: '#484644'
  secondary-fixed: '#ece1d6'
  secondary-fixed-dim: '#cfc5ba'
  on-secondary-fixed: '#201b14'
  on-secondary-fixed-variant: '#4c463e'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#e7c094'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#5c4220'
  background: '#fbf9f3'
  on-background: '#1b1c18'
  surface-variant: '#e4e2dd'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 30px
  study-label:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.04em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  meta-caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.02em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system channels an editorial, high-end fine art aesthetic rooted in classical archival print and luxury gallery curation. Designed for discerning couples and patrons of couture wedding photography, the experience prioritizes restraint, tactile intimacy, and timeless craftsmanship. 

The aesthetic is characterized by:
- **Warm Paper Substrate:** Replacing cold digital whites with warm, unbleached cotton paper and parchment tones that evoke tactile, heavyweight wedding albums.
- **Editorial Archival Typography:** High-contrast, literary display serifs paired with disciplined, understated modernist grotesques.
- **Museum Indexing & Study Notes:** Catalog-style numbering (`Fig. 01 —`, `01 — Consultation & Scouting`), structured metadata captions, and curated provenance markers.
- **Disciplined Structural Grids:** Ultra-fine 1px hairline dividers (`border-stone-300` / `rgba(34, 34, 34, 0.12)`) and vast breathing room that let intimate, emotional photography command focus.

## Colors

The palette is deliberately subdued, allowing photography to be the primary chromatic focus. 

- **Primary (`#1A1917`):** Deep carbon charcoal, softer than pure digital `#000000`. Used for high-contrast serif headlines, primary buttons, and sharp typographic accents.
- **Neutral Background (`#F8F6F0`):** A warm, tactile cream paper tone. Secondary canvas tiers utilize `#F2EFE8` (album backing) and `#EAE6DC` (subtle framing).
- **Secondary (`#766E65`):** Warm graphite/stone. Applied to secondary narrative paragraphs, figure notes, metadata, and descriptive labels.
- **Hairlines & Dividers (`rgba(26, 25, 23, 0.12)` or `#DFDAD0`): Fine structural rules separating sections, catalog lists, and caption zones.
- **Tertiary Accent (`#9E7D56`):** Antique gold/sepia bronze, used sparingly for active states, monograph emblems, or highlighted collection status.

## Typography

The type system pairs **Playfair Display**—a high-contrast transitional editorial serif—with **Plus Jakarta Sans**, a clean geometric sans with refined humanistic proportion.

- **Display & Headlines:** Set in `Playfair Display` with delicate tracking and tight line heights to evoke high-fashion print editorial spreads and art books.
- **Process & Study Indexing:** Set in `Plus Jakarta Sans` Medium with an em-dash convention (`01 — The Engagement Session`, `Fig. 02 — Saint George Cathedral`).
- **Body & Editorial Summaries:** Set in `Plus Jakarta Sans` Regular with generous leading for comfortable legibility against the cream paper background.
- **Captions & Metadata:** Small, clean, muted secondary text aligned to grid borders, conveying precise dates, locations, and format notes (`Medium Format Film, 2025`).

## Layout & Spacing

The layout philosophy is founded on an **asymmetric, spacious fixed-bleed editorial grid** with extensive breathing room:
- **Columns & Framing:** 12-column desktop grid with a maximum content container of 1320px. Sections are divided by 1px hairlines running edge-to-edge or inset to column margins.
- **Horizontal Rhythms:** Generous section spacing (`space-2xl` to `space-3xl`) simulates the experience of turning broadsheet pages in an exhibition catalog.
- **Gallery Arrangements:** Mixed vertical ratios (4:5, 3:2, and cinematic 16:9 banners) accompanied by offset, staggered column alignments rather than uniform dense tiles.
- **Mobile Adaptations:** Folds multi-column curated steps (`01`, `02`, `03`) into stacked horizontal blocks separated by hairlines; margins compress to 20px while preserving image aspect ratios.

## Elevation & Depth

This design system avoids simulated skeuomorphic drop shadows, heavy blurs, and stacked elevation tiers. Instead, depth is articulated through:
- **Low-Contrast Hairlines:** 1px horizontal and vertical rules (`#DFDAD0` or `rgba(26, 25, 23, 0.12)`) establish planes and structural divisions without visual bulk.
- **Tonal Insets:** Occasional muted parchment boxes (`#F2EFE8`) delineate pull-quotes, booking inquiries, or featured portrait contact sheets.
- **Pure Photography Layering:** Full-bleed photo headers and cinematic breaks create organic immersion without interface trickery.

## Shapes

In keeping with fine-art print tradition, all elements have crisp, architectural boundaries:
- **Zero Radius (`0`):** Buttons, inputs, photo frames, and interactive chips feature sharp 90-degree corners.
- **Linework:** Borders and dividers are strictly 1px hairlines, reinforcing the precision of gallery matting and museum monographs.

## Components

### Buttons & Interactive Links
- **Primary Action:** Solid charcoal rectangle (`#1A1917`) with cream text (`#F8F6F0`), uppercase or title case sans-serif (`13px`, medium, letter-spaced `0.05em`), zero radius, padding `14px 28px`. Hover shifts to subtle warm bronze (`#2D2926`).
- **Text Link / Inquiry Trigger:** High-contrast underline or inline arrow (`Check availability →` or `See the full index →`), positioned flush with typography, transitioning opacity on hover.
- **Secondary Ghost Button:** 1px border (`#1A1917`), transparent background, charcoal text.

### Curated Study Items & Process Lists
- Horizontal flex/grid spanning 3 columns across desktop.
- Header featuring numbering and label: `01 — Consultation & Scouting` in `study-label`.
- Separated by top and bottom 1px hairlines. Body description beneath in secondary graphite (`#766E65`).

### Gallery Cards & Figure Frames
- Images unencumbered by corner radii or drop shadows.
- Accompanied by a two-part meta bar above or below: `Fig. 01 — Morning Veil, Addis Ababa` left-aligned; `Medium Format, 2025` right-aligned in `meta-caption`.
- Hover interactions feature subtle scale or soft opacity transitions (no elevation lift).

### Form Controls & Inquiries
- Underlined minimalist text fields with a single bottom 1px hairline (`border-b border-[#1A1917]/20`), expanding to 100% opacity on focus.
- Labels set above inputs in `meta-caption` uppercase.
- Dropdown selectors and date pickers use flat, borderless styling on warm parchment backgrounds.

### Accordion / Archive Index Rows
- Thin top and bottom hairlines framing collection categories (`Ceremony`, `Reception`, `Editorial Portraits`).
- Title in `headline-md` serif with a slim `+` or `—` icon flush right, expanding into an integrated photo contact strip.