---
name: Seville Boutique Elegance
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#50443e'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#82746d'
  outline-variant: '#d4c3bb'
  surface-tint: '#7a5642'
  primary: '#7a5642'
  on-primary: '#ffffff'
  primary-container: '#dcae96'
  on-primary-container: '#62412e'
  inverse-primary: '#ecbda4'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#60603e'
  on-tertiary: '#ffffff'
  tertiary-container: '#bbba91'
  on-tertiary-container: '#4a4a2a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ecbda4'
  on-primary-fixed: '#2e1506'
  on-primary-fixed-variant: '#603f2d'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e6e5b9'
  tertiary-fixed-dim: '#cac99f'
  on-tertiary-fixed: '#1d1d03'
  on-tertiary-fixed-variant: '#484828'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 32px
  section-padding: 80px
  mobile-margin: 20px
---

## Brand & Style
The design system embodies the high-end boutique experience of a luxury hair salon in Seville. The personality is warm, feminine, and deeply refined, blending traditional Andalusian sophistication with modern minimalism. 

The aesthetic is centered on **Minimalism with Tactile Accents**, prioritizing generous white space to evoke a sense of calm and exclusivity. It utilizes soft, organic layering to create a "boutique" feel that is professional yet deeply inviting. The emotional response should be one of pampering, confidence, and timeless beauty.

## Colors
The palette is inspired by the warm light of Seville and high-end cosmetic textures.
- **Primary (Dusty Pink):** Used for soft backgrounds, accent surfaces, and secondary call-to-actions. It provides the feminine warmth.
- **Secondary (Aged Gold):** Reserved for high-value details like borders, icons, and primary button states. It adds the "high-end" signature.
- **Tertiary (Cream/Ivory):** The foundational canvas color. It replaces pure white to provide a softer, more luxurious "paper-like" quality.
- **Neutral (Charcoal):** Used for typography to ensure legibility while maintaining a softer contrast than pure black.

## Typography
The typography system relies on a high-contrast pairing between a sophisticated Serif and a functional Geometric Sans.
- **Headlines:** Playfair Display is used for all major headings. Its high stroke contrast communicates luxury and editorial style. Use tighter tracking for larger display sizes.
- **Body & UI:** Montserrat provides a clean, modern balance. Its geometric clarity ensures the brand feels contemporary and accessible.
- **Labels:** Small labels and navigation items should use Montserrat in uppercase with increased letter spacing to create an airy, premium feel.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain an editorial, magazine-like composition. 
- **Whitespace:** Use aggressive vertical spacing (section padding) to separate content. Elements should never feel crowded.
- **Grid:** A 12-column system is used. Service descriptions and gallery items should favor asymmetric layouts (e.g., spanning 5 columns or 7 columns) to avoid a standard "bootstrap" look.
- **Mobile:** Transition to a single-column flow with reduced margins, but maintain consistent 40-60px vertical gaps between distinct content blocks to preserve the airy feel.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows** rather than heavy outlines.
- **Surfaces:** Use the Cream (#FFFDD0) as the base layer, with Dusty Pink (#DCAE96) for raised container elements.
- **Shadows:** Apply very soft, diffused shadows with a slight warm tint (`rgba(220, 174, 150, 0.15)`). The blur radius should be high (20px+) with low offset to create a "floating" effect.
- **Interactions:** On hover, depth should increase subtly by expanding the shadow blur, suggesting the element is lifting toward the user.

## Shapes
The shape language is **Soft** and restrained. While sharp corners feel too clinical, overly rounded "pill" shapes feel too casual for a high-end salon. 
- **Standard Radius:** 4px (0.25rem) for cards and input fields.
- **Large Radius:** 12px (0.75rem) for featured image containers and large modals.
- **Accents:** Use circular crops for stylist profiles or specific decorative elements to break the linear grid.

## Components
- **Buttons:** Primary buttons use a Secondary (Gold) 1px border with a transparent background or a solid Dusty Pink fill. Typography inside buttons must be `label-md` (uppercase, tracked out).
- **Service Cards:** Minimalist tiles using the Cream background. Use thin Gold dividers (0.5px) to separate price from service name. No heavy borders; let the soft shadow define the edge.
- **Input Fields:** Bottom-border only or very light Cream-on-Pink containers. Use the Aged Gold for the focus state indicator.
- **Gallery Grid:** Use varying aspect ratios (alternating between 4:5 and 1:1) to create an editorial flow. Images should have a subtle 4px corner radius.
- **Chips/Labels:** Used for service categories (e.g., "Color," "Styling"). These should be Dusty Pink text on a slightly lighter tint of the same hue, with no border.
- **Booking Bar:** A persistent, narrow component at the bottom of the screen or top navigation, anchored in Aged Gold to highlight the primary conversion.