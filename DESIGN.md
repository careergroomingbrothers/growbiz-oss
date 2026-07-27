---
name: Celestial Enterprise
colors:
  surface: '#13131b'
  surface-dim: '#13131b'
  surface-bright: '#393842'
  surface-container-lowest: '#0d0d15'
  surface-container-low: '#1b1b23'
  surface-container: '#1f1f27'
  surface-container-high: '#292932'
  surface-container-highest: '#34343d'
  on-surface: '#e4e1ed'
  on-surface-variant: '#ccc3d7'
  inverse-surface: '#e4e1ed'
  inverse-on-surface: '#302f39'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d3bbff'
  primary: '#d3bbff'
  on-primary: '#3f008d'
  primary-container: '#6d28d9'
  on-primary-container: '#dac5ff'
  inverse-primary: '#7331df'
  secondary: '#c7c4d9'
  on-secondary: '#2f2f3f'
  secondary-container: '#4a4a5b'
  on-secondary-container: '#bcbace'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#0054b6'
  on-tertiary-container: '#baceff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ebddff'
  primary-fixed-dim: '#d3bbff'
  on-primary-fixed: '#250059'
  on-primary-fixed-variant: '#5b00c5'
  secondary-fixed: '#e3e0f6'
  secondary-fixed-dim: '#c7c4d9'
  on-secondary-fixed: '#1a1a29'
  on-secondary-fixed-variant: '#464556'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#13131b'
  on-background: '#e4e1ed'
  surface-variant: '#34343d'
  accent-purple: '#8B5CF6'
  text-primary: '#FFFFFF'
  text-muted: '#94A3B8'
  surface-glass: rgba(22, 22, 37, 0.7)
  glow-purple: rgba(109, 40, 217, 0.15)
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  title-md:
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
  label-numeric:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  unit: 8px
---

## Brand & Style

This design system embodies a **Futuristic Corporate** aesthetic, blending the precision of high-end productivity tools like Linear with the premium, tactile depth of Apple’s ecosystem. It is designed for a technology-first audience that values efficiency, luxury, and clarity.

The visual narrative is defined by:
- **Minimalism & Precision:** Vast whitespace and rigorous alignment create a sense of calm and institutional reliability.
- **Glassmorphism:** Subsurface scattering and frosted textures indicate a sophisticated "OS" layer, separating data from the void.
- **Atmospheric Depth:** The use of purple "glows" and subtle mesh gradients creates a three-dimensional workspace that feels alive yet professional.
- **High-End Tactility:** Interactive elements feature micro-interactions and subtle skeuomorphic cues to provide a "physical" feedback loop within a digital environment.

## Colors

The palette is strictly dark-mode, utilizing deep obsidian tones to provide maximum contrast for neon-influenced accents.

- **The Void (#0B0B13):** The foundational background color. It should feel bottomless and expansive.
- **The Core (#6D28D9):** The primary purple used for critical actions and brand identity.
- **Atmospherics:** Blue accents (#3B82F6) are used sparingly for data visualization and secondary indicators to provide a "cool" counterbalance to the warm purple tones.
- **Glass Surfaces:** Secondary surfaces use #161625 with varying levels of opacity (70-90%) and backdrop blurs to establish hierarchy without blocking the "glow" of the background.

## Typography

The typographic hierarchy utilizes three distinct families to separate brand voice from utility:

1.  **Headlines (Montserrat):** Replaces Poppins with a slightly more geometric, premium feel. Used for high-level messaging and section titles. Bold weights are preferred to ensure high readability against dark backgrounds.
2.  **Body (Inter):** The workhorse for all UI text, chosen for its exceptional legibility and neutral character.
3.  **Utility/Numbers (Space Grotesk):** Provides a technical, "OS" feel. This font is used exclusively for data points, dashboard metrics, and navigational labels to emphasize the "technology-first" nature of the product.

**Scale:** Large display sizes should utilize negative letter spacing to feel tighter and more editorial. Small labels should utilize wide letter spacing for clarity.

## Layout & Spacing

This design system employs a **Fixed-Fluid Hybrid Grid**. Content is centered within a maximum width container of 1280px, but background glows and glass panels often bleed to the edge of the viewport.

- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Desktop:** A 12-column grid with 24px gutters. Use generous vertical padding (80px - 120px) between major sections to maintain a "Luxury" feel.
- **Mobile:** A 4-column grid with 16px margins. Elements reflow vertically, with complex cards transforming into simplified stacked lists.
- **Density:** High-density data views (tables) should use a 4px grid unit, while marketing and landing pages should use the standard 8px unit.

## Elevation & Depth

Hierarchy is established through **Luminous Stacking**. Instead of traditional black shadows, this design system uses:

- **Tiers of Surface:** Level 0 is the `#0B0B13` background. Level 1 is the secondary color with a subtle 1px border. Level 2 (Modals/Popovers) uses backdrop-blur (20px) and a semi-transparent fill.
- **Glow Shadows:** Primary buttons and active cards emit a soft, wide-spread purple glow (`rgba(109, 40, 217, 0.3)`) instead of a dark shadow.
- **Inner Borders:** High-elevation elements feature a subtle top-down inner light border (white at 10% opacity) to simulate a light source from above, creating a chamfered glass effect.

## Shapes

The shape language is defined by **Progressive Rounding**:

- **Small Components:** Buttons, inputs, and tags use a `rounded-lg` (1rem) radius.
- **Container Cards:** Main content areas and dashboards use a `rounded-2xl` (1.5rem) radius to feel approachable and modern.
- **Interactive States:** On hover, cards may increase their perceived elevation via a slight scale-up (1.02x) rather than changing the border-radius.
- **Consistency:** Never use sharp corners. Even the smallest elements must have a minimum of 4px rounding to maintain the premium software aesthetic.

## Components

### Buttons
- **Primary:** Gradient fill (Primary Purple to Accent Purple), white text, 1.5rem padding, soft purple glow on hover.
- **Secondary:** Glass background (white at 5% opacity), 1px border (white at 10% opacity), backdrop-blur.
- **Tertiary/Ghost:** Text-only with Space Grotesk labels, underlined or purple-tinted on hover.

### Cards
- **The "OS" Card:** Background #161625, border 1px `rgba(255, 255, 255, 0.05)`, 24px padding. For premium sections, add a 40px backdrop-blur and set opacity to 80%.

### Input Fields
- Dark backgrounds (#0B0B13) with a 1px border that glows Primary Purple when focused. Labels should always be in Space Grotesk (Label-Caps).

### Chips & Tags
- Pill-shaped with a subtle blue or purple tint. Use Space Grotesk for the internal text at a small scale.

### Dashboard Widgets
- Large numeric displays in Space Grotesk. Trend indicators (arrows) should use Accent Blue for neutral/positive and a specific Error Red only when necessary.