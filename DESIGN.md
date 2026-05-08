---
name: Nurturing Minimalism
colors:
  surface: '#fff8f4'
  surface-dim: '#e1d8d3'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ec'
  surface-container: '#f5ece6'
  surface-container-high: '#efe6e1'
  surface-container-highest: '#eae1db'
  on-surface: '#1f1b18'
  on-surface-variant: '#4d463e'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efe9'
  outline: '#7e766d'
  outline-variant: '#d0c5ba'
  surface-tint: '#6a5c4b'
  primary: '#6a5c4b'
  on-primary: '#ffffff'
  primary-container: '#fbe7d1'
  on-primary-container: '#756755'
  inverse-primary: '#d6c4af'
  secondary: '#516255'
  on-secondary: '#ffffff'
  secondary-container: '#d4e7d6'
  on-secondary-container: '#57695b'
  tertiary: '#615e59'
  on-tertiary: '#ffffff'
  tertiary-container: '#efe9e3'
  on-tertiary-container: '#6c6864'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f3dfca'
  primary-fixed-dim: '#d6c4af'
  on-primary-fixed: '#241a0d'
  on-primary-fixed-variant: '#514535'
  secondary-fixed: '#d4e7d6'
  secondary-fixed-dim: '#b9cbbb'
  on-secondary-fixed: '#0f1f14'
  on-secondary-fixed-variant: '#3a4b3e'
  tertiary-fixed: '#e7e2dc'
  tertiary-fixed-dim: '#cbc6c0'
  on-tertiary-fixed: '#1d1b18'
  on-tertiary-fixed-variant: '#494642'
  background: '#fff8f4'
  on-background: '#1f1b18'
  surface-variant: '#eae1db'
typography:
  h1:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max-width: 1140px
  section-padding: 80px
  card-gap: 32px
  gutter: 24px
---

## Brand & Style

This design system is built on the philosophy of "Gentle Progress." It avoids the high-pressure, gamified intensity of traditional habit trackers in favor of a calm, editorial aesthetic. The UI should evoke a sense of breathing room, utilizing a spacious "website" layout that prioritizes mental clarity over information density. 

The visual style is a blend of **Minimalism** and **Soft Tactility**. It relies on intentional whitespace to guide the user's eye and reduces cognitive load by hiding secondary actions until they are needed. The overall emotional response should be one of quiet encouragement, warmth, and steady growth.

## Colors

The palette is designed to be nurturing and organic. The primary background is a clean, warm off-white, providing a softer canvas than pure white. 

- **Primary (Soft Peach):** Used for primary calls to action and highlighting active states. It represents warmth and personal energy.
- **Secondary (Gentle Green):** Reserved for "success" states, habit completions, and growth indicators. It should feel like fresh foliage rather than a digital "system green."
- **Tertiary (Cream):** Used for subtle container backgrounds and card layering to create soft depth without harsh lines.
- **Neutral (Deep Earth):** A warm, desaturated brown used for typography to ensure readability while maintaining a softer contrast than pure black.

## Typography

This design system utilizes **Plus Jakarta Sans** exclusively to maintain a modern yet approachable character. The typographic hierarchy is generous, with large, expressive headings that allow the brand voice to shine.

Body text is set with increased line height to improve legibility and contribute to the overall feeling of "airiness." Small labels should be used sparingly, often in uppercase with slight tracking to provide a clear structural anchor for more complex data points without cluttering the interface.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** approach common in premium editorial websites. Content is centered within a generous max-width container, surrounded by wide margins that prevent the UI from feeling cramped.

A 12-column grid is used for structure, but elements are encouraged to span multiple columns to create large, readable blocks of information. Vertical rhythm is established through 8px increments, with a focus on "oversized" padding (e.g., 80px to 120px) between major sections to emphasize the minimalist aesthetic.

## Elevation & Depth

Hierarchy is achieved through **Ambient Shadows** and **Tonal Layering** rather than traditional borders or heavy dark shadows.

- **Surface Levels:** The base background is the lowest level. Cards and containers sit one level above, distinguished by a subtle color shift to the Tertiary Cream or a very soft, diffused shadow (Blur: 40px, Opacity: 4%, Color: Neutral).
- **Interactive Depth:** When an element is hovered, the shadow should slightly expand and become more diffused, simulating the effect of the element lifting closer to the user.
- **Glassmorphism:** Use very light backdrop blurs (4px to 8px) for sticky navigation bars to maintain a sense of context and continuity without breaking the clean aesthetic.

## Shapes

The shape language is consistently **Rounded**. All primary containers and buttons use a 1rem (16px) radius to feel friendly and safe. 

Progress bars and input fields should utilize a fully rounded "Pill" shape to represent fluidity and movement. Avoid sharp corners entirely, as they introduce a visual "harshness" that contradicts the nurturing brand goals of this design system.

## Components

### Buttons
Primary buttons are pill-shaped with the Soft Peach background and Deep Earth text. They should feel substantial but light. Secondary buttons use a simple low-contrast outline or a transparent background with an underline on hover.

### Cards
Cards are the primary container for habit tracking. They should be large, featuring generous internal padding (min 32px) and a subtle ambient shadow. Use the Secondary Green sparingly within cards—only for checkboxes or completion rings.

### Habit Trackers
Progress should be visualized through thin, elegant lines or soft-colored rings. Avoid heavy "filled" bars. Use a "dot-grid" style for weekly views to keep the interface looking like a clean physical journal.

### Input Fields
Inputs are minimal, featuring only a bottom border or a very light cream background. Focus states are indicated by a gentle shift to the Primary Peach color, avoiding heavy focus rings.

### Chips & Tags
Use chips for habit categories (e.g., "Health," "Mindfulness"). These should be small, pill-shaped, and use very desaturated versions of the brand colors to avoid competing with primary actions.