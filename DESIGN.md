---
name: Academic Excellence & Modern Science
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#44474e'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#485f83'
  primary: '#00142f'
  on-primary: '#ffffff'
  primary-container: '#0f294a'
  on-primary-container: '#7a91b7'
  inverse-primary: '#b0c8f1'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#001626'
  on-tertiary: '#ffffff'
  tertiary-container: '#002b45'
  on-tertiary-container: '#2f96db'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#b0c8f1'
  on-primary-fixed: '#001b3b'
  on-primary-fixed-variant: '#30476a'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: 4rem
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
  headline-md:
    fontFamily: Newsreader
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
  headline-sm:
    fontFamily: Newsreader
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.06em
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
  margin: 2rem
  margin-mobile: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the tradition of scholarly prestige blended with modern scientific inquiry. Designed for students, parents, faculty, and research affiliates, the UI communicates authority, rigorous intellectual ambition, and forward-looking optimism. 

The aesthetic is Modern Collegiate: a synthesis of structured editorial layout, clean architectural grids, and refined material details. The experience avoids sterile enterprise minimalism and chaotic youthful playfulness in favor of timeless academic credibility. Subtle micro-interactions, clean hairline borders, and disciplined card architectures reinforce clarity, focus, and prestige.

## Colors

The palette establishes an immediate sense of institutional heritage and energetic innovation:
- **Primary Navy (`#0F294A`):** Anchors the brand with institutional gravity, intellectual rigor, and trust. Used for primary navigation, primary action buttons, dark hero states, and dominant brand headers.
- **Secondary Amber/Gold (`#D97706`):** Infuses vitality, honor, and achievement. Reserved for key calls to action, badges of excellence, active indicator states, and editorial highlights.
- **Tertiary Cyan (`#0284C7`):** Represents scientific curiosity, STEM pathways, and laboratory research initiatives. Applied to secondary data visualizations, interactive links, and technical tags.
- **Neutral Slate (`#475569`):** Governs structural body typography and understated UI elements.
- **Surface Foundations:** Backgrounds default to soft architectural slate tints (`#F8FAFC` to `#F1F5F9`) paired with crisp white card surfaces (`#FFFFFF`) to maintain optical comfort during intensive study or administrative review. Charcoal (`#0F172A`) is designated for high-contrast body reading.

## Typography

Typography establishes an intentional dichotomy between historical institution and scientific forward-momentum:
- **Headings (Newsreader):** Brings editorial grace, classical scholarship, and authoritative warmth. Display titles pair italicized serif flourishes for secondary commentary with confident medium/semibold weights for section headers.
- **Interface & Content (Plus Jakarta Sans):** Delivers clean geometry, exceptional screen legibility at small sizes, and contemporary clarity for portal dashboards, scientific tables, and body copy.
- **Hierarchical Discipline:** All academic titles, thesis summaries, and programmatic milestones use Newsreader. Data tables, schedules, form controls, navigation labels, and interactive metrics rely on Plus Jakarta Sans with explicit tracking on uppercase labels.

## Layout & Spacing

The layout is built upon an architectural 12-column fluid grid system, adapting to 8 columns on tablet and 4 columns on mobile.
- **Rhythm & Grid:** Content regions use disciplined multi-tier structures. Academic modules, curriculum pathways, and research showcases standardly occupy 3, 4, 6, or 12 columns.
- **Breakpoints:**
  - **Mobile (< 768px):** 4 columns, `margin-mobile` (1rem), compact vertical stacks with tight `gutter-mobile` (1rem).
  - **Tablet (768px – 1024px):** 8 columns, `margin` (2rem), fluid split cards.
  - **Desktop (> 1024px):** 12 columns capped at a maximum container width of `1280px` centered, utilizing `margin-desktop` (3rem) and `gutter` (1.5rem).
- **Density:** Educational administration portals and gradebooks utilize compact component padding (`space-xs` and `space-sm`), whereas admissions and curriculum showcase layouts employ spacious breathing room (`space-lg` and `space-xl`).

## Elevation & Depth

