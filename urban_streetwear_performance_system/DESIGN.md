---
name: Urban Streetwear Performance System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e3bfb1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#aa8a7d'
  outline-variant: '#5a4136'
  surface-tint: '#ffb596'
  primary: '#ffb596'
  on-primary: '#581e00'
  primary-container: '#ff6600'
  on-primary-container: '#561d00'
  inverse-primary: '#a33e00'
  secondary: '#ffb599'
  on-secondary: '#5a1c00'
  secondary-container: '#f66018'
  on-secondary-container: '#4f1700'
  tertiary: '#4ae176'
  on-tertiary: '#003915'
  tertiary-container: '#00ae4f'
  on-tertiary-container: '#003814'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb596'
  on-primary-fixed: '#360f00'
  on-primary-fixed-variant: '#7c2e00'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7f2b00'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '900'
    lineHeight: 52px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '900'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 26px
    fontWeight: '800'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 28px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.03em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-badge:
    fontFamily: Montserrat
    fontSize: 11px
    fontWeight: '800'
    lineHeight: 12px
    letterSpacing: 0.08em
  label-action:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '800'
    lineHeight: 16px
    letterSpacing: 0.05em
  price-hero:
    fontFamily: Montserrat
    fontSize: 38px
    fontWeight: '900'
    lineHeight: 40px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system is engineered for an aggressive, high-energy streetwear e-commerce platform rooted in urban culture and sneakerhead dynamics. The visual identity embodies raw confidence, speed, exclusivity, and uncompromising conversion focus. It speaks directly to young, style-conscious consumers seeking premium sneaker silhouettes at competitive price points.

The aesthetic fuses **High-Contrast / Bold** streetwear typography with **Dark Mode Technical Brutalism**. Deep, light-absorbing obsidian backgrounds let product photography leap forward, while high-voltage electric orange drives behavioral focus toward purchase actions, countdown timers, price anchors, and conversion triggers. Structural borders and geometric modules establish trust and technical precision, counteracting visual clutter with razor-sharp alignment.

## Colors

The palette is tuned specifically for deep dark interfaces with vivid high-contrast focal points:

- **Primary (`#ff6600`) & Primary Hover (`#ea580c`):** Electric Street Orange. Reserved for high-value transactional triggers, flash-offer badges, active size selectors, checkout CTAs, and promotional accents.
- **Secondary (`#ea580c`):** Deep Flame Orange. Used for active interaction states, subtle linear gradients behind hero products, and pressed states.
- **Tertiary (`#22c55e`):** Trust Green. Applied strictly to in-stock badges, secure checkout locks, and verified shipping indicators.
- **Neutral Surface Hierarchy:**
  - Base Canvas: `#0a0a0a` (Pitch Black)
  - Surface Card / Modals: `#111111` (Deep Charcoal)
  - Elevated Container / Hover Rows: `#18181b` (Zinc Dark)
  - Interactive Structural Borders: `#27272a` (Zinc 800)
- **Typography Neutrals:**
  - Primary Titles & Headers: `#ffffff` (Solid White)
  - Body & Specifications: `#d4d4d8` (Zinc 300)
  - Secondary Metadata & Inactive Labels: `#a1a1aa` (Zinc 400)

## Typography

Typography establishes an intentional contrast between raw, high-impact athletic branding and surgical technical legibility:

- **Display & Headline Levels (`Montserrat`):** All major headings, prices, action buttons, and sale callouts utilize bold to black weights (700-900) set in uppercase. Tight tracking on ultra-large headings conveys speed, while uppercase tracking on buttons and badges enhances readability in condensed layouts.
- **Body & Specs (`Inter`):** Product technical details, shipping estimates, size chart descriptions, and guarantee microcopy use clean geometric sans-serif styling to guarantee immediate clarity even on low-resolution mobile devices.
- **Pricing Notation:** Prices feature `Montserrat` 900 with currency symbols superscripted or positioned adjacent at 60% font size, maximizing instant cognitive parsing.

## Layout & Spacing

The layout is built around a rigorous mobile-first commerce grid engineered for high product density and lightning-fast checkout flow:

- **Grid Framework:**
  - **Mobile (< 768px):** 4-column fluid layout with `1rem` outer margins and `0.75rem` gutters. Product feeds render as a dynamic 2-column card stack.
  - **Tablet (768px - 1024px):** 8-column layout with `1.5rem` outer margins and `1rem` gutters. Product feeds render across 3 columns.
  - **Desktop (> 1024px):** 12-column fixed/max-width container bounded at `1320px` with `2.5rem` margins and `1.5rem` gutters.
- **Vertical Spacing Rhythm:** Component interiors operate on strict multiples of 4px and 8px (`0.5rem`, `1rem`, `1.5rem`). Section separators employ generous rhythm (`2.5rem` on mobile, `4rem` on desktop) to let dark surfaces breathe between dense catalog grids.

