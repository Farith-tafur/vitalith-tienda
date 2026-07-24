---
name: Luminous Earth
colors:
  surface: '#fff8f7'
  surface-dim: '#ffcece'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#ffe9e8'
  surface-container-high: '#ffe1e1'
  surface-container-highest: '#ffdad9'
  on-surface: '#331012'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#4c2526'
  inverse-on-surface: '#ffedec'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#855300'
  on-tertiary: '#ffffff'
  tertiary-container: '#e29100'
  on-tertiary-container: '#523200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#fff8f7'
  on-background: '#331012'
  surface-variant: '#ffdad9'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 20px
  unit: 8px
---

## Brand & Style

The brand personality is rooted in a fusion of natural mysticism and modern luxury. It targets a sophisticated audience seeking holistic wellness through high-quality, artisanal jewelry. The UI should evoke a sense of clarity, serenity, and high-end craftsmanship.

The chosen design style is **Minimalist with Tactile accents**. By utilizing heavy white space and a radiant background, the interface allows the natural textures and colors of the gemstones to serve as the primary visual interest. Subtle gold filigree details and high-quality product photography create an organic yet polished atmosphere.

## Colors

The palette is anchored by a warm, tinted neutral base to provide a sophisticated, organic backdrop for jewelry showcases.
- **Emerald Green (#10b981):** Used for primary actions, success states, and brand-defining headers. It represents vitality and growth.
- **Vibrant Turquoise (#06b6d4):** Used for secondary interactions, categories, and highlights. It evokes calm and water-like clarity.
- **Golden Aura (#f59e0b):** Reserved for delicate accents, star ratings, and premium iconography to signify the artisanal gold details in the jewelry.
- **Neutral Palette:** High-contrast text for readability, with warm, rose-tinted neutral surfaces (`#dba0a0`) used for section backgrounds and containers to provide earthy depth and a sense of "clay" or "stone" craftsmanship.

## Typography

The typography system balances the geometric precision of **Manrope** for structural elements and headlines with the organic, approachable curves of **Plus Jakarta Sans** for body copy.

- **Headlines:** Use Manrope with slightly tighter letter-spacing to create a "premium boutique" feel.
- **Body:** Plus Jakarta Sans is used for long-form text and product descriptions to maintain readability and a friendly, welcoming tone.
- **Labels:** Product metadata (e.g., "Handmade", "Natural Stone") uses uppercase Manrope to create clear information hierarchy.

## Layout & Spacing

This design system utilizes a **Fluid Grid** with a generous 12-column structure for desktop and a 4-column structure for mobile.

- **Desktop:** 12 columns, 24px gutters, and 64px side margins. Large "hero" sections should span the full width to emphasize the radiant background.
- **Mobile:** 4 columns, 16px gutters, and 20px margins. 
- **Rhythm:** An 8px linear scale is used for all internal component spacing (padding, gaps). Large sections of content should be separated by at least 80px (10 units) of vertical whitespace to maintain the "airy" and "modern" feel.

## Elevation & Depth

To maintain a "Modern and Luminous" feel, this design system avoids heavy shadows. Instead, it uses:
- **Tonal Tiers:** Objects are separated by subtle shifts between light surfaces and the warm, neutral stone tones (`#dba0a0`).
- **Ambient Glows:** Elements like primary buttons or active product cards use a very soft, diffused shadow tinted with the primary emerald color (e.g., `rgba(16, 185, 129, 0.08)`) to suggest a subtle inner radiance.
- **Frosted Glass:** Overlay menus and navigation bars use a backdrop blur (12px) with a semi-transparent white fill (85% opacity) to create a "glassmorphic" luxury effect.

## Shapes

The shape language is "Rounded" to echo the organic nature of polished gemstones.
- **Base Components:** 8px (0.5rem) radius for buttons and input fields.
- **Large Components:** 16px (1rem) radius for product cards and containers.
- **Interactive Elements:** Checkboxes and toggle tracks use a slightly more pronounced rounding (3) to feel softer to the touch.

## Components

### Product Cards
Cards should be borderless with a clean white background. Use a subtle 1px inner stroke in the neutral stone tint for definition. Images should have a soft "floating" appearance. The product title uses `title-md` and the price uses the Primary Emerald color in a bold weight.

### Action Buttons
- **Primary:** Solid Emerald Green (`#10b981`) with white text. High-contrast and clear.
- **Secondary:** Transparent background with a 2px Golden (`#f59e0b`) border for "Add to Wishlist" or "View Details".
- **Interaction:** On hover, primary buttons should have a slight upward translation (-2px) and an increased ambient glow.

### Reviews & Social Proof
Testimonial blocks should feature a small "Golden Aura" star icon system. Use `body-md` for the quote and `label-sm` for the reviewer’s name. A subtle Turquoise border-left (4px) can be used to distinguish featured reviews.

### Input Fields & Controls
Fields use the warm neutral stone background (`#dba0a0` at low opacity) with a 1px Emerald bottom-border on focus. This mimics the feeling of high-end stationary or a boutique catalog.

### Tags & Chips
Used for stone types (e.g., "Malachite", "Turquoise"). These should be pill-shaped with a light tint of the stone’s color (e.g., 10% opacity Emerald) and dark text.