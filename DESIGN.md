---
name: Conecta Professional HVAC System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#5c5f61'
  on-secondary: '#ffffff'
  secondary-container: '#e0e3e5'
  on-secondary-container: '#626567'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#e0e3e5'
  secondary-fixed-dim: '#c4c7c9'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Hanken Grotesk
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
    letterSpacing: 0.05em
  label-sm:
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
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

The design system is engineered for **Conecta Instalaciones**, a premier HVAC service provider in Barcelona. The brand personality is rooted in technical expertise, rapid response, and Mediterranean professionalism. It aims to evoke an immediate sense of relief (cooling) and reliability.

The aesthetic follows a **Corporate / Modern** direction with a focus on **Precision Minimalism**. By utilizing high-contrast accents against a structured, clean backdrop, the UI communicates both the "cool" of air conditioning and the "energy" of high-quality service. The interface prioritizes clarity and speed of action, ensuring that users in urgent need of climate control solutions feel supported by an organized, high-performance digital environment.

## Colors

The palette is strategically split between "The Foundation" and "The Action."

- **Primary (Deep Slate Blue):** Used for headers, heavy typography, and grounding elements. It represents the "Conecta" brand's stability and authoritative presence in the industry.
- **Secondary (Cool White/Gray):** These shades provide a "breathable" atmosphere, mimicking the sensation of a well-ventilated, clean space.
- **Tertiary (Frost Blue):** Used for iconography, interactive secondary elements, and subtle backgrounds to reinforce the cooling theme.
- **Accent (Solar Orange):** Reserved strictly for high-conversion CTAs like "Get a Quote" or "Emergency 24h." Its warmth contrasts against the cool primary tones to draw immediate ocular attention.

## Typography

The design system employs **Hanken Grotesk** for headlines to provide a sharp, contemporary edge that feels engineered and precise. **Inter** is utilized for body copy and UI labels due to its exceptional legibility and neutral tone, which ensures that technical specifications and service details remain easy to digest.

A strict hierarchy is maintained:
- **Headlines:** Use high weight (600-700) and slightly tighter letter-spacing for a "solid" architectural feel.
- **Labels:** Uppercase labels are used for small metadata and "Urgency Badges" to distinguish them from standard prose.
- **Mobile scaling:** Headline sizes are reduced by approximately 15-20% on mobile to maintain readability without overwhelming the viewport.

## Layout & Spacing

This design system uses a **Fluid-Fixed Hybrid Grid**. Content is housed in a 12-column grid that centers on large screens with a max-width of 1280px, but remains fluid on mobile and tablet.

- **Spacing Rhythm:** Based on an 8px baseline. All paddings and margins should be multiples of 8 (e.g., 16, 24, 32, 64).
- **Mobile Layout:** Margins shrink to 16px. Elements like service cards reflow from a 3-column desktop layout to a single-column vertical stack.
- **Sticky Contact Bar:** A persistent header or sub-header (mobile) ensures that the "Call Now" and "WhatsApp" triggers are always within thumb-reach (bottom-anchored on mobile for better ergonomics).

## Elevation & Depth

To maintain a "clean and professional" look, depth is used sparingly but purposefully:

- **Tonal Layers:** The primary background is white, but different service tiers or "How it Works" sections use a very light gray (#F1F5F9) to create logical separation without adding visual weight.
- **Ambient Shadows:** Cards use a "Low-and-Slow" shadow (0px 4px 20px rgba(15, 23, 42, 0.08)). This makes the cards appear slightly lifted off the surface, inviting interaction without looking "gamified."
- **Focus States:** Input fields and interactive cards use a subtle blue glow (Tertiary color) upon hover or focus to provide tactile feedback.

## Shapes

The shape language is **Rounded (Level 2)**. This strikes a balance between the industrial nature of HVAC equipment (hard lines) and the customer-centric service (friendly curves).

- **Standard Elements:** Buttons, inputs, and small cards use a 0.5rem (8px) radius.
- **Container Elements:** Large sections or high-impact service cards use 1rem (16px) for a more modern, approachable feel.
- **Icons:** Should be contained within circular or "Squircle" backgrounds when used as features to soften the technical iconography.

## Components

### Buttons
- **Primary Action (CTA):** Solar Orange background with white text. Bold, 16px padding horizontal, 8px vertical. Used for "Get a Free Quote."
- **Secondary Action:** Ghost style with a Deep Slate Blue border. Used for "View All Services."
- **Emergency Button:** High-contrast red/orange mix with a pulsing icon for "24h Urgent Repair."

### Cards
- **Service Cards:** White background with Level 2 roundedness and a subtle ambient shadow. Icons are placed in the top-left, using the Tertiary blue color.
- **Case Study Cards:** Full-width images with a text overlay at the bottom, using a soft backdrop blur (glassmorphism) for the description.

### Urgency Badges
- Small, pill-shaped labels with a Tertiary Blue or Accent Orange background. Text is `label-sm` (uppercase). Examples: "AVAILABLE NOW", "24H SERVICE", "BCN LOCAL".

### Input Fields
- Structured with a light gray border (#E2E8F0) that transitions to the Tertiary Blue on focus. Labels are always visible above the field in `label-sm`.

### Icons
- **Style:** Thin-to-medium stroke (2px), monolinear.
- **Themes:** Snowflakes (Cooling), Fire (Heating), Wrench (Installation), Clock (24h Service), Pin (Barcelona coverage).