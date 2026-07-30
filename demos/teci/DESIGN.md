---
name: Teci Technical Service System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#6f5d00'
  on-secondary: '#ffffff'
  secondary-container: '#fdd828'
  on-secondary-container: '#705e00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#091b39'
  on-tertiary-container: '#7484a7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#ffe16a'
  secondary-fixed-dim: '#e8c404'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#b6c6ed'
  on-tertiary-fixed: '#091b39'
  on-tertiary-fixed-variant: '#374767'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered to project absolute technical competence, reliability, and precision for professional electrical services in Seville. The brand personality is "The Expert Engineer"—authoritative yet accessible, prioritizing clarity of information over decorative flair. 

The aesthetic blends **Minimalism** with **High-Contrast Technicality**. It utilizes a "Utility-First" visual language, where every element serves a functional purpose. High-contrast pairings between deep navy and electric gold evoke the duality of safety and power. The interface feels robust and structural, mirroring the physical reliability of high-quality electrical installations.

**Target Audience:** Homeowners requiring urgent repairs, commercial facility managers, and industrial contractors seeking certified technical expertise.
**Emotional Response:** Confidence, safety, promptness, and professional rigor.

## Colors

The palette is anchored by **Deep Navy (#0A192F)**, which serves as the foundation for all structural elements, text, and primary branding to establish a sense of "Corporate Professionalism." 

**Electric Gold (#F9D423)** is used exclusively for functional accents: Call-to-Actions (CTAs), emergency indicators, and status highlights. This creates a high-visibility "caution tape" effect that guides the user to the most critical actions.

- **Primary:** Navy for backgrounds, headers, and primary buttons.
- **Secondary (Accent):** Gold for primary CTAs and critical badges.
- **Tertiary:** Lightened navy for subtle containers and secondary navigation.
- **Neutral:** Cool grays and off-whites for background surfaces to maintain a clean, technical environment.
- **Error:** A sharp crimson used specifically for "Emergency" or "Power Outage" triggers.

## Typography

This design system uses a dual-sans-serif approach to balance impact with utility. 

**Montserrat** is used for headlines. Its geometric, wide stance conveys stability and modern infrastructure. It should be set with tight letter-spacing in larger sizes to feel "constructed."

**Inter** is the workhorse for all body copy, forms, and technical specifications. It was chosen for its exceptional legibility in data-heavy contexts and its neutral, systematic tone. 

- Use **Label-Caps** for technical categories, service IDs, and breadcrumbs.
- Maintain high contrast by using Primary Navy text on White backgrounds or White text on Primary Navy backgrounds. Avoid mid-tone grays for text.

## Layout & Spacing

The layout philosophy follows a **Rigid Grid** model. This reflects the order and precision of electrical wiring and schematics. 

- **Grid:** A 12-column system for desktop, 4-column for mobile. 
- **Rhythm:** An 8px base unit is used for all internal component spacing, while a 4px "micro-unit" handles technical labels and tight data clusters.
- **Alignment:** Strict left-alignment is preferred for all technical information to ensure fast scanning.
- **Breakpoints:** 
  - Mobile: < 640px (Margins: 16px)
  - Tablet: 641px - 1024px (Margins: 24px)
  - Desktop: > 1024px (Margins: 40px, Max-width: 1280px)

## Elevation & Depth

This system avoids soft shadows and organic depth. Instead, it uses **Tonal Layering** and **Bold Outlines** to define hierarchy.

- **Flat Depth:** Surfaces sit on the same plane, separated by 1px solid borders in `#E2E8F0` or `#0A192F`.
- **Tonal Contrast:** Use Primary Navy for headers or footers to "anchor" the page. Secondary containers use a subtle off-white background to distinguish them from the main canvas.
- **High-Contrast Focus:** Elements that require focus (like active input fields) do not glow; they receive a 2px solid Electric Gold border.
- **No Shadows:** Shadows are eliminated in favor of "Hard Edges" to maintain a technical, schematic feel.

## Shapes

The design system utilizes **Sharp (0px)** roundedness. 

Right angles are used across all cards, buttons, and inputs to reinforce the "technical" and "industrial" nature of the service. Rounded corners are perceived as softer and more consumer-facing; sharp corners communicate structural integrity and professional precision. 

The only exception to the "sharp" rule is circular iconography and toggle switches, where the circle serves a functional symbolic purpose.

## Components

### Buttons
- **Primary:** Solid Primary Navy background, White text, sharp corners. High weight.
- **Urgent/Action:** Solid Electric Gold background, Primary Navy text. Used for "Call Now" or "Book Service."
- **Ghost:** Transparent background, 2px Primary Navy border.

### Cards
- White background with a 1px solid stroke (Navy).
- No border-radius.
- Internal padding is strictly 24px or 32px for clear information grouping.

### Emergency Badges
- High-visibility components using a diagonal stripe "hazard" pattern in the background (Gold/Navy) or a solid Error Red block.
- Positioned in the top-right of cards or pinned to the top of the viewport.

### Input Fields
- 1px Navy border, sharp edges.
- Labels are always visible above the field in **label-caps** style.
- Active state: 2px Electric Gold border.

### Lists
- Technical specs and service features use "Plus" (+) icons or "Arrow" icons as bullets, never circles.
- Separated by 1px horizontal dividers.