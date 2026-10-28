---
name: Kinetic Enterprise Digital
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#5a4138'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#8e7166'
  outline-variant: '#e2bfb2'
  surface-tint: '#a73a00'
  primary: '#a33900'
  on-primary: '#ffffff'
  primary-container: '#cc4900'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb599'
  secondary: '#006781'
  on-secondary: '#ffffff'
  secondary-container: '#8fdfff'
  on-secondary-container: '#00647d'
  tertiary: '#0e6479'
  on-tertiary: '#ffffff'
  tertiary-container: '#347d92'
  on-tertiary-container: '#fafdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbce'
  primary-fixed-dim: '#ffb599'
  on-primary-fixed: '#370e00'
  on-primary-fixed-variant: '#7f2b00'
  secondary-fixed: '#b9eaff'
  secondary-fixed-dim: '#81d1f0'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#004d62'
  tertiary-fixed: '#b2ebff'
  tertiary-fixed-dim: '#8bd1e8'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5f'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses high-velocity digital transformation, combining strategic marketing acumen with robust enterprise engineering. Tailored for enterprise executives, growth-stage founders, and operational leaders, the aesthetic strikes a deliberate balance between corporate authority and creative technical ingenuity.

The design movement is **Modern Corporate Tech**: architectural, luminous, and refined. It avoids decorative clutter in favor of crisp structural layouts, precision grid systems, and functional neon-burn accents. The interface relies on slate-tinted canvas structures, high-contrast typography, and restrained ambient lighting to communicate reliability, forward momentum, and bespoke digital craft across enterprise SaaS dashboards and client-facing digital flagships.

## Colors

The palette leverages a high-impact tension between warm conversion drivers and cool structural backbones:

- **Primary (`#EA580C`)**: An energetic kinetic orange. Used selectively for high-priority calls-to-action, key performance highlights, active tabs, and critical interactive feedback.
- **Secondary (`#0E7490`)**: A vivid deep petroleum cyan. Deployed for secondary workflows, technical category tags, progress metrics, and data visualizations.
- **Tertiary (`#005F73`)**: A dense teal anchor, providing balanced support for interactive iconography, enterprise badges, and alternate analytical charts.
- **Neutral Dark (`#0F172A`)**: Deep slate charcoal, establishing strict contrast for typography, high-priority frames, and navigation anchors.
- **Neutral Canvas (`#F8FAFC` to `#FFFFFF`)**: Crisp, sterile foundations that allow complex dashboards and media components to breathe without visual fatigue.

### Roles & Color Rules
- Primary orange must never compete with tertiary teal; orange dictates primary intent, teal/cyan informs structure and categorization.
- Surface levels build from pure white (`#FFFFFF`) on elevated cards, resting on a `#F8FAFC` page background with micro-borders in `#E2E8F0`.
- Text utilizes three strict tiers: Primary (`#0F172A`), Secondary (`#475569`), and Subtle (`#94A3B8`).

## Typography

The type system blends the energetic geometry of **Plus Jakarta Sans** for titles, metrics, and callouts with the systematic utility of **Inter** for data-dense contexts, long-form technical proposals, and dashboard grids.

### Usage Hierarchy
- **Plus Jakarta Sans**: Reserved for headings, numeric data callouts, navigation items, buttons, and badges. Tight tracking on display and headline weights reinforces a sculpted, premium agency posture.
- **Inter**: Dedicated exclusively to body copy, table data cells, form input text, and technical helper copy to maintain optimum legibility across variable viewport resolutions.
- **Micro-Labels**: Form uppercase badges and status tags using `label-sm` with widened letter-spacing (`0.05em`) to balance geometric weight.

## Layout & Spacing

The layout is rooted in a dynamic 12-column responsive fluid grid designed to bridge agency marketing showcases with modular ERP dashboards.

### Grid Breakpoints
- **Desktop (1280px+)**: 12 columns, `margin-lg` (4rem) outer margin, `gutter-lg` (2rem) gutter. Maximum layout containment is 1440px.
- **Tablet (768px - 1279px)**: 8 columns, `margin-md` (2.5rem) outer margin, `gutter` (1.5rem) gutter. Sidebars collapse to icon rails or off-canvas drawers.
- **Mobile (320px - 767px)**: 4 columns, `margin` (1.5rem) outer margin, `gutter-sm` (1rem) gutter. Multi-column dashboard widgets reflow into single-column vertical stacks.

