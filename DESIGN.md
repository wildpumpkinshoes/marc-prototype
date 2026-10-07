---
name: Marc Civic Trust
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191c22'
  surface-container: '#1d2027'
  surface-container-high: '#272a31'
  surface-container-highest: '#32353c'
  on-surface: '#e0e2ec'
  on-surface-variant: '#c3c6ce'
  inverse-surface: '#e0e2ec'
  inverse-on-surface: '#2d3038'
  outline: '#8d9198'
  outline-variant: '#43474d'
  surface-tint: '#b0c9e8'
  primary: '#b0c9e8'
  on-primary: '#19324b'
  primary-container: '#0f2942'
  on-primary-container: '#7991af'
  inverse-primary: '#49607c'
  secondary: '#6bd8cb'
  on-secondary: '#003732'
  secondary-container: '#29a195'
  on-secondary-container: '#00302b'
  tertiary: '#93ccff'
  on-tertiary: '#003351'
  tertiary-container: '#002a44'
  on-tertiary-container: '#2e95da'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b0c9e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#10131a'
  on-background: '#e0e2ec'
  surface-variant: '#32353c'
typography:
  display:
    fontFamily: Montserrat
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.5rem
    letterSpacing: -0.025em
  display-mobile:
    fontFamily: Montserrat
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 1.625rem
    fontWeight: '700'
    lineHeight: 2.125rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Montserrat
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Montserrat
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Montserrat
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Montserrat
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Montserrat
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Montserrat
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Montserrat
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
  code-badge:
    fontFamily: Montserrat
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies authoritative public-sector trust, deep civic empathy, and utilitarian clarity. Tailored for Massachusetts residents, agency case managers, and front-line service providers navigating critical social safety nets (SNAP, TAFDC, MassHealth, fuel assistance), the visual language eliminates anxiety through structural stability, crystal-clear information architecture, and rigorous WCAG AAA compliance.

The design movement is **Modern Institutional / Civic Humanist**. It blends the structural sobriety of governmental portals with warm, human-centered modern SaaS ergonomics. Visual elements prioritize readability over ornamentation: clean spatial divisions, explicit provenance indicators (such as state source badges and verification timestamps), high-contrast borders, and structured hierarchy that remains rock-solid whether accessed on a low-end smartphone in a transit lobby or an agency dual-monitor workstation.

## Colors

The color system is calibrated for institutional authority, calm reassurance, and high legibility. 

- **Primary (`#0F2942` - Civic Deep Navy):** Represents state gravity, permanence, and primary navigational landmarks. Used for main action buttons, major typography headers, and active structural chrome.
- **Secondary (`#0D9488` - Commonwealth Deep Teal):** Signals progress, assistance confirmation, and community service workflows.
- **Tertiary (`#0284C7` - Beacon Sky Blue):** Provides a lively directional signal for links, active interactive focus states, and discovery chips.
- **Neutral (`#1C1F26` - Charcoal Ink):** Used for all primary body text, ensuring a minimum contrast ratio against surfaces for maximum accessibility across all visual acuities.
- **Canvas & Surface System:** Crisp card layers sit upon slate backgrounds establishing depth through tonal differentiation rather than heavy drop shadows.
- **Provenance & Verification Badges:** Specific semantic tokens (`status-verified`, `status-alert`, and `ai-provenance`) distinguish between official Mass.gov DTA source feeds, recent manual case-worker verification, and machine-assisted benefit calculations.

## Typography

The design system uses **Montserrat** across all text levels. It delivers rigorous institutional authority, expansive language support, and open aperture clarity for complex civic criteria.

- **Headlines:** Set with heavier weights (`600` to `800`) and subtle negative letter spacing to provide solid anchor points for rapid skimming.
- **Body:** Standardized with generous line heights (`1.5` to `1.55`) to reduce cognitive strain for users under duress or reading dense policy requirements.
- **Labels & Metadata:** Styled at `label-md` and `label-sm` with slight positive tracking to ensure absolute clarity on administrative timestamps, program application steps, and state verification notices.

