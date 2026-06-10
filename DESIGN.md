---
name: Ethereal Wellness
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#564246'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#897176'
  outline-variant: '#dcc0c5'
  surface-tint: '#a4355b'
  primary: '#8d2249'
  on-primary: '#ffffff'
  primary-container: '#ac3b61'
  on-primary-container: '#ffd8e0'
  inverse-primary: '#ffb1c4'
  secondary: '#76546a'
  on-secondary: '#ffffff'
  secondary-container: '#ffd3ed'
  on-secondary-container: '#7b586e'
  tertiary: '#763d27'
  on-tertiary: '#ffffff'
  tertiary-container: '#93543d'
  on-tertiary-container: '#ffdbcf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e0'
  primary-fixed-dim: '#ffb1c4'
  on-primary-fixed: '#3f001a'
  on-primary-fixed-variant: '#851c44'
  secondary-fixed: '#ffd8ee'
  secondary-fixed-dim: '#e5bad4'
  on-secondary-fixed: '#2d1225'
  on-secondary-fixed-variant: '#5d3d52'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59b'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#6f3722'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
  ivory-base: '#FCFAF7'
  warm-beige: '#F2E8DF'
  soft-gold: '#D4AF37'
  deep-plum: '#4A2C40'
  terracotta: '#AC3B61'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 32px
    letterSpacing: 0.03em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.02em
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
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
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap-lg: 160px
  section-gap-md: 80px
---

## Brand & Style

The design system is anchored in a "Soulful Premium" aesthetic, specifically tailored for a global life and wellness coach. It balances spiritual warmth with sophisticated, international refinement. The target audience seeks transformation, peace, and high-end professional guidance.

The visual style is a blend of **Minimalism** and **Glassmorphism**, emphasizing "lavish" whitespace and breathability. It avoids the coldness of corporate minimalism by introducing tactile, warm color transitions and soft, layered depth. The interface should feel like an invitation to a calm, sacred space—uncluttered, intentional, and human-centric.

Key visual principles:
- **Atmospheric Depth:** Use of soft gradients and background blurs to suggest a spiritual, airy environment.
- **Intentional Breathing Room:** Higher-than-average margins and paddings to reduce cognitive load.
- **Refined Transitions:** Interaction states that fade or glide rather than snap.

## Colors

The palette is a "Warm Earthy" spectrum that evokes groundedness and vitality. 

- **Background Strategy:** Use `ivory-base` for primary backgrounds to provide a softer, more premium feel than pure white. `warm-beige` serves as a secondary surface color for sectioning.
- **Primary & Secondary:** `terracotta` (derived from the brand's signature #AC3B61) acts as the primary driver for action and energy. `deep-plum` provides the "soulful" weight needed for high-contrast text and grounding elements.
- **Accents:** `soft-gold` is reserved for delicate highlights, iconography, or subtle borders to signify premium quality. 
- **Sentiment:** The combination of rose tones and earthy terracotta creates a "human" warmth that feels both professional and approachable.

## Typography

The typography pairs a literary, sophisticated serif with a modern, breathable sans-serif.

- **Headlines:** Use **Libre Caslon Text** for all editorial headlines. It carries an authoritative yet graceful weight. For the largest display styles, a slight negative letter-spacing adds a modern editorial touch.
- **Body Text:** **Montserrat** is utilized at lighter weights (300/400) with increased letter-spacing to ensure the text feels airy and legible, even on mobile devices.
- **Hierarchy:** Maintain high contrast between serif headers and sans-serif body text. Labels should almost always use uppercase with generous tracking to reinforce the premium, "spa-like" aesthetic.

## Layout & Spacing

This design system uses a **Fluid Grid** model with "Lavish Padding." 

- **The Breathability Rule:** Sections should be separated by significant vertical space (`section-gap-lg`) to allow the user to digest content slowly. 
- **Grid:** Use a 12-column grid for desktop and a 4-column grid for mobile. 
- **Safe Zones:** Content containers should never feel "tight." Avoid edge-to-edge text; keep line lengths between 60-80 characters for readability.
- **Mobile-First:** Ensure that spacing does not collapse too aggressively on mobile; maintain a minimum of 24px side margins to preserve the premium feel.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Soft Gradients** rather than harsh shadows.

- **Surfaces:** Use subtle shifts between `ivory-base` and `warm-beige` to define different content areas. 
- **Shadows:** If used, shadows must be "Ambient"—very long, highly diffused, and tinted with the `deep-plum` or `terracotta` hues at 5-10% opacity. They should look like a soft glow rather than a dark drop-shadow.
- **Glassmorphism:** For overlays, navigation bars, or floating action cards, use a backdrop blur (20px+) with a semi-transparent `ivory-base` (80% opacity) to maintain the "spiritual/airy" feel.

## Shapes

The shape language is defined by **Softness**. 

- **Corner Radii:** Standard components use a `rounded-lg` (1rem) or `rounded-xl` (1.5rem) setting. This removes any "aggressive" sharp edges, aligning with the brand's peaceful nature.
- **Buttons & Chips:** Use fully rounded (pill-shaped) ends for interactive elements like primary CTAs and category filters.
- **Containers:** Large content cards or image containers should use the `rounded-xl` setting to feel like "smooth stones" or organic forms.

## Components

- **Buttons:** Primary buttons should be pill-shaped with a `terracotta` background and white text. Secondary buttons should use a `deep-plum` outline with `soft-gold` text for an elegant contrast.
- **Input Fields:** Fields should have a subtle `warm-beige` background, a 1px `soft-gold` border on focus, and no harsh shadows.
- **Cards:** Use high-level elevation with `rounded-xl` corners. Cards should often feature "Emotional Photography" as backgrounds with a 40% `deep-plum` or `warm-beige` gradient overlay to ensure text legibility.
- **Chips/Tags:** Small, uppercase labels with a slight `warm-beige` fill and `soft-gold` text.
- **Transitions:** All hover states for components should utilize a minimum 300ms ease-in-out transition.
- **Imagery:** Photography should be full-bleed where possible, using soft-focus backgrounds and warm color grading to evoke a sense of "Peaceful Presence."