### Spacing Discipline
All component-internal spacing relies strictly on a standardized 4px/8px rhythm. Padding within interactive surfaces (cards, panels) defaults to `space-lg` on desktop and scales down to `space-md` on mobile viewports.

## Elevation & Depth

Visual hierarchy combines low-contrast structural outlines with ambient tinted shadows and localized luminous glow effects. Surfaces never float disconnectedly; they reside within structured atmospheric planes.

- **Level 0 (Base Canvas)**: Flat `#F8FAFC` background.
- **Level 1 (Cards, Containers)**: Solid `#FFFFFF` fill with a crisp 1px perimeter border in `rgba(15, 23, 42, 0.06)` and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Hover States, Interactive Cards)**: `0 10px 25px -5px rgba(15, 23, 42, 0.06), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`, subtly lifting the element with a 1px border transition to `rgba(14, 116, 144, 0.20)`.
- **Level 3 (Modals, Overlays, Dropdowns)**: Floating layer with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.05)`.
- **Kinetic Glow (Accent Accents)**: Critical active modules (e.g., active metrics, primary conversion nodes) utilize a soft orange accent bloom: `box-shadow: 0 0 20px rgba(234, 88, 12, 0.18)`.

## Shapes

The interface embraces a balanced modern corner language using **Level 2 (Rounded)**:
- Standard UI elements (buttons, text inputs, chips): `0.5rem` (8px).
- Structural containers (cards, dashboard panels, hero splitters): `rounded-lg` at `1rem` (16px).
- Modals, prominent marketing frames, and preview mockups: `rounded-xl` at `1.5rem` (24px).
- Badges and status pills: fully pill-shaped (`9999px`) to visually separate metadata tokens from structural cards.

## Components

### Buttons
- **Primary**: Solid `#EA580C` fill, pure white text, semi-bold `label-lg`, `0.5rem` border-radius. On hover, background shifts to `#C2410C` with a matching `0 0 16px rgba(234, 88, 12, 0.3)` glow.
- **Secondary**: Solid `#0E7490` background with white text for secondary actions, or `#0F172A` for technical platform actions.
- **Outline / Subtle**: Transparent background, 1px border in `rgba(15, 23, 42, 0.12)`, text `#0F172A`. On hover, fills with `rgba(14, 116, 144, 0.04)` and border transitions to `#0E7490`.

### Status Badges & Chips
- Fully rounded pills (`9999px`) using `label-sm` in all-caps.
- **Tech / Mobile / Web Category Badges**: Translucent petroleum cyan tint (`background: rgba(14, 116, 144, 0.1)`, `text: #0E7490`).
- **Growth / Marketing / Alert Badges**: Translucent orange tint (`background: rgba(234, 88, 12, 0.1)`, `text: #EA580C`).
- Interactive filter chips include a 1px border and hover fill states.

### Cards & Service Tiles
- Background: pure white (`#FFFFFF`) encased in a 1px `rgba(15, 23, 42, 0.06)` border with `1rem` border radius.
- Agency portfolio and service cards feature an accent top border or dynamic inner corner notch highlighted by an active cyan-to-orange mini gradient during hover.
- Cards maintain distinct internal visual separation between header metrics, graphical media, and metadata tags using `space-md` gaps.

### Form Inputs & Controls
- **Inputs**: Background `#FFFFFF`, 1px border `rgba(15, 23, 42, 0.15)`, text `body-md` in `#0F172A`, placeholder `#94A3B8`. Padding `0.75rem 1rem`. Focus state features a sharp 1.5px border in `#0E7490` alongside a diffuse focus ring (`0 0 0 3px rgba(14, 116, 144, 0.12)`).
- **Checkboxes & Radios**: 1.25rem square or circular controls; when checked, filled with `#EA580C` containing crisp white icon glyphs.

### Lists & Data Tables
- Row cells enforce strict vertical alignment with 1px divider lines in `#F1F5F9`.
- Interactive rows transition to an ambient background of `rgba(14, 116, 144, 0.02)` on cursor focus.

### Dashboards & Custom ERP Modules
- **Metric Widgets**: Prominent display numbers (`headline-lg`) paired with micro status indicators (green upward telemetry arrows or orange attention flags).
- **Tab Rails**: Segmented pills resting in a recessed container (`#F1F5F9`) with active tabs elevated using pure white fill and micro-elevation.