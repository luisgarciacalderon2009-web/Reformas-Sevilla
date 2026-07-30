---
name: Terracotta & Stone
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4e453e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#80756d'
  outline-variant: '#d2c4bb'
  surface-tint: '#705a49'
  primary: '#322214'
  on-primary: '#ffffff'
  primary-container: '#4a3728'
  on-primary-container: '#bba08c'
  inverse-primary: '#dec1ac'
  secondary: '#705b40'
  on-secondary: '#ffffff'
  secondary-container: '#fbdebb'
  on-secondary-container: '#766145'
  tertiary: '#252522'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b3b38'
  on-tertiary-container: '#a7a5a0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbddc7'
  primary-fixed-dim: '#dec1ac'
  on-primary-fixed: '#28180b'
  on-primary-fixed-variant: '#574333'
  secondary-fixed: '#fbdebb'
  secondary-fixed-dim: '#dec2a1'
  on-secondary-fixed: '#271904'
  on-secondary-fixed-variant: '#56432a'
  tertiary-fixed: '#e5e2dd'
  tertiary-fixed-dim: '#c9c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system is built on the pillars of craftsmanship, local heritage (Sevilla), and architectural precision. The brand personality is that of a "Master Artisan"—expert and reliable, yet accessible and warm. 

The visual style blends **Modern Minimalism** with **Tactile / Skeuomorphic** hints. It uses expansive white space to denote transparency and "breathing room" in construction, contrasted against high-quality photography of materials like plaster, oak, and stone. The aesthetic avoids the coldness of industrial tech, opting instead for a "Structured Organic" feel that mirrors a well-executed home renovation.

## Colors
The palette is rooted in the earth tones of Seville’s architecture. 
- **Primary (Dark Brown):** Represents the "Solid Ground" and structural integrity. Used for primary headings and heavy structural elements.
- **Secondary (Warm Beige):** Acts as the "Craftsman’s Touch." Used for highlights, active states, and accents that draw the eye to detail.
- **Tertiary (Stone White):** A warm off-white used for section backgrounds to prevent the clinical feel of pure hex white.
- **Neutral (Carbon):** Used exclusively for body text to ensure maximum legibility against the light backgrounds.

## Typography
Typography reflects the balance between modern engineering and classic aesthetics. 
- **Headings:** Manrope provides a geometric yet friendly structure. High-level displays use tighter letter spacing to feel "built" and compact.
- **Body:** Work Sans is chosen for its exceptional clarity in professional and service-oriented contexts. It maintains a grounded, neutral tone.
- **Labels:** Use uppercase tracking to denote categories (e.g., "KITCHEN," "BATHROOM," "FULL RENOVATION") to provide a secondary layer of hierarchy without competing with headlines.

## Layout & Spacing
This design system utilizes a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). 

The layout philosophy is "Photography-First." Large-scale imagery should occupy full-width or large column spans (8-10 columns) to showcase craftsmanship. Spacing between sections is intentionally generous (120px+) to evoke a premium, unhurried feeling of quality. Margins are wide to frame content like an architectural blueprint.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** rather than aggressive shadows. 
- **Surface Level:** Tertiary (Stone White) provides the base.
- **Elevated Level:** Pure White cards are used to "pop" content off the warm background.
- **Shadows:** When used, shadows are "Ambient Shadows"—extremely soft, using a 5% opacity of the Primary color (Brown) to maintain a warm, natural feel. 
- **Interactions:** Elements should feel "pressed" into the page rather than floating far above it, emphasizing stability.

## Shapes
The shape language is **Soft (0.25rem)**. This subtle rounding softens the "hard" edges of the construction industry, making the brand feel more approachable and domestic. Large image containers may use `rounded-lg` (0.5rem) to create a window-like effect into the renovated spaces.

## Components
- **Buttons:** Primary buttons are solid Primary color with white text, using `body-md` bold. Secondary buttons use a thick 2px border in Primary color with no fill (Ghost style) to signify transparency.
- **Cards:** Project cards should have a "Border-Bottom" highlight in the Secondary (Beige) color when hovered, creating a subtle tactile response.
- **Input Fields:** Professional and sturdy. Use a 1px border in a lightened version of the Primary color. On focus, the border thickens to 2px in the Secondary color.
- **Lists:** Service lists should use custom checkmarks in the Secondary (Beige) color to reinforce the "Quality Checked" narrative.
- **Before/After Slider:** A critical component for this system. A vertical handle using a Secondary color circular grip to allow users to compare renovation results.
- **Process Timeline:** A vertical line component using the Primary color to walk clients through the "Estimate -> Design -> Build" journey.