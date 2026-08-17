---
name: Kinetic Infrastructure
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
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-name:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-section:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.05em
  title-job:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
  body-main:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-tech:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-meta:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  display-name-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 36px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  container-padding: 40px
  section-gap: 32px
  element-gap: 12px
  grid-gutter: 24px
---

## Brand & Style

The design system is engineered for the high-stakes IT and engineering sector, where technical precision must meet modern aesthetics. The personality is "Sophisticated Technicality"—it projects the image of an architect who understands both the code and the presentation.

The visual style merges **Minimalism** with **Glassmorphism**. It utilizes a structured, high-density information layout typical of technical documentation but softens it with translucent layers and refined blurs. This approach ensures that the density of a professional CV feels breathable and organized rather than overwhelming. The emotional response is one of reliability, forward-thinking expertise, and extreme attention to detail.

## Colors

The palette is anchored in **Deep Slate (#0F172A)**, used for primary typography and structural headers to provide a sense of authority. **Cyber Blue (#3B82F6)** serves as the high-visibility accent for interactive elements, links, and technical highlights, symbolizing "active" status and connectivity.

**Clean White (#F8FAFC)** is the primary surface color, providing a crisp, high-contrast background that prevents eye fatigue during long reading sessions. Use a specialized "Surface Tint" of Cyber Blue at 5% opacity for glassmorphic backgrounds to maintain a cohesive technical temperature across the UI.

## Typography

This design system utilizes **Inter** for its systematic, utilitarian clarity. It is the workhorse for all prose and structural labeling. For technical metadata, such as coding languages or tool versions, **JetBrains Mono** (or a similar high-quality monospaced font) is introduced to evoke a "code-editor" feel within the document.

Hierarchy is strictly enforced through weight and letter spacing rather than dramatic size shifts. Section headers use uppercase styling with increased tracking to create clear visual "anchors" for the eye when scanning. Body text maintains a generous line height (1.5x-1.6x) to ensure technical descriptions remain legible at smaller point sizes.

## Layout & Spacing

The system employs a **Fixed Grid** model for desktop (A4/Letter proportions) and a **Fluid Grid** for web views. The layout is divided into a 12-column system, typically utilized as an asymmetrical 4-8 split: 4 columns for a sidebar containing contact info and skills, and 8 columns for the main experience timeline.

Vertical rhythm is based on an **8px grid**. All padding and margins must be multiples of 4px. Breakpoints are set at 768px (Tablet) where the sidebar collapses to the top of the document, and 480px (Mobile) where margins are reduced to 16px to maximize content width.

## Elevation & Depth

Depth is achieved through **Glassmorphism** rather than traditional heavy shadows. Surfaces use a "Surface-1" (Background) and "Surface-2" (Card) logic:
- **Surface-2 (Cards):** Background color of `#FFFFFF` at 70% opacity with a `20px` backdrop-filter blur. 
- **Borders:** Cards are defined by a 1px solid border of `#0F172A` at 10% opacity.
- **Shadows:** Use a single, very soft ambient shadow for cards (`0px 4px 20px rgba(15, 23, 42, 0.05)`) to lift elements slightly without creating visual "noise."

This creates a sense of stacked, translucent layers that feel like a high-end dashboard interface.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding suggests modern software interfaces while maintaining the professional rigor required for an IT resume. Excessive rounding (pill shapes) should be reserved exclusively for "Tech Tags" (Skill Chips) to differentiate them from functional containers. Interactive components like buttons use the base `rounded-sm` (4px) or `rounded-md` (8px) values.

## Components

### Cards & Containers
Experience and Project entries are housed in glassmorphic cards. They feature a 1px top border in **Cyber Blue** to act as a primary visual accent and to group related information chronologically.

### Tech Chips (Skills)
Use a background of Cyber Blue at 10% opacity with a text color of Deep Slate. Font should be the Monospaced Label at 12px. These should be "pill-shaped" to stand out as discrete units of data.

### Progress Indicators
For skill proficiency (if used), utilize a 4px tall track. The background track is Deep Slate at 5% opacity; the "fill" is a solid Cyber Blue. Avoid gradients to maintain the minimalist aesthetic.

### Icons
Use **Lucide-style** (2px stroke) icons. Icons should always be monochrome (Deep Slate or Cyber Blue) and sized to 18px x 18px within a 24px bounding box to ensure alignment with typography cap-heights.

### Inputs & Contact Fields
Simple underlines or 1px ghost borders. Labels should use the **Label-Meta** style to remain secondary to the actual contact data.