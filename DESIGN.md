---
name: Bharat Enterprise Core
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#44474d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#75777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#4d5f7d'
  primary: '#000615'
  on-primary: '#ffffff'
  primary-container: '#0b1f3a'
  on-primary-container: '#7587a7'
  inverse-primary: '#b5c7ea'
  secondary: '#006b5c'
  on-secondary: '#ffffff'
  secondary-container: '#65fade'
  on-secondary-container: '#007262'
  tertiary: '#000613'
  on-tertiary: '#ffffff'
  tertiary-container: '#141f30'
  on-tertiary-container: '#7c879c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b5c7ea'
  on-primary-fixed: '#071c36'
  on-primary-fixed-variant: '#364764'
  secondary-fixed: '#65fade'
  secondary-fixed-dim: '#41ddc2'
  on-secondary-fixed: '#00201b'
  on-secondary-fixed-variant: '#005045'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  margin: 40px
  max-width: 1280px
---

## Brand & Style
The design system is engineered to evoke institutional trust and modern efficiency, specifically tailored for the Indian B2B SaaS ecosystem. The brand personality is "The Reliable Partner"—authoritative enough to handle complex business operations, yet accessible enough for a diverse range of business owners transitioning to digital workflows.

The visual style follows a **Corporate / Modern** aesthetic with a focus on "Precision Minimalism." This avoids generic stock aesthetics by utilizing intentional whitespace, high-density information layouts that remain legible, and a purposeful use of the Teal accent to guide the user’s eye toward growth-oriented actions. The interface should feel "built to last," favoring structural integrity and clarity over fleeting trends.

## Colors
The palette is anchored by **Deep Blue (#0B1F3A)**, a color that represents stability and corporate maturity in the Indian market. **Teal (#00C2A8)** serves as the high-energy catalyst for conversion, used exclusively for primary actions and progress indicators. 

Sectional hierarchy is achieved through a subtle contrast between pure White (#FFFFFF) surfaces and **Light Grey (#F8F9FA)** backgrounds, creating a distinct "card-on-canvas" feel that helps organize dense data without the need for heavy borders. Semantic colors for success, error, and warning are slightly desaturated to maintain the professional tone.

## Typography
This design system employs a dual-font strategy. **Manrope** is used for headlines to provide a refined, modern, and slightly geometric character that feels confident and premium. **Inter** is utilized for body copy and UI labels due to its exceptional legibility at small sizes and neutral, functional tone.

Headings should use the Deep Blue primary color to maintain authority. Body text should typically use a dark slate (#334155) rather than pure black to reduce eye strain during long-form data entry or reporting tasks.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid Grid**. For dashboard views, a 12-column fluid grid is used to maximize screen real estate, while marketing or settings pages conform to a 1280px centered container. 

The spacing rhythm is based on an **8px linear scale**. Use 24px (lg) for standard gutters between major components and 16px (md) for internal component padding. This consistent mathematical rhythm creates a sense of order and reliability, which is essential for business software.

## Elevation & Depth
Elevation in this design system is primarily conveyed through **Tonal Layers** and **Ambient Shadows**. Instead of traditional heavy shadows, we use "Soft Depth"—low-opacity, highly diffused shadows (e.g., Blur 20px, Spread 0, Opacity 4% of Primary Color) to lift cards off the light grey background.

Surface tiers are defined as:
1.  **Level 0 (Background):** Light Grey (#F8F9FA)
2.  **Level 1 (Default Surface):** White (#FFFFFF) with no shadow.
3.  **Level 2 (Active/Hover Surface):** White (#FFFFFF) with a soft ambient shadow.
4.  **Level 3 (Overlay/Modals):** White (#FFFFFF) with a more pronounced shadow and a 20% backdrop tint.

## Shapes
The shape language is "Soft Professional." A **roundedness level of 1 (0.25rem / 4px)** is the default for most UI elements like input fields and small buttons. This provides a clean, modern look that doesn't feel overly "consumerized" or playful. 

For larger elements like Cards or Modals, use `rounded-lg` (8px) to soften the overall interface. Interactive elements should never be fully pill-shaped (except for status badges/chips), as rectangular forms with soft corners project more "industrial strength" for B2B applications.

## Components
- **Buttons:** Primary buttons use the Teal accent with white text. Secondary buttons use a Deep Blue outline. Use bold Manrope for button labels to maintain confidence.
- **Input Fields:** Use 1px borders in a medium-grey (#CBD5E1). On focus, the border should transition to Teal with a subtle 2px outer glow.
- **Cards:** Cards should have no border, using the Level 2 ambient shadow for definition against the light grey background.
- **Chips/Badges:** Use "Tonal Backgrounds" (e.g., a 10% opacity version of the status color) with high-contrast text for status indicators (e.g., "Paid", "Pending").
- **Data Tables:** These are the heart of the system. Use Inter Sm (14px) for cell data with minimal horizontal lines and no vertical lines. The header row should be Deep Blue with White text for maximum structural clarity.
- **Navigation:** A vertical sidebar in Deep Blue with Teal active-state indicators is recommended for Indian B2B contexts, providing a clear hierarchy for multi-module software.