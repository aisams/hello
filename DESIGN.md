---
name: Synthetic Identity
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#c1c8c4'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#8c928e'
  outline-variant: '#424845'
  surface-tint: '#afcdc0'
  primary: '#afcdc0'
  on-primary: '#1b352d'
  primary-container: '#06221a'
  on-primary-container: '#6f8b80'
  inverse-primary: '#49645a'
  secondary: '#ecffe3'
  on-secondary: '#003907'
  secondary-container: '#13ff43'
  on-secondary-container: '#007117'
  tertiary: '#a0d1bc'
  on-tertiary: '#033829'
  tertiary-container: '#002318'
  on-tertiary-container: '#608f7c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cbe9dc'
  primary-fixed-dim: '#afcdc0'
  on-primary-fixed: '#042018'
  on-primary-fixed-variant: '#314c42'
  secondary-fixed: '#72ff70'
  secondary-fixed-dim: '#00e639'
  on-secondary-fixed: '#002203'
  on-secondary-fixed-variant: '#00530e'
  tertiary-fixed: '#bbedd7'
  tertiary-fixed-dim: '#a0d1bc'
  on-tertiary-fixed: '#002117'
  on-tertiary-fixed-variant: '#204f3f'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-xl:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-xl-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.15em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-sm: 16px
  stack-md: 40px
  stack-lg: 80px
---

## Brand & Style

This design system centers on the philosophy that artificial intelligence transforms the individual into a scalable intellectual property. The brand personality is **Visionary, Technical, and Empowering**, positioning the user as a high-value entity within a digital-first ecosystem.

The aesthetic follows a **High-Tech Minimalism** approach, blending the precision of developer tools with the premium feel of a luxury tech brand. Key stylistic pillars include:
- **Futuristic Glassmorphism:** Using depth and translucency to suggest sophisticated processing layers.
- **Technical Grid Patterns:** Subtle background motifs that evoke high-end hardware and architectural blueprints.
- **Luminescent Accents:** High-contrast highlights that guide the eye to interactive elements, mimicking the glow of a terminal or a neural interface.
- **Aggressive Whitespace:** Large, purposeful gaps to allow the complex "IP" concept to breathe and maintain a professional, calm authority.

## Colors

The palette is engineered for a high-contrast dark mode experience.

- **Primary (Forest Deep):** A dense, near-black green (#06221A) used for foundational surfaces. It provides a more organic, sophisticated depth than pure black.
- **Secondary (Neon Pulse):** A hyper-vibrant lime green (#00FF41) reserved exclusively for calls to action, active states, and critical data points.
- **Tertiary (Emerald Shadow):** A mid-tone green (#0A3D2E) used for secondary containers, borders, and glassmorphic strokes.
- **Neutral (Ghost White):** An off-white (#F8FAFC) used for primary typography to ensure maximum legibility without the harshness of absolute white.

## Typography

The typographic system utilizes a trio of fonts to balance technical precision with modern editorial flair.

- **Geist** handles the primary display and headlines. Its geometric construction feels engineered and contemporary. Tracking should be tightened slightly in larger sizes to create a "locked-in" technical feel.
- **Inter** is the workhorse for body copy. It is chosen for its exceptional readability in dark environments and its neutral, systematic appearance.
- **JetBrains Mono** is used for labels, metadata, and technical callouts. This introduces a "code-adjacent" aesthetic that reinforces the AI/tech theme.

**Formatting Rules:** 
- Use `label-caps` for section headers and eyebrow text. 
- Implement generous paragraph spacing (1.5x font size) to maintain the minimalist feel.

## Layout & Spacing

This design system uses a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 

- **The Technical Grid:** Backgrounds should optionally feature a subtle 32px grid pattern in `tertiary_color` at 5% opacity to reinforce the "Synthetic Identity" metaphor.
- **Rhythm:** All spacing is derived from an 8px base unit. 
- **Verticality:** Use `stack-lg` for separating major narrative sections on the landing page. `stack-md` is the standard for grouping related component blocks like feature cards or pricing tiers.
- **Margins:** Desktop views utilize wide horizontal margins (64px) to drive focus toward the center-aligned "IP" content.

## Elevation & Depth

Depth is not communicated via traditional shadows, but through **Luminous Tiers** and **Glassmorphism**.

1.  **Floor (Base):** The `primary_color` background.
2.  **Plinth (Containers):** Semi-transparent surfaces using `tertiary_color` with a 40% opacity and a 20px backdrop blur.
3.  **Stroke (Edges):** Instead of shadows, use 1px solid borders. For active or high-elevation items, use a subtle inner glow (0px 0px 8px) in the `secondary_color` at 20% opacity.
4.  **The Glow:** High-priority elements (like CTAs) should have a soft, external bloom of the `secondary_color` to simulate light emission on a dark surface.

## Shapes

The shape language is **Soft (0.25rem)**, leaning towards architectural sharpness rather than playful roundness.

- **Standard Elements:** Buttons, input fields, and small chips use the base 4px (0.25rem) radius.
- **Cards & Sections:** Use `rounded-lg` (8px) to provide enough distinction from the background without feeling "bubbly."
- **Interactive States:** On hover, borders may transition from `tertiary_color` to `secondary_color`, maintaining the sharp edge to feel like precision-cut glass.

## Components

### Buttons
- **Primary:** Background in `secondary_color`, text in `primary_color` (Geist Bold). No shadow, but a 4px bloom effect on hover.
- **Ghost:** Transparent background, 1px border in `secondary_color`, text in `secondary_color`.

### Cards (The IP Profile)
- Background: `tertiary_color` at 20% opacity.
- Border: 1px solid `tertiary_color`.
- Effect: 12px backdrop-blur. 
- Content: Headline in Geist, technical metadata in JetBrains Mono.

### Input Fields
- Dark backgrounds with `neutral_color` text.
- Focus state: Border changes to `secondary_color` with a 1px solid line and a subtle "scanline" animation across the bottom of the field.

### Technical Chips
- Small, rectangular labels used for AI capabilities. 
- Style: JetBrains Mono, all-caps, 1px border, no background.

### Navigation
- A floating "Glass" header with a 1px bottom border. 
- Links use `label-md` with a `secondary_color` dot appearing above the active link.