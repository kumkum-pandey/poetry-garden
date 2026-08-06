---
name: Manuscript Editorial
colors:
  surface: '#fef8f6'
  surface-dim: '#ded9d7'
  surface-bright: '#fef8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f2f0'
  surface-container: '#f2edeb'
  surface-container-high: '#ede7e5'
  surface-container-highest: '#e7e1df'
  on-surface: '#1d1b1a'
  on-surface-variant: '#4d453f'
  inverse-surface: '#32302f'
  inverse-on-surface: '#f5f0ed'
  outline: '#7f756e'
  outline-variant: '#d0c4bc'
  surface-tint: '#695c51'
  primary: '#180f08'
  on-primary: '#ffffff'
  primary-container: '#2e241b'
  on-primary-container: '#9a8a7e'
  inverse-primary: '#d5c3b6'
  secondary: '#7e5714'
  on-secondary: '#ffffff'
  secondary-container: '#fec97c'
  on-secondary-container: '#78520f'
  tertiary: '#0b1217'
  on-tertiary: '#ffffff'
  tertiary-container: '#20272c'
  on-tertiary-container: '#878e94'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f2dfd1'
  primary-fixed-dim: '#d5c3b6'
  on-primary-fixed: '#231a11'
  on-primary-fixed-variant: '#51453a'
  secondary-fixed: '#ffddb1'
  secondary-fixed-dim: '#f2be72'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#624000'
  tertiary-fixed: '#dce3ea'
  tertiary-fixed-dim: '#c0c7ce'
  on-tertiary-fixed: '#151c21'
  on-tertiary-fixed-variant: '#41484d'
  background: '#fef8f6'
  on-background: '#1d1b1a'
  surface-variant: '#e7e1df'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-md:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: ebGaramond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: manrope
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-caps:
    fontFamily: manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  poetry-block:
    fontFamily: ebGaramond
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  margin-desktop: 64px
  section-padding: 120px
---

## Brand & Style

This design system is anchored in the tactile world of literary publishing and heritage storytelling. It evokes the quiet dignity of a Mumbai heritage library and the warmth of a handwritten letter. The brand personality is scholarly yet welcoming, sophisticated yet deeply human.

The visual direction follows a **Premium Editorial** style, blending the structured elegance of high-end magazines with the organic texture of handmade paper. It rejects the sterility of modern SaaS interfaces in favor of intentional whitespace, classical proportions, and a "slow-tech" philosophy. The emotional goal is to provide a serene sanctuary for readers and poets, emphasizing the weight and beauty of the written word over rapid interaction.

## Colors

The palette is derived from natural, organic materials—ink, aged paper, and oxidized botanical pigments.

- **Primary Text (#2E241B):** A deep, warm charcoal that mimics aged lampblack ink. It provides high legibility while remaining softer than pure black.
- **Background Parchment (#F7F1E7):** The core canvas, offering a warm, low-fatigue reading experience.
- **Accent Gold (#B88A44):** Used sparingly for highlighting special attributes, call-to-actions, or ornamental touches, representing the gilding on a leather-bound book.
- **Accent Burgundy (#6A2F2F):** Reserved for moments of emotional emphasis or critical storytelling elements.
- **Borders (#DED2BF):** Low-contrast lines that define structure without interrupting the flow of the layout.

## Typography

The typography system relies on a high-contrast pairing between a classical serif and a modern, technical sans-serif.

**Headline & Display:** Using *ebGaramond* (as the closest available match to Cormorant) to provide historical weight. For large headers, use tight letter-spacing to create an "ink-on-page" feel.
**Body & Interface:** *Manrope* is utilized for its exceptional legibility and neutral character, ensuring that the interface elements do not compete with the poetry content.
**Line Height:** Generous leading is mandatory for body copy (1.6x) to facilitate a calm, rhythmic reading experience.
**Poetry Blocks:** Large quotes or poetic verses should use the `poetry-block` style, which emphasizes the serif’s elegant italic forms.

## Layout & Spacing

This design system uses a **Fixed Grid** model for desktop to maintain editorial control over line lengths, transitioning to a fluid model for mobile.

- **Editorial Rhythm:** Use large vertical gaps (`section-padding`) to separate different story arcs or community sections.
- **The "Golden" Gutter:** A wide 32px gutter ensures that even dense text blocks feel airy and approachable.
- **Responsive Behavior:** On mobile, margins reduce significantly to maximize the reading area, while font sizes for headings are scaled down to prevent awkward word breaks.
- **Alignment:** Central alignment is preferred for hero moments and poetic verses, while functional information (lists, forms) should remain left-aligned.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** rather than traditional shadows.

- **The Base:** The Parchment (#F7F1E7) background acts as the desk surface.
- **The Cards:** Surface cards (#FFF9F2) represent fresh sheets of paper laid atop the desk.
- **Shadows:** Avoid heavy dropshadows. If elevation is required for floating elements (like the navigation), use a barely-perceptible, highly diffused shadow: `0px 4px 20px rgba(46, 36, 27, 0.05)`.
- **The Scroll Transition:** The floating navigation bar should be transparent on the hero section and transition to a solid Parchment background with a thin bottom border (#DED2BF) as the user scrolls, simulating a header that remains "pinned" to the top of the manuscript.

## Shapes

The shape language is "Soft," mimicking the slightly rounded corners of premium cardstock and handmade stationery.

- **Standard Radius:** 0.5rem (8px) for small components like inputs.
- **Large Radius:** 1rem (16px) for editorial cards and main containers, providing a friendly, organic silhouette.
- **Dividers:** Use thin (1px) lines for structure. For decorative transitions, use "ink brush" style horizontal lines that taper at the ends.

## Components

- **Editorial Cards:** Large containers with `rounded-lg` (16px), a thin border (#DED2BF), and generous internal padding (min 32px). Titles should always use the Serif display font.
- **Buttons:**
  - *Primary:* Solid Ink (#2E241B) with White text. Rectangular with a slight 4px radius.
  - *Secondary:* Outline style with a thin #2E241B border and #B88A44 text for a "signature" feel.
- **Floating Navigation:** A minimal bar using `label-caps` typography. It should feel lightweight, using high whitespace between menu items.
- **Input Fields:** Minimalist design with only a bottom border (#DED2BF) that darkens on focus. Labels sit above the field in `label-caps`.
- **Botanical Accents:** Small, single-color vintage botanical illustrations (line art) should be used as background decorations or "end-of-article" markers.
- **Chips/Tags:** Rounded-pill shapes with the Secondary background (#EFE4D1) and Muted Text (#6C5A4B), used for poetry categories (e.g., "Haiku", "Spoken Word").