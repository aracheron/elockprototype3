---
name: Cybernetic Security & Hardware
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
  on-surface-variant: '#444651'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#3e2400'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c3800'
  on-tertiary-container: '#ef9900'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
  surface-crisp: '#FFFFFF'
  surface-canvas: '#F8FAFC'
  surface-elevated: '#F1F5F9'
  hardware-slate: '#334155'
  secure-cyan: '#06B6D4'
  alert-coral: '#EF4444'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-telemetry:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies engineering rigor, uncompromised security, and refined industrial hardware design. It addresses facilities managers, modern homeowners, and commercial security architects who demand physical reliability coupled with encrypted software intelligence. 

The aesthetic combines **Corporate / Modern** precision with architectural **Tactile / Hardware** elements. The interface prioritizes high-clarity structural layouts, restrained industrial metallics, and deliberate luminous accents reminiscent of biometric scanners and encrypted communication status indicators. The resulting visual signature communicates impenetrable physical safety, absolute precision, and effortless smart control.

## Colors

The chromatic architecture establishes structural authority through deep oceanic security blues and precision teals, avoiding frivolous decoration.

- **Primary (`#1E3A8A`)**: Deep Vault Blue communicates corporate institutional trust, cryptographic stability, and physical locking power.
- **Secondary (`#0D9488`)**: Cybernetic Teal signals active synchronization, digital key validation, and operational health.
- **Tertiary (`#F59E0B`)**: Signal Amber serves as an alert state for battery thresholds, pending clearances, and critical warnings.
- **Neutral (`#0F172A`)**: Slate Black delivers deep structural contrast, typographic legibility, and premium metal-chassis framing.

Use `secure-cyan` strictly for active telemetry badges, radio indicators, and telemetry glow. Light surfaces default to clinical white and cool architectural grays to evoke modern cleanroom environments and premium anodized aluminum hardware.

## Typography

Typography balances architectural authority and clinical data legibility. 

- **Headlines (Plus Jakarta Sans)**: High-geometry counters and sturdy grotesque proportions project modern industrial prestige and direct authority.
- **Body & Technical Specs (Inter)**: Delivers neutral, uncompromising readability in hardware specifications, lock operational logs, and data-dense enterprise settings.
- **Tracking & Proportion**: Headline scales (`display-hero` through `headline-md`) use `-0.02em` tight letter-spacing to reinforce density and solid weight. Technical labels (`label-telemetry`) utilize `+0.05em` wide uppercase tracking for immediate status detection.

## Layout & Spacing

The spatial engine utilizes a modular 12-column grid system built on an 8px base rhythm. Layouts convey strength through structured, orderly modularity rather than chaotic asymmetry.

- **Desktop (1280px+)**: 12 columns, 24px gutters, max content boundary of 1280px flanked by generous outer margins.
- **Tablet (768px - 1023px)**: 8 columns, 20px gutters, dynamic fluid side margins.
- **Mobile (< 767px)**: 4 columns, 16px gutters, 20px outer margin gutter. Stack multi-column hardware comparison tables into individual swipeable spec cards.
- **Rhythm**: Apply vertical section spacing at strict intervals of 4rem, 6rem, or 8rem to preserve premium breathing room between core product modules.

## Elevation & Depth

Depth mimics high-tolerance machined components and recessed sensor housings. Interfaces avoid muddy, heavy drop shadows in favor of ambient precision:

- **Level 0 (Recessed Chassis)**: `#F1F5F9` surfaces with an inner border stroke of `rgba(15, 23, 42, 0.06)` for device housings and data tables.
- **Level 1 (Card Deck)**: Pure white `#FFFFFF` surface accompanied by a hairline border `1px solid rgba(15, 23, 42, 0.08)` and subtle diffusion: `0 1px 3px rgba(15, 23, 42, 0.05), 0 4px 12px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Hardware Modules / Hover States)**: `0 8px 24px -4px rgba(15, 23, 42, 0.08), 0 2px 6px -1px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Interactive Overlays & Critical Modals)**: `0 20px 48px -12px rgba(15, 23, 42, 0.18)` paired with backdrop filter blur (`12px`) across semi-opaque surfaces (`rgba(255, 255, 255, 0.85)`).
- **Status Luminescence**: Critical biometric validation pulses leverage faint color blooms using cyan (`box-shadow: 0 0 16px rgba(6, 182, 212, 0.35)`).

## Shapes

The design system adopts a **Soft (Level 1)** structural radius. Physical security hardware is characterized by chamfered edges, machined metal plates, and tight mechanical tolerances. 

- Base UI components (standard buttons, input fields, and tags) adhere strictly to `0.25rem` (4px).
- Structural containers (cards, hardware telemetry panels, security matrices) scale to `0.5rem` (8px).
- Modal frames and large hero display casings use `0.75rem` (12px).
- Round pills are strictly limited to active connection dots and telemetry indicator badges. Completely circular shapes are reserved exclusively for fingerprint scanner targets and rotary lock icons.

## Components

### Buttons
- **Primary Action (Physical Unlock / Buy Now)**: High-density solid `#1E3A8A` background with crisp white text, `4px` corner radius, `1px` border of `rgba(255,255,255,0.12)`, height `44px`, padding `0 24px`. Transitions to `#172554` on hover with a sharp elevation lift.
- **Secondary (Telemetry / Tech Spec)**: Outlined `#334155` border with transparent background, `#0F172A` text. Hover transitions to `#F8FAFC` background.
- **Status Trigger**: Solid `#0D9488` for positive lock engagement, accompanied by an inline pulsing SVG lock glyph.

### Hardware & Feature Cards
- Constructed with `#FFFFFF` background, `8px` corner radius, and subtle outer stroke (`1px solid #E2E8F0`).
- Headers showcase the hardware tier in `label-telemetry` styling with uppercase tracking, a structural separator line, and an integrated technical specification matrix (e.g., "AES-256", "IP65 Rated", "Bluetooth LE").

### Status Chips & Badges
- Compact `20px` height containers with `4px` corner radius.
- Backgrounds use 10% tint of the status color with 100% solid color text and an internal `6px` circular pulse dot:
  - *Secured*: Cyan background (`rgba(6, 182, 212, 0.12)`), `#0E7490` text.
  - *Active Lock*: Teal background (`rgba(13, 148, 136, 0.12)`), `#0F766E` text.
  - *Low Battery / Jammed*: Amber/Coral background.

### Input Fields
- `44px` height, `#FFFFFF` background, bordered with `#CBD5E1`.
- Focus state switches border to `2px solid #1E3A8A` with an ambient glow ring of `0 0 0 3px rgba(30, 58, 138, 0.15)`. Labels sit fixed above the input in `label-md` weight `#334155`.

### Security Diagnostics & Key Management Lists
- Monospaced serial IDs rendered in `Inter` tabular figures.
- Alternating row backgrounds on `#FFFFFF` and `#F8FAFC` separated by `1px solid #EDF2F7`. Includes inline action controls for instant credential revocation.

### Lock Status Visualizer
- A dedicated interactive landing widget showcasing the lock core. Features a circular visual target flanked by real-time lock state indicators, an animated bolt-retraction status graphic, and encrypted token transfer diagrams.