## Layout & Spacing

A predictable 12-column fluid grid system structures the desktop experience, collapsing gracefully into 8 columns on tablet viewports and 4 columns on mobile devices.

- **Breakpoints:** Mobile (`< 640px`), Tablet (`640px - 1024px`), Desktop (`> 1024px`).
- **Rhythm:** Spacing follows a strict 8-point structural system, with a 4-point micro-scale (`space-xs` = 4px) for compact tags, form metadata, and badge padding.
- **Max Content Container:** Primary content wells cap at `1200px` to maintain optimal line lengths for reading complex statutory requirements, while utility dashboards can expand to `1440px`.
- **Reflow Rules:** Benefit cards, program filter bars, and verification metadata stacks reflow vertically without horizontal overflow, safeguarding functionality on mobile devices.

## Elevation & Depth

This system intentionally departs from deep, floaty shadows, opting for **tactile structural planes and tonal layering** to maintain civic sobriety and performance integrity.

- **Level 0 (Flat Canvas):** Base canvas set at dark tones.
- **Level 1 (Cards & Modules):** Surface bordered by a crisp outline. Shadows are restrained.
- **Level 2 (Hover States & Interactive Tiles):** Light shift on elevation accompanied by border changes.
- **Level 3 (Modals, Overlays & Benefit Drawers):** High-priority focus overlays backed by authoritative backdrop tints.

## Shapes

With a roundedness level of `2`, the system strikes an intentional balance: human-friendly and inviting without looking frivolous or game-like.

- **Standard Elements (Buttons, Inputs, Badges):** Feature `0.5rem` (`8px`) border radii, yielding welcoming touchpoints.
- **Containers (Cards, Benefit Summary Panels, Alert Banners):** Use `rounded-lg` (`1rem` / `16px`) to distinguish discrete program packages.
- **Modal Dialogs & Hero Shelves:** Utilize `rounded-xl` (`1.5rem` / `24px`) to create gentle framing around complex application journeys.

## Components

### Buttons
- **Primary:** Background `#0F2942`, foreground `#FFFFFF`, height `48px`, font `label-md`. Focus state uses an accessible high-contrast outer ring: `3px solid #0284C7` offset by `2px`.
- **Secondary:** Transparent background, `1.5px solid #0F2942`, text `#0F2942`. Active hover shifts to surface tracks.
- **Tertiary / Assist:** Background `#0D9488`, foreground `#FFFFFF`. Reserved for life-line actions (e.g., "Find Nearest Food Pantry Now").

### Badges & Verification Chips
- **Mass.gov DTA Source Badge:** High-contrast civic badge. Border `1px solid #94A3B8`. Features a leading state seal/department check icon and uppercase `code-badge` typography.
- **Human-Verified Notice:** Indicates explicit case-worker sign-off with last-checked date.
- **AI Assist Tag:** Explicitly labels algorithmic eligibility calculations to preserve transparency.

### Cards
- **Benefit Directory Card:** Background cards, border, padding `space-lg`. Contains three distinct horizontal zones:
  1. Top metadata band with category chips and verification stamps.
  2. Core content tier with `headline-sm` title, providing income caps and benefit amounts in bold callouts.
  3. Action bar featuring next application steps and external agency links.

### Input Fields & Controls
- **Text Inputs:** Height `48px`, border `1.5px solid #94A3B8`. Focused state: border `#0F2942` with `3px solid #0284C7` halo.
- **Checkboxes & Radios:** Generous `22px × 22px` clickable footprint with `2px` solid stroke to ensure instant motor-skill accessibility.

### Lists & Key-Value Rules
- Clean rule summaries separated by clean dividers, using bold labels on the left and accessible secondary values on the right for clear eligibility self-assessment.