---
name: BioPrecision AgroTech
colors:
  surface: '#0f1513'
  surface-dim: '#0f1513'
  surface-bright: '#343b38'
  surface-container-lowest: '#090f0d'
  surface-container-low: '#171d1b'
  surface-container: '#1b211f'
  surface-container-high: '#252b29'
  surface-container-highest: '#303634'
  on-surface: '#dee4e0'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dee4e0'
  inverse-on-surface: '#2b322f'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#94de2d'
  on-secondary: '#1f3700'
  secondary-container: '#7ac100'
  on-secondary-container: '#2c4900'
  tertiary: '#68dba9'
  on-tertiary: '#003825'
  tertiary-container: '#3eb686'
  on-tertiary-container: '#00422c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acf847'
  secondary-fixed-dim: '#91db2a'
  on-secondary-fixed: '#102000'
  on-secondary-fixed-variant: '#304f00'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#0f1513'
  on-background: '#dee4e0'
  surface-variant: '#303634'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  metric-val:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
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
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system embodies the fusion of advanced aerial robotics and modern agronomy. Built for agricultural producers, agronomists, and agribusiness enterprises seeking high-efficiency drone crop solutions, it projects precision, sustainability, and technological supremacy. 

The aesthetic is dark-mode AgroTech: deep, obsidian soil-toned surfaces contrasting with electric bio-luminescent greens. The design merges technical minimalism with subtle glassmorphism—featuring translucent HUD-like data cards, fine linear grid accents reminiscent of multispectral telemetry, and vibrant energetic glows that communicate real-time precision seeding, spraying, and diagnostic health monitoring.

## Colors

The palette is engineered to evoke synthetic vitality against a nocturnal, data-rich landscape:

- **Primary (`#10B981`)**: Radiant emerald green used for primary interactive states, key success notifications, and drone telemetry highlights.
- **Secondary (`#84CC16`)**: Bio-tech lime green, utilized for high-velocity metrics, efficiency deltas, and focal point badges.
- **Tertiary (`#059669`)**: Deep forest emerald providing rich baseline contrast, active container strokes, and focused UI foundations.
- **Neutral (`#0B110F`)**: Deep bio-obsidian black, grounding the entire interface with an architectural, darkroom cockpit environment. Accents of soft slate-green (`#1E2922`) and light frost (`#F0FDF4`) define structural card backdrops and high-readability text elements respectively.

## Typography

The pairing creates immediate tension between industrial precision and humanistic clarity:

- **Space Grotesk** commands all headings, statistical metrics, KPI displays, and UI pill tags. Its mechanical terminals and distinct geometric glyphs reflect aeronautical instruments and autonomous flight computers.
- **Manrope** drives all contextual narratives, technical specifications, and body copy. Highly legible on high-density OLED and dark surfaces, its open letterforms ensure effortless reading of agricultural telemetry and service protocols.

## Layout & Spacing

Layout adheres to a responsive 12-column grid system built on an 8pt architectural rhythm, collapsing to 8 columns on tablet devices and 4 columns on mobile viewports. 

Desktop displays implement generous outer margins (`2.5rem`) and structural gutters (`1.5rem`) to evoke expansive crop fields and unconstrained flight paths. Dynamic metric cards and service modules snap cleanly to predefined multi-column bands (3, 4, 6, or 12 columns), allowing telemetry overlays to float effortlessly over geospatial backgrounds and interactive topography models.

## Elevation & Depth

Visual hierarchy leverages a calibrated dark-field glassmorphism structure with micro-luminescent layering:

- **Layer 0 (Canvas Base):** Deep bio-obsidian surface (`#0B110F`) with ambient background radial gradients (`rgba(16, 185, 129, 0.08)` blur 120px).
- **Layer 1 (Card & Module Foundation):** Translucent composite panels built with `rgba(16, 28, 23, 0.65)` and `backdrop-filter: blur(16px)`. Border boundaries are defined by low-opacity emerald hairline outlines (`1px solid rgba(16, 185, 129, 0.2)`).
- **Layer 2 (Floating Overlays & Menus):** `rgba(20, 36, 29, 0.85)` with `backdrop-filter: blur(24px)`, enclosed with a dual-edge shadow: `0 20px 40px -10px rgba(0, 0, 0, 0.7)` combined with a soft emerald rim illumination (`0 0 15px rgba(16, 185, 129, 0.15)`).
- **Layer 3 (Hover States & Active Telemetry):** Accent boundaries bloom to `rgba(132, 204, 22, 0.45)` with a targeted outer aura glow (`0 0 24px rgba(16, 185, 129, 0.35)`).

## Shapes

A balanced `roundedness: 2` forms the structural identity. Standard cards, telemetry panes, and input fields adopt a `0.5rem` (8px) radius, while featured service hero panels scale to `1rem` (16px). This subtle radius preserves the high-precision, technical ethos of aerospace hardware while avoiding harsh brutalist corners. Interactive micro-elements like trust pills, status nodes, and drone status tags employ full rounded pills (`9999px`) for quick scanability and modern digital elegance.

## Components

### Buttons
- **Primary CTA:** Solid gradient background from `#10B981` to `#059669`, crisp white text (`#FFFFFF`), subtle emerald outer glow (`0 0 18px rgba(16, 185, 129, 0.4)`), uppercase `Space Grotesk` tracking (`0.04em`). On hover, dynamic brightness jump with lime halo.
- **Secondary / Ghost CTA:** Frosted surface (`rgba(16, 185, 129, 0.08)`), framed with a `1px` border in `#10B981`, text in `#10B981`. Smooth hover transition to solid emerald fill.

### Cards & Service Tiles
- Crafted with blurred glassmorphism backing (`backdrop-filter: blur(14px)`).
- Integrated with hairline top-edge reflections (`1px solid rgba(255, 255, 255, 0.12)`) and inner subtle borders (`rgba(16, 185, 129, 0.15)`).
- Accommodates iconography rendered in neon lime (`#84CC16`) and technical drone service bullet points.

### Trust Badges & Performance Metrics
- **Performance Pill:** High-contrast, micro-bordered indicators with pulsating live-status dots (`#84CC16` ping animation) indicating active flight diagnostics or GPS precision thresholds.
- **Metric Highlights:** Large tabular figures (`metric-val`) in `#F0FDF4` accompanied by upward delta chips in vibrant `#84CC16` with sub-captions tracking hectares per hour, fuel savings, and chemical optimization percentages.

### Input Fields & Controls
- Form fields are dark translucent trenches (`rgba(11, 17, 15, 0.8)`) lined with `rgba(16, 185, 129, 0.25)`.
- Active focus state activates an emerald halo (`border-color: #10B981; box-shadow: 0 0 0 3px rgba(16, 185, 129, 0.2)`).
- Checkboxes and toggles render in mechanical emerald blocks with crisp lime checkmark indicators.