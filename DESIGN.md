---
name: Apex Avian & Fauna Logistics
colors:
  surface: '#f8f9fd'
  surface-dim: '#d9dade'
  surface-bright: '#f8f9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f7'
  surface-container: '#edeef2'
  surface-container-high: '#e7e8ec'
  surface-container-highest: '#e1e2e6'
  on-surface: '#191c1f'
  on-surface-variant: '#44474d'
  inverse-surface: '#2e3134'
  inverse-on-surface: '#eff1f5'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#4f5e7f'
  primary: '#00030f'
  on-primary: '#ffffff'
  primary-container: '#0b1d3a'
  on-primary-container: '#7585a8'
  inverse-primary: '#b6c7ec'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#000310'
  on-tertiary: '#ffffff'
  tertiary-container: '#0f1d37'
  on-tertiary-container: '#7885a5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b6c7ec'
  on-primary-fixed: '#091b38'
  on-primary-fixed-variant: '#374766'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#b9c6e8'
  on-tertiary-fixed: '#0d1b35'
  on-tertiary-fixed-variant: '#3a4763'
  background: '#f8f9fd'
  on-background: '#191c1f'
  surface-variant: '#e1e2e6'
typography:
  display-hero:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system establishes a high-tier, authoritative, yet serene digital environment for bespoke international live-animal logistics and customs brokerage. The audience includes falconers, private wildlife preserves, zoological institutions, equine and camel racing stables, and ultra-high-net-worth animal guardians. 

The emotional tone balances absolute regulatory rigor with veterinary empathy and prestigious white-glove handling. Visually, the design system combines **Corporate Modernism** with an **Editorial Luxury** sensibility:
- Spatial airiness and generous negative margins inspire composure and confidence.
- Crisp, aerodynamic structural layouts mirror the precision and forward speed seen in high-velocity flight imagery.
- Balanced contrasts pair deep maritime slate blues with soft, lavender-tinged atmospheric off-whites and muted champagne-gold accents, avoiding sterile industrial cliches while sustaining clinical reliability.

## Colors

The palette directly honors the precision deep navy from falcon iconography, framed by luminous tinted whites and subtle desert-inspired gold tones.

- **Primary (`#0B1D3A`)**: Sovereign Navy. Conveys institutional authority, international customs expertise, and navigational command. Used for key headlines, dark-fill hero blocks, brand emblems, and primary buttons.
- **Secondary (`#D4AF37`)**: Royal Falcon Gold / Muted Sand. Used sparingly for clearance tier badges, verification seals, active status rings, and critical callouts to reflect prestige handling without gaudiness.
- **Tertiary (`#5A6785`)**: Air-Transit Slate. Serves as supporting structural lines, secondary metadata labels, iconography, and subtle ambient gradients.
- **Neutral Canvas (`#F6F7FB`)**: Alabaster Mist. A cool, lavender-tinted porcelain white that softens stark visual strain and establishes an airy, clean background.
- **Surface Elevation Containers**:
  - `surface-card`: `#FFFFFF` with whisper-fine border `#E5E9F2`.
  - `surface-tint`: `#EEF2FA` for inset data panels, flight timeline trackers, and quarantine chamber metrics.
  - `surface-dark`: `#0B1D3A` for high-impact dark modular cards, mimicking modern luxury fintech dashboards.

## Typography

The type system blends the editorial elegance of **Newsreader** with the hyper-legible, geometric clarity of **Plus Jakarta Sans**. 

- **Newsreader** anchors prominent narrative titles, section anchors, and trust statements, conveying decades of trade compliance, diplomacy, and veterinary integrity.
- **Plus Jakarta Sans** powers real-time manifests, biometric updates, cabin temperature telemetries, and operational actions. It remains pristine and readable even at condensed dashboard sizes.
- Use `label-sm` in full uppercase for CITES permit classifications, IATA LAR status tags, and waypoint markers.

## Layout & Spacing

The layout is built upon a balanced 12-column responsive fluid grid with disciplined maximum container limits (max-width: 1320px). 

- **Desktop (≥ 1024px)**: 12 columns with `gutter: 1.5rem` and outer page margin of `3rem` to `4rem`. Sections breathe through vertical gaps of `space-2xl` to mimic curated luxury portfolios.
- **Tablet (768px - 1023px)**: 8 columns with `gutter: 1.25rem` and `margin: 2rem`. Cards flex into 2-column stacked groupings.
- **Mobile (< 768px)**: 4 columns with `gutter: 1rem` and `margin: 1.25rem`. Complex logistics cards cascade into vertically stacked modules with full touch targets.