Visual hierarchy relies on structural hairline delineation, stratified slate surfaces, and soft academic shadows:
- **Structural Outlines:** Clean borders in `rgba(15, 41, 74, 0.08)` (light mode) or subtle slate divisions maintain crisp, paper-like boundaries across all content containers.
- **Ambient Elevation:** Shadows are strictly low-contrast and diffused with a cool navy tint to avoid heavy charcoal drop shadows:
  - *Elevation 1 (Cards, Modules):* `0 1px 3px rgba(15, 41, 74, 0.05), 0 1px 2px rgba(15, 41, 74, 0.03)`
  - *Elevation 2 (Dropdowns, Hover States):* `0 4px 12px -2px rgba(15, 41, 74, 0.08), 0 2px 6px -1px rgba(15, 41, 74, 0.04)`
  - *Elevation 3 (Modals, Dialogs):* `0 12px 28px -4px rgba(15, 41, 74, 0.14), 0 6px 12px -2px rgba(15, 41, 74, 0.06)`
- **Layering:** Backgrounds layer sequentially from `slate-100` (`#F1F5F9`) canvas to `white` card surface, punctuated by tinted primary navy surfaces for callouts and credential ribbons.

## Shapes

The shape system adopts a soft, tailored profile (Level 1 / Soft):
- **Base Rounding (0.25rem / 4px):** Input fields, inline tags, data grid rows, and table cells.
- **Medium Rounding (0.5rem / 8px):** Primary UI cards, interactive action blocks, standard buttons, and dialogs.
- **Large Rounding (0.75rem / 12px):** Hero banners, featured programmatic highlight containers, and modal window frames.
- **Pill Accents:** Reserved strictly for status badges (e.g., "Honors", "STEM Accredited", "Admissions Open") to preserve the clean architectural discipline of all structural layouts.

## Components

### Buttons
- **Primary:** Background in primary navy (`#0F294A`), label in white (`#FFFFFF`), `0.5rem` border radius, semi-bold typography. Hover triggers a subtle lightening to `#1A3D68` with a micro-lift shadow.
- **Secondary (Honor/Action):** Background in gold/amber (`#D97706`), label in dark navy or pure white depending on WCAG AAA criteria, reserved for critical conversion moments like "Apply Now" or "Book Campus Tour".
- **Tertiary / Outline:** Hairline border (`1px solid #CBD5E1`), background transparent, text in navy. Hover shifts to soft slate (`#F8FAFC`).

### Input Fields & Selects
- Constructed with a crisp 1px border (`#CBD5E1`), pure white background, and a 4px corner radius.
- Active and focused inputs transition border color to primary navy (`#0F294A`) paired with a 2px outer focus ring in translucent amber (`rgba(217, 119, 6, 0.2)`).
- Field labels use `label-md` uppercase styling with subtle tracking for academic precision.

### Cards & Academic Containers
- White foundation (`#FFFFFF`), encased in a hairline border (`1px solid rgba(15, 41, 74, 0.08)`), supported by Elevation 1.
- Header divisions within cards feature an optional top accent rule (2px height in gold or tertiary cyan) to categorize faculty departments, science labs, or K-12 stages.

### Chips & Badges
- **Academic Badges:** Full pill-shaped geometry, uppercase `label-sm` tracking.
- **Curriculum Chips:** Soft rounded (4px) with subtle tinted backgrounds (e.g., pale cyan `#E0F2FE` with deep blue text `#0369A1` for STEM; warm amber `#FEF3C7` with `#92400E` for Honors).

### Checkboxes & Radios
- Square with 3px radius for checkboxes; circular for radios.
- Unchecked states use a 1.5px border (`#94A3B8`). Checked states fill with primary navy (`#0F294A`) featuring a crisp white geometric icon check or center dot.

### Specialized Academic Modules
- **Academic Crest Seal Containers:** Circular iconography shields integrated into headers with an embossed thin gold border ring.
- **Curriculum Progress Trackers:** Step indicators styled as numbered scholastic nodes connected via hairline slate paths, highlighted in gold for completed milestones.