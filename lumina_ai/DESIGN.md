---
name: Lumina AI
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
  on-surface-variant: '#d1c6ab'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#999077'
  outline-variant: '#4d4632'
  surface-tint: '#edc200'
  primary: '#fff0c8'
  on-primary: '#3b2f00'
  primary-container: '#fdd000'
  on-primary-container: '#6e5900'
  inverse-primary: '#725c00'
  secondary: '#ffdb9f'
  on-secondary: '#422d00'
  secondary-container: '#ffb700'
  on-secondary-container: '#6b4b00'
  tertiary: '#f4f0ee'
  on-tertiary: '#31302f'
  tertiary-container: '#d7d4d2'
  on-tertiary-container: '#5d5b5a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe07d'
  primary-fixed-dim: '#edc200'
  on-primary-fixed: '#231b00'
  on-primary-fixed-variant: '#564500'
  secondary-fixed: '#ffdea9'
  secondary-fixed-dim: '#ffba26'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4100'
  tertiary-fixed: '#e5e2e0'
  tertiary-fixed-dim: '#c9c6c4'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#484645'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  mono-data:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base-unit: 4px
  container-padding: 20px
  stack-gap: 16px
  section-gap: 32px
  gutter: 12px
---

## Brand & Style

This design system targets high-performance sales professionals and executive leadership. The brand personality is **authoritative, kinetic, and predictive**. It aims to evoke a sense of "superpowered intelligence"—the feeling that the AI is an invisible but potent partner working ahead of the user.

The visual style is a fusion of **Glassmorphism** and **Futuristic Minimalism**. By layering translucent surfaces over a deep, monochromatic background, the interface gains spatial depth without clutter. The use of high-contrast yellow highlights serves as a functional signifier for "AI Intelligence," indicating when the system is active, thinking, or has prepared an actionable insight. 

Key attributes include:
- **Spatiality:** Content exists on distinct planes.
- **Precision:** Ultra-thin 1px borders and sharp typography.
- **Tactility:** Large, thumb-friendly touch targets with soft glowing feedback.

## Colors

The palette is anchored in **Deep Night Black (#0F0F0F)** to minimize ocular strain and create a premium "infinite depth" canvas. 

- **Primary Jonquil (#FDD000):** Used for primary conversion points and "Call Ready" states.
- **Accent Yellow (#FFB700):** Reserved for AI-driven insights, active processing states, and critical notification badges.
- **Surface Tiers:** **Jet (#2A2929)** and **Black Olive (#444342)** are used for card backgrounds and container elevations, always with a semi-transparent alpha channel (80-90%) to allow background blurs to pass through.
- **Functional Grays:** **Muted Gray (#969696)** is used for non-essential borders and secondary metadata.

## Typography

The system utilizes **Hanken Grotesk** for its clean, geometric, yet professional character. It provides the necessary weight for high-impact sales metrics while remaining legible at smaller sizes for CRM data.

**Geist** is introduced as a secondary mono-spaced utility font for metadata, labels, and AI-generated snippets to provide a technical, futuristic edge. 

**Usage Rules:**
- Headlines should use tighter letter spacing to maintain a "locked-in" editorial look.
- Use `label-caps` for section headers and categories to create clear vertical rhythm.
- Avoid font weights below 400 on dark backgrounds to prevent "smearing" on OLED screens.

## Layout & Spacing

This design system follows a **Mobile-First Fluid Grid** with a strict 4px baseline. 

- **Safe Zones:** A 20px horizontal margin is mandatory for all primary content containers.
- **Vertical Rhythm:** Elements are stacked using 16px (Medium) or 32px (Large) gaps to maintain a high-end, airy feel despite the dark theme.
- **AI-Focus Layout:** Critical AI insights should use a "Full Bleed" card style with 0px horizontal margin, or a 12px inset to distinguish them from standard CRM records.
- **Adaptation:** On larger screens (Tablet/Desktop), the 1-column mobile stack reflows into a 12-column grid with a maximum content width of 1200px.

## Elevation & Depth

Depth is communicated through **Tonal Stacking** and **Backdrop Blurs** rather than traditional black shadows.

1.  **Level 0 (Base):** Deep Night Black (#0F0F0F) - The background.
2.  **Level 1 (Cards):** Jet (#2A2929) at 85% opacity with a 20px Backdrop Blur. 1px solid border (#444342).
3.  **Level 2 (Modals/Overlays):** Black Olive (#444342) at 90% opacity. 1px solid border (#969696 at 30% opacity).
4.  **Level 3 (AI Active):** Primary Yellow glow. Use a 24px spread, 15% opacity yellow drop shadow to indicate "Live" or "Active" AI states.

All elevated surfaces must feature a 1px inner stroke (top and left) to simulate a light source coming from the top-left, enhancing the glass effect.

## Shapes

The system uses a **Rounded** shape language to soften the futuristic aesthetic and make the tool feel more approachable.

- **Standard Cards:** 20px (`rounded-lg`)
- **Buttons:** Full Pill (`rounded-full`) for primary actions; 16px for secondary.
- **Input Fields:** 12px for a precise, modern look.
- **AI Tooltips:** 8px to distinguish small utility elements from larger containers.

## Components

### Buttons
- **Primary:** Pill-shaped, #FDD000 background, black text. Feature a subtle outer glow (box-shadow: 0 4px 14px 0 rgba(253, 208, 0, 0.39)).
- **Glass/Secondary:** Translucent #FFFFFF at 10% opacity, 1px border, white text.

### Cards
- Surfaces must use `backdrop-filter: blur(16px)`.
- Padding should be a consistent 20px.
- Use #FFB700 for a thin vertical "intent bar" on the left side of cards that require immediate attention.

### Input Fields
- Dark, recessed look. Background #0F0F0F with a 1px border #444342.
- Focus state: Border color changes to #FDD000 with a 2px inner glow.

### Bottom Navigation
- A floating "island" bar. 
- Background: #2A2929 at 80% opacity.
- Icons: 2px stroke weight, minimal line style. Active state icon uses #FDD000.

### AI Pulse
- A unique component: A 4px glowing dot next to AI-generated text or buttons that pulses slowly between 40% and 100% opacity to indicate background processing.