## Elevation & Depth

Visual depth avoids excessive diffused blurs in favor of structural dark layering, neon optical glows, and tactile physical framing:

- **Level 0 (Base Surface):** Deep black `#0a0a0a` background layer.
- **Level 1 (Surface Cards & Shelves):** Solid `#111111` bounded by a 1px structural outline of `#27272a`.
- **Level 2 (Active Dropdowns & Flyouts):** Solid `#18181b` with a 1px border of `#3f3f46` and a crisp, dark drop shadow: `0 10px 25px -5px rgba(0, 0, 0, 0.8)`.
- **Level 3 (Cart Drawer & Floating Modals):** Backdrop blur `12px` over an 85% opacity dark overlay (`rgba(10, 10, 10, 0.85)`), layered with an inner edge highlight: `1px solid rgba(255, 255, 255, 0.08)`.
- **Accent Glow (Conversion Lighting):** Active selections and primary CTAs trigger a controlled, radiant orange underglow: `0 0 20px -3px rgba(255, 102, 0, 0.45)`.

## Shapes

The system implements a sharp, industrial silhouette profile using roundedness level `1` (Soft):

- **Interactive Core:** Buttons, input inputs, size chips, and filter toggles have a standard radius of `0.25rem` (4px). This creates an agile, aggressive streetwear silhouette reminiscent of industrial sneaker tags and technical apparel.
- **Product Tiles & Cards:** Outer radius set to `0.5rem` (8px), maintaining structured borders without appearing generic or overly rounded.
- **Badge Indicators:** Promos and stock tags use `0.125rem` (2px) or sharp `0px` chamfered styles for a cut-and-sew street aesthetic.
- **Avatars & Color Swatches:** Strict geometric circles (`rounded-full`) to differentiate functional color selections from rectangular size blocks.

## Components

### Header (Fixed Sticky)
- **Structure:** 64px height on mobile, 76px on desktop. Built with `#0a0a0a` background at 95% opacity with a `12px` backdrop blur and a bottom border of `1px solid #27272a`.
- **Elements:** High-impact lion crest brand mark left-aligned; centered quick navigation; right-aligned cart trigger icon featuring an orange notification pill badge with numeric counter in black bold typography.

### CTA & Buttons
- **Primary Purchase CTA:** Full-bleed on mobile or bold block desktop. Background: `#ff6600` transitioning to `#ea580c` on hover. Text: `#0a0a0a` (Solid Black), uppercase `Montserrat` Black (900), `letter-spacing: 0.05em`. Box shadow emits an ambient orange glow on hover.
- **Secondary CTA (Fast Checkout / PIX):** Background `#18181b`, border `1px solid #ff6600`, text `#ffffff`.
- **Ghost/Tertiary CTA:** Background transparent, border `1px solid #27272a`, text `#a1a1aa`, hover border `#ffffff`.

### Size Selectors (Grid 34 to 43)
- **Default State:** Rigid square-proportioned tiles (46px x 46px), background `#111111`, border `1px solid #27272a`, text `#ffffff`, font `Montserrat` Bold.
- **Active / Selected State:** Background `#ff6600`, border `1px solid #ff6600`, text `#0a0a0a`, equipped with `0 0 12px rgba(255, 102, 0, 0.4)`.
- **Disabled / Out of Stock:** Inactive opacity 35%, background `#0a0a0a`, border `1px solid #1c1917`, strike-through diagonal line across the number.

### Color Swatches
- 36px circular swatches wrapped in a `2px` transparent gap and a `1px` border of `#27272a`. On selection, an external ring of `#ff6600` with `2px` offset activates around the swatch.

### Product Card
- Background `#111111`, border `1px solid #27272a`, radius 8px, overflow hidden.
- Includes upper-left sale pill tag (`#ff6600`, text `#000000`, uppercase, 10px bold) and quick-favorite heart button top-right.
- Image area displays sneakers on dark stage lighting with a hover zoom (scale `1.05`, transition `300ms ease-out`).
- Footer displays model title in uppercase white, installment text in `#a1a1aa`, and bold anchor price in `#ff6600`.

### Cart Drawer (Slide-Over)
- Width: `100%` on mobile, `420px` on desktop. Slides from the right on top of a blurred `#0a0a0a` backdrop.
- Background: `#111111` with a left border of `1px solid #27272a`.
- Features a dynamic "Frete Grátis" progress bar in `#ff6600`, itemized product cards with quantity increment controls (`#18181b`), order subtotal in white bold, and high-visibility "FINALIZAR PEDIDO" button.

### Trust Badges & Guarantees
- 3-column micro-strip or horizontal icon list.
- Minimalist vector outlines in `#ff6600` (Shield, Fast Delivery Truck, Lock) paired with two-tier text: bold uppercase white title (`Montserrat`, 12px) over zinc subtext (`Inter`, 11px).