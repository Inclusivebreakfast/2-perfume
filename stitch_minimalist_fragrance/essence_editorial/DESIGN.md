---
name: Essence Editorial
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#1e1e1e'
  on-primary: '#ffffff'
  primary-container: '#333333'
  on-primary-container: '#9c9b9b'
  inverse-primary: '#c8c6c6'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#1d1f1c'
  on-tertiary: '#ffffff'
  tertiary-container: '#323431'
  on-tertiary-container: '#9b9c98'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2e1'
  primary-fixed-dim: '#c8c6c6'
  on-primary-fixed: '#1b1c1c'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e3e3de'
  tertiary-fixed-dim: '#c6c7c2'
  on-tertiary-fixed: '#1a1c19'
  on-tertiary-fixed-variant: '#454744'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

This design system is anchored in **Editorial Minimalism**. It prioritizes high-fashion photography and excessive whitespace to create an atmosphere of quiet luxury and heritage. The UI is designed to be "invisible," acting as a sophisticated gallery frame for the product.

The emotional response should be one of serenity, exclusivity, and timelessness. By stripping away heavy textures and vibrant colors, the design system focuses on precision, thin lines, and intentional compositions. It draws inspiration from high-end print magazines, where every element has room to breathe.

## Colors

The palette is rooted in the high-contrast neutrals found in the reference brand, refined for a luxury context. 

- **Primary (#333333):** A deep charcoal used for typography and structural lines, offering a softer alternative to pure black.
- **Secondary (#D4AF37):** A muted gold reserved for subtle accents, call-to-actions, or iconography to signify premium quality.
- **Tertiary (#F5F5F0):** A soft beige used for section backgrounds to break the starkness of pure white.
- **Neutral (#FAFAFA / #FFFFFF):** The primary canvas colors, ensuring a clean and airy environment.

Use the gold accent sparingly—it should feel like a signature, not a primary theme.

## Typography

The typography strategy pairs **Noto Serif** for a sense of literary heritage and **Manrope** for modern clarity. 

- **Headlines:** Set in Noto Serif with generous leading. Larger displays should use slightly tighter letter-spacing for a sophisticated "masthead" look.
- **Body:** Manrope is utilized in lighter weights (300-400) to maintain an airy feel. 
- **Labels:** Small caps and increased letter-spacing are used for navigation and product labels to create a distinct hierarchy without adding visual weight.

## Layout & Spacing

This design system employs a **Fixed Grid** with an emphasis on "negative space as a feature." 

- **Grid:** A 12-column grid with wide 64px margins on desktop to center-align the experience and evoke a boutique feel.
- **Spacing Rhythm:** Vertical rhythm is categorized by "stacks." Use `stack-lg` (80px) between major sections to ensure the user never feels overwhelmed. 
- **Photography Layout:** Images should often break the grid or occupy large, asymmetric blocks to mimic a fashion lookbook.

## Elevation & Depth

To maintain a minimalist aesthetic, the design system avoids traditional shadows. Depth is achieved through:

- **Tonal Layering:** Using the tertiary beige (#F5F5F0) against pure white to distinguish between content areas.
- **Low-Contrast Outlines:** Essential UI containers (like cards or inputs) use 1px "ghost borders" in a light gray or beige, appearing as thin etchings rather than structural blocks.
- **Layered Imagery:** Subtle overlaps where typography sits slightly over the edge of a photograph to create a physical, paper-like depth.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Right angles convey precision, architectural stability, and formal luxury. This applies to buttons, input fields, image containers, and cards. The only exception to the "sharp" rule is the use of circular iconography for social links or very specific interaction indicators, but these should be contained within square hit areas.

## Components

- **Buttons:** Rectangular with no border-radius. Primary buttons are solid #333333 with white text. Secondary buttons are "ghost style" with a 1px border. All text within buttons uses the `label-sm` style (uppercase, tracked out).
- **Input Fields:** Bottom-border only or a 1px thin perimeter. Labels sit above the field in a small, light font-weight. Focus states are indicated by the border transitioning from light gray to the primary charcoal or gold.
- **Cards:** Product cards are borderless with the image taking 100% width. Product details are center-aligned underneath with generous padding.
- **Chips/Tags:** Small, sharp-edged boxes with a light beige background and charcoal text, used for fragrance notes (e.g., "Bergamot", "Oud").
- **Product Gallery:** A vertical-scroll or large-scale carousel that prioritizes one image at a time, emphasizing the product-first approach of the design system.
- **Navigation:** A minimalist top bar with hidden or "hamburger" menus to keep the focus on the visual storytelling of the perfume.