Layout modules replicate the serene composition in modern tech hero layouts: generous whitespace, high-prominence intro decks with centered or asymmetrical value propositions, and asymmetric card clusters (e.g., a 7-column primary feature card paired with two 5-column stacked operational data cards).

## Elevation & Depth

This design system favors **tonal layering with ultra-soft ambient indigo shadows**, deliberately avoiding harsh dropshadows:

- **Level 0 (Flat / Ground)**: `#F6F7FB` base screen tone.
- **Level 1 (Card & Module Resting)**: `#FFFFFF` surface accompanied by a subtle hairline border (`1px solid #E5E9F2`) and an ambient tinted shadow: `box-shadow: 0 4px 20px -2px rgba(11, 29, 58, 0.04), 0 2px 6px -1px rgba(11, 29, 58, 0.02)`.
- **Level 2 (Hover & In-Transit Cards)**: `box-shadow: 0 12px 32px -4px rgba(11, 29, 58, 0.08), 0 4px 12px -2px rgba(11, 29, 58, 0.03)`, slightly elevating the active manifest or species clearance card.
- **Level 3 (Overlays, Flight Track Drawers, Modals)**: `box-shadow: 0 24px 48px -8px rgba(11, 29, 58, 0.16)`.
- **Inverted Dark Cards**: Primary deep navy backgrounds (`#0B1D3A`) rely on gentle interior ambient glows (`box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.1)`) instead of heavy external drop shadows to preserve architectural discipline.

## Shapes

The shape hierarchy employs a medium-high curvature level (`roundedness: 2`), reflecting the organic curvature of aerodynamic flight paths, avian wings, and approachable veterinary stewardship:

- **Primary Cards & Large Panels**: Standardized at `rounded-xl` (`1.5rem` / `24px`) to create safe, welcoming visual containers for imagery, compliance logs, and service pillars.
- **Inner Data Cells & Nested Blocks**: Scaled at `rounded-lg` (`1rem` / `16px`).
- **Interactive Controls, Inputs & CTAs**: Shaped at `0.5rem` (`8px`) for structured inputs, while conversion-driven pill forms (`9999px`) are reserved exclusively for contextual tags, status badges, and hero CTA capsules.

## Components

### Buttons
- **Primary Action**: Deep Navy (`#0B1D3A`) fill with crisp white text, pill-shaped (`border-radius: 9999px`), padding `12px 28px`. Hover shifts to `#162E56` with micro-lift transition (`transform: translateY(-1px)`).
- **Secondary Action**: Crisp white surface with fine border (`1px solid #D1D9E7`), text color `#0B1D3A`. Hover brings soft background tint `#F0F4FC`.
- **Gold Accent / VIP Brokerage CTA**: Subtle warm gold fill (`#D4AF37`) with dark navy typography for high-tier customs expediting services.

### Cards & Grid Containers
- **Bento & Feature Cards**: Generous internal padding (`space-lg` to `space-xl`), `rounded-xl`, pristine white background or deep navy hero fills. Borders are kept whisper-light (`1px solid #E5E9F2`). Highlighting uses soft 3D visual badges or floral/wildlife photography anchors.
- **Status & Metric Cards**: Include clear typographic contrast: smaller uppercase labels, followed by bold numerical data and subtle compliance icons.

### Badges & Chips
- **Permit & Regulatory Badges**: Rounded pills with 6px horizontal padding and 2px vertical padding. 
  - *Approved / CITES Validated*: Light emerald tint background with deep pine text.
  - *Transit In-Progress*: Soft lavender-blue background with `#0B1D3A` text.
  - *Quarantine Monitored*: Pale amber tint with deep gold text.

### Input Fields & Forms
- Minimalist inset fields with `0.5rem` border radii, white background, `1px solid #D7DEE9` contour. Active focus triggers a 2px highlight in `#0B1D3A` without jarring neon glows.

### Lists & Manifest Feed
- Clean alternating rows or border-separated items with integrated timeline ticks. Subtle status dots indicate live transit milestones (e.g., Health Inspection Passed, Tarmac Climate Control Active, Border Clearance Dispatched).