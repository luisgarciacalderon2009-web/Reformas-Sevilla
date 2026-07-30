---
name: Hydro-Professional Service System
colors:
  surface: '#f7f9ff'
  surface-dim: '#d5dae2'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4fc'
  surface-container: '#e9eef6'
  surface-container-high: '#e3e9f0'
  surface-container-highest: '#dde3eb'
  on-surface: '#161c22'
  on-surface-variant: '#424752'
  inverse-surface: '#2b3137'
  inverse-on-surface: '#ecf1f9'
  outline: '#727784'
  outline-variant: '#c2c6d4'
  surface-tint: '#115cb9'
  primary: '#003f87'
  on-primary: '#ffffff'
  primary-container: '#0056b3'
  on-primary-container: '#bbd0ff'
  inverse-primary: '#acc7ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#004859'
  on-tertiary: '#ffffff'
  tertiary-container: '#006177'
  on-tertiary-container: '#76ddff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#004491'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#b6ebff'
  tertiary-fixed-dim: '#47d6ff'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e60'
  background: '#f7f9ff'
  on-background: '#161c22'
  surface-variant: '#dde3eb'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style
The design system is built to convey reliability, clinical cleanliness, and modern efficiency for a high-end plumbing service. The brand personality balances the technical precision of a skilled tradesman with the approachability of a local professional. 

The aesthetic follows a **Corporate / Modern** style with subtle **Minimalist** influences. By utilizing heavy whitespace and a restricted color palette, the UI avoids the "clutter" often associated with home service websites, instead projecting an image of organized excellence and "sterile" cleanliness—essential for a service that enters a customer's home. The emotional response should be one of immediate relief and trust.

## Colors
This design system utilizes a high-contrast palette designed for clarity and urgency. 

- **Primary Blue (#0056b3):** Used for headers, primary icons, and branding elements. It symbolizes water and professional stability.
- **Accent Orange (#ff8c00):** Reserved exclusively for high-priority calls to action (CTAs) such as "Emergency Call" or "Request Quote." This creates a "stop-and-act" psychological trigger.
- **Turquoise (#00d2ff):** Used sparingly as a secondary accent for success states, active progress bars, or decorative elements that reinforce the water theme.
- **Graphite Gray (#343a40):** The primary color for typography and deep borders, providing better readability than pure black.
- **Foundation Colors:** Pure White is the primary canvas, with Light Gray used to differentiate sections and form fields.

## Typography
The typography system uses **Montserrat** for headlines to project confidence and strength through its geometric construction. **Inter** is used for all body copy and labels, ensuring maximum legibility on mobile devices even in harsh lighting conditions (e.g., a customer viewing their phone while dealing with a leak).

Hierarchies are strictly enforced through weight. Headlines should almost always be Bold (700) or SemiBold (600). Body text remains at Regular (400) weight to maintain a clean, airy feel. Use wide line-heights (1.5x minimum for body) to ensure the technical information is easy to scan.

## Layout & Spacing
The design system employs a **Fluid Grid** model based on an 8px square rhythm. 

- **Desktop:** 12-column grid with 24px gutters and 48px side margins. 
- **Mobile:** Single column with 16px side margins. 

The layout philosophy emphasizes "Generous Whitespace." Sections should be separated by `xl` spacing (80px) to prevent the user from feeling overwhelmed. Key service offerings should be placed in cards that span 4 columns on desktop or 12 on mobile, ensuring a clear vertical scan path.

## Elevation & Depth
Depth is achieved through **Ambient Shadows** and **Tonal Layers**. 

The background is predominantly White (#FFFFFF). Interactive elements like cards and buttons use a very soft, diffused shadow: `0px 4px 20px rgba(52, 58, 64, 0.08)`. This "lifts" the content off the page without appearing heavy or dated. 

When an element is hovered, the shadow should deepen slightly to `0px 8px 30px rgba(0, 86, 179, 0.12)`, using a blue-tinted shadow to reinforce the primary brand color. Surface containers in Light Gray (#F8F9FA) are used to group secondary information, such as footer areas or "How It Works" steps, providing a subtle contrast against the primary white background.

## Shapes
This design system uses the **Rounded** (Level 2) setting. 

All primary UI elements (Buttons, Input Fields, Cards) feature a 0.5rem (8px) corner radius. This choice avoids the clinical harshness of sharp corners while remaining more professional and "engineered" than full pill shapes. Large containers, such as hero image sections or testimonial blocks, use the `rounded-xl` (1.5rem/24px) setting to create a friendly, modern frame for visual content.

## Components

### Buttons
- **Primary:** Solid Primary Blue with white text. High-emphasis for navigation and standard actions.
- **CTA (Action):** Solid Orange with white text. Used for "Call Now" or "Emergency Repair."
- **Secondary:** Outline Primary Blue with 2px stroke. Used for "Learn More" or secondary service details.

### Cards
Cards are the primary vehicle for services. They must include an 8px border-radius, the standard ambient shadow, and a white background. Icons within cards should use the Primary Blue color.

### Input Fields
Inputs use the Light Gray (#F8F9FA) background with a subtle Graphite Gray placeholder. Upon focus, the border transitions to a 2px Primary Blue stroke with a soft blue outer glow.

### Chips & Badges
Small, rounded-full indicators used for "24/7 Service" or "Certified." Use Turquoise background with white text for positive attributes.

### Lists
Service lists should use custom Primary Blue "check" icons rather than standard bullets to reinforce the "problem solved" narrative.

### Floating Action Button (Mobile)
A persistent "Call Now" button should be anchored to the bottom right of the screen on mobile, using the Orange CTA color and a heavy shadow for immediate accessibility.