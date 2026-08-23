---
name: Nexins Precision System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c8'
  surface-tint: '#5d5f5f'
  primary: '#5d5f5f'
  on-primary: '#ffffff'
  primary-container: '#ffffff'
  on-primary-container: '#747676'
  inverse-primary: '#c6c6c7'
  secondary: '#5d5f5d'
  on-secondary: '#ffffff'
  secondary-container: '#e2e3e1'
  on-secondary-container: '#636563'
  tertiary: '#5e5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffffff'
  on-tertiary-container: '#767676'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e2e3e1'
  secondary-fixed-dim: '#c6c7c5'
  on-secondary-fixed: '#1a1c1b'
  on-secondary-fixed-variant: '#454746'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  meta-mono:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 128px
---

## Brand & Style

The design system is rooted in the intersection of architectural clarity and high-precision engineering. It targets a sophisticated audience of deep-tech investors and engineers who value performance over flash. The aesthetic is "White-First," prioritizing clarity and focus through a minimal, clinical approach.

The visual language is **Architectural Minimalism**. It emphasizes:
- **Structural Integrity:** Every element serves a functional purpose, aligned to a rigorous grid.
- **High-Precision:** Thin, hair-line borders and monospaced technical metadata evoke the feeling of a blueprint or a calibrated instrument.
- **Premium Air:** Generous whitespace (macro-negative space) is used to elevate content, ensuring the UI feels unhurried and authoritative.
- **Technical Honesty:** Subtle textures—such as micro-dot patterns or fine grain—may be used sparingly to prevent the interface from feeling sterile.

## Colors

The palette is monochromatic and high-key, designed to reflect light and clarity. 

- **Primary White (#FFFFFF):** The dominant surface color for all main containers and backgrounds to maintain the "white-first" identity.
- **Secondary Off-white (#F7F7F5):** Used for structural depth, specifically for subtle section differentiation or secondary backgrounds.
- **Technical Gray (#6B6B6B):** Reserved for secondary information, metadata, and inactive states.
- **Deep Charcoal (#111111):** Used for primary text and high-contrast UI elements like primary buttons to provide a strong visual anchor.
- **Electric Green (#10FF00):** A high-vibrancy accent used exclusively for status indicators, precision highlights, and successful completion states.
- **Structural Borders (#E5E5E5):** A consistent, low-contrast gray for all dividers and element outlines.

## Typography

Typography is used as a structural element. The system leverages **Inter** for its clean, Swiss-inspired legibility in high-density interfaces. **Space Mono** is introduced as a secondary technical typeface to denote "system output," measurements, and data metadata.

- **Headlines:** Use tight letter-spacing and substantial weight to create a strong visual hierarchy against the whitespace.
- **Body:** Prioritizes readability with slightly increased line-height.
- **Metadata (Space Mono):** Always set in small sizes, often uppercase, used for serial numbers, timestamps, or technical specs. It should feel like a label from a hardware component.

## Layout & Spacing

This design system utilizes a **Fixed Grid** philosophy for desktop to maintain architectural proportions, and a fluid model for mobile.

- **The 8px Grid:** All internal spacing (padding/margins) must be multiples of 8.
- **Macro Spacing:** Large gaps (64px+) are encouraged between major sections to prevent visual clutter and signal a premium editorial feel.
- **The Column System:** A 12-column grid for desktop with 24px gutters. Elements should align strictly to these vertical lines.
- **Vertical Rhythm:** Content should be separated by intentional "breathing rooms." Avoid cramming data; instead, use nested scroll areas or paginated views to maintain the "white-first" cleanliness.

## Elevation & Depth

To maintain a minimal and technical aesthetic, the design system avoids traditional shadows and neomorphism. Depth is communicated through:

- **Low-Contrast Outlines:** Every container is defined by a 1px border (#E5E5E5). In light mode, this replaces the need for shadows.
- **Tonal Layering:** The secondary Off-white (#F7F7F5) is used to create a background layer, with Primary White (#FFFFFF) cards or sections "floating" on top.
- **Focused Accents:** On hover, borders may transition from #E5E5E5 to Technical Gray (#6B6B6B) or feature a subtle 1px internal stroke of Electric Green.
- **Flat Surface:** Interaction should feel like touching a smooth, precision-milled surface rather than a soft, "squishy" button.

## Shapes

The shape language is disciplined and geometric. 
- **Radius:** A "Soft" setting is used (0.25rem / 4px) for interactive elements like buttons and input fields to prevent them from feeling too sharp/aggressive, while maintaining a predominantly "square" architectural appearance.
- **Containers:** Large page-level containers and section dividers should remain at 0px roundedness to reinforce the grid-based, engineering-drawing aesthetic.
- **Consistency:** Do not mix roundedness levels; use the 4px standard for all UI controls.

## Components

- **Buttons:** 
  - *Primary:* Solid Deep Charcoal (#111111) with White text. No shadow. 
  - *Secondary:* White background with 1px border (#E5E5E5).
  - *Technical:* Ghost buttons using Space Mono for labels.
- **Input Fields:** 1px #E5E5E5 border, square corners (4px radius), using Space Mono for placeholder text to signal a "data entry" intent.
- **Chips / Tags:** Small, rectangular labels with a light #F7F7F5 fill and Space Mono text. Used for status or categories.
- **Cards:** No shadows. Defined by a 1px border. Title in Inter, metadata in Space Mono at the top-right corner.
- **Indicators:** Small, circular dots of Electric Green (#10FF00) to show active status or "Live" data streams.
- **Dividers:** 1px horizontal or vertical lines in #E5E5E5, often extending to the edge of the grid to create a blueprint-like framework.