---
name: FRACAS
colors:
  surface: '#fcf8ff'
  surface-dim: '#dcd6fa'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f1ff'
  surface-container: '#f0ebff'
  surface-container-high: '#eae5ff'
  surface-container-highest: '#e4dfff'
  on-surface: '#1b1832'
  on-surface-variant: '#5b3f46'
  inverse-surface: '#302d49'
  inverse-on-surface: '#f3eeff'
  outline: '#8f6f76'
  outline-variant: '#e3bdc5'
  surface-tint: '#ba005c'
  primary: '#b60059'
  on-primary: '#ffffff'
  primary-container: '#e30071'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb1c5'
  secondary: '#725c00'
  on-secondary: '#ffffff'
  secondary-container: '#fdd000'
  on-secondary-container: '#6e5900'
  tertiary: '#3255bb'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e6ed5'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#ffb1c5'
  on-primary-fixed: '#3f001b'
  on-primary-fixed-variant: '#8f0045'
  secondary-fixed: '#ffe07c'
  secondary-fixed-dim: '#ecc200'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#564500'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b5c4ff'
  on-tertiary-fixed: '#00164e'
  on-tertiary-fixed-variant: '#143ea4'
  background: '#fcf8ff'
  on-background: '#1b1832'
  surface-variant: '#e4dfff'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 96px
    fontWeight: '800'
    lineHeight: 92px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 52px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 58px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-md-mobile:
    fontFamily: Syne
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Epilogue
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.05em
spacing:
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  space-4xl: 6rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1.25rem
  margin-desktop: 3rem
---

## Brand & Style

This design system channels the visceral, anarchic energy of street art festivals and physical printmaking workshops. The core visual philosophy unites Neo-Brutalism with authentic screenprint/risograph imperfections: intentional ink misregistration (registration shifts), raw mechanical halftone screens, high tactile density, and kinetic typography. It communicates urgency, public joy, civic disruption, and artisanal precision.

### Target Audience & Emotional Impact
- **Audience:** Festival attendees, street performers, local collectives, cultural tourists, and contemporary art enthusiasts spanning ages 18 to 65.
- **Emotional Response:** Euphoric cultural immersion, physical tactility, spontaneous playfulness, and subcultural vitality.
- **Tone:** Loud, unvarnished, direct, radically welcoming, and celebratory.

### Stylistic Directives
- **Risograph Misregistration:** Visual accents and secondary elements frequently use an offset pseudo-shadow (solid ink shifts without blur) simulating misaligned two-pass drum printing.
- **Halftone & Texture:** Use dot screens and grain overlays in imagery and hero backgrounds to evoke uncoated kraft paper stock and heavy ink coverage.
- **Sharp Physical Boundaries:** Surfaces clip cleanly without soft synthetic drop shadows. Structural rules mimic razor-cut stencils and paste-up zines.

## Colors

The palette reproduces mechanical ink separation on warm, unbleached cotton-wood pulp paper. Inks interact through flat overprinting simulation rather than opacity washes.

### Palette Architecture
- **Primary Ink (Electric Fluo Pink - `#FF2A85`):** Used for primary CTAs, critical badges, high-impact headline highlights, and active states.
- **Secondary Ink (Solar Cadmium Yellow - `#FFD200`):** Acts as high-visibility backing, date counters, sticker backgrounds, and warning highlights.
- **Tertiary Ink (Deep Cobalt Blue - `#0B39A0`):** Used for structural contrast, timetable headers, artist tags, and inverted contextual containers.
- **Key Ink (Night Navy Black - `#0E0B25`):** The master text, stroke, and boundary color. Pure `#000000` is strictly forbidden; all dark elements use this saturated printer's black.
- **Substrate (Raw Kraft Paper - `#F5EFEB`):** The universal application backdrop. Replaces digital pure white (`#FFFFFF`) to ground all vibrant inks in physical paper reality.
- **Overprint Artifact (`#861149`):** Represents the optical blend when Hot Pink overlaps Deep Cobalt in print, deployed on hover states, nested borders, and icon intersections.

### Application Rules
- Maintain high-contrast ratios: Navy text (`#0E0B25`) sits comfortably on Paper (`#F5EFEB`) and Solar Yellow (`#FFD200`).
- When Electric Pink is paired with Solar Yellow, anchor it with heavy Night Navy typography or borders to preserve legible contrast.
- Never use radial gradients or standard digital linear fades. Transitions must occur through solid block thresholds, dithering, or stepped halftone dot densities.

## Typography

Typography balances hyper-expressive display scale with robust editorial legibility.

- **Display & Large Headlines (Syne):** Provides punchy, unconventional European poster letterforms. Used for festival dates, artist names, headliners, and macro slogans. Case styling alternates between full uppercase display for impact and tight title case for narrative headers.
- **Body & Continuous Copy (Epilogue):** A sturdy grotesque with rich personality and structural ink traps that holds up under dense layouts, long artist bios, logistics, and legal notices.
- **Technical & Interactive Meta (Space Grotesk):** Brings precise, screen-printed poster production specs into tags, timestamps, venue coordinates, filters, and tickets. Always set with generous letter-spacing (`0.05em` to `0.08em`) and uppercase treatment where applicable.

## Layout & Spacing

Layouts follow a structured paste-up poster composition. Rhythm relies on visible vertical and horizontal module lines, intentional modular offsets, and dynamic density.

### Grid Foundations
- **Desktop (1024px+):** 12-column dynamic grid with a `1.5rem` (`24px`) gutter and `3rem` (`48px`) outer margins. Content zones can span full-bleed or pack into asymmetric column splits (e.g., 5-column sticky metadata against 7-column performance schedules).
- **Tablet (768px - 1023px):** 8-column grid with `1.25rem` (`20px`) gutters and `2rem` (`32px`) margins.
- **Mobile (320px - 767px):** 4-column column system with `1rem` (`16px`) gutters and `1.25rem` (`20px`) margins.

### Spacing Philosophy
Elements pack tightly into clear visual groupings bounded by thick rules, followed by abrupt, breathing-room gaps between distinct program blocks. Section breaks frequently feature high-contrast poster dividers rather than empty white space.

## Elevation & Depth

This system rejects soft, blurred lighting models. Elevation is entirely tactile, mechanical, and planar, reflecting wooden block relief and riso drum offset.

### The Misregistration Displacement Model
- **Level 0 (Flat Ground):** Elements rest directly on `#F5EFEB` with a solid `2px` or `3px` border in Night Navy (`#0E0B25`). No offset shadow.
- **Level 1 (Slight Lift - Cards, Tags):** Offset hard shadow of `4px 4px 0px 0px #0E0B25` or saturated ink offset `4px 4px 0px 0px #FF2A85`.
- **Level 2 (Active Focus / Interactive Elements):** Offset hard shadow of `6px 6px 0px 0px #0E0B25`.
- **Level 3 (Modals, Overlays, Floating Timetables):** Heavy physical stamp offset: `10px 10px 0px 0px #0E0B25` accompanied by an overprinted under-layer or solar yellow outline.

### Surface Treatment
Surfaces remain fully opaque. Translucency is achieved only through simulated ink multiplication (`mix-blend-mode: multiply` on graphic motifs), letting the warm paper substrate breathe through the layered inks.

## Shapes

The design system is strictly sharp (`roundedness: 0`). 

All buttons, cards, images, badges, and structural modules feature `0px` border-radius, reflecting trimmed card stock, linocut cuts, and wheat-paste street bills. 

### Geometric Accents
- Chamfered corner cuts (45-degree angle slices at 12px or 16px) may be applied to select featured banners, VIP passes, and date badges to emulate perforated, tearable festival tickets.
- Circular elements are reserved strictly for circular festival stamps, rotation badges ("FRACAS • OCCITANIE • 2025"), and icon containers.

## Components

### Buttons
- **Primary Action (Loud):** Deep Solar Yellow (`#FFD200`) or Electric Pink (`#FF2A85`) background, `3px` solid `#0E0B25` border, bold `Space Grotesk` uppercase typography. Hard drop shadow: `4px 4px 0px 0px #0E0B25`.
- **Hover State:** Translate `-2px -2px` with shadow expanding to `6px 6px 0px 0px #0E0B25`.
- **Active State:** Translate `+2px +2px` with shadow collapsing to `2px 2px 0px 0px #0E0B25`.
- **Secondary Action:** Raw Paper (`#F5EFEB`) background, `2px` solid `#0E0B25`, sharp hover fill invert to `#0B39A0` with text reversing to `#FFFDF9`.

### Chips & Badges
- **Genre/Venue Chips:** Flat rects, `1px` or `2px` black border, `8px 12px` padding. Solid color-coded fills: `#FF2A85` (Dance & Circus), `#FFD200` (Street Theatre), `#0B39A0` with white text (Music/Sound Installations).
- **Status Badges ("Live", "Full", "Free"):** Sharp rectangular tags with `Space Grotesk` uppercase text and a solid `4px` square status pip.

### Cards (Artist & Performance Modules)
- **Structure:** Crisp `3px` solid `#0E0B25` stroke, base background `#FFFDF9`.
- **Media Presentation:** Performance photos receive a duotone or two-color riso filter (Cobalt Blue + Hot Pink) with a visible halftone dot texture.
- **Card Footer:** Thick horizontal divider rule (`2px` solid `#0E0B25`) separating performance location, time, and quick-save bookmark trigger.

### Lists & Timetables
- **Festival Lineup Rows:** Monospaced and tabular layout bounded by single hairline rules (`2px` solid `#0E0B25`).
- **Interactive Row States:** Hovering a timetable row floods the entire row with `#FF2A85` or `#FFD200`, abruptly inverting text color to create instantaneous street poster hierarchy.

### Checkboxes & Form Elements
- **Input Fields:** Uncoated cream paper surface (`#FFFDF9`), framed with `2px` solid `#0E0B25`. Label stacked above in `Space Grotesk` uppercase. Focus state creates a sharp `4px 4px 0px 0px #0B39A0` displacement.
- **Checkboxes:** Square boxes (`20px x 20px`), `2px` border. Checked state renders a solid inner ink square or cross-hatch, eliminating standard fluid checkmark animations.

### Festival-Specific Components
- **Sticker Badges:** Circular or angled rotated badges (`-4deg` to `+6deg`) pinned dynamically over cards or hero sections to denote "PREMIÈRE", "AU PARC", or "GRATUIT".
- **Ticket Stubs:** Modular cards featuring a dashed border divider (`border-style: dashed`) representing tear-off perforated entry sections with monospaced barcode/serial tokens.