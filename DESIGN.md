---
name: Fig & Filter
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  warm-off-white: '#FAF6F0'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 54px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 34px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 30px
  headline-sm:
    fontFamily: Newsreader
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 26px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system supports a neighbourhood café that roasts its own coffee and bakes on site daily. The interface is built for two distinct moments: a stranger on a phone deciding whether to walk in, and an office manager on a laptop comparing catering packages.

The aesthetic blends **Editorial Minimalism** with **Tactile Warmth**. Generous whitespace, unhurried typography, and a restrained palette let photography of espresso, pastry, and the shopfront carry the sensory weight. There are no decorative flourishes, no booking widgets, and no visual noise. Every page has one clear primary action; all other links remain plain and unobtrusive.

The emotional tone is **warm, plainspoken, and grounded**—like a chalkboard menu written by someone who cares about what they serve.

## Colors

The palette is anchored in a warm, paper-like light mode (`#FAF6F0`) paired with near-black ink (`#221E1F`) for high-contrast, comfortable reading.

- **Primary (`#4A2C4D` — Deep Fig Purple):** Reserved for the single primary call-to-action button on each page, active navigation states, and key structural accents.
- **Secondary (`#D9A441` — Warm Amber):** Used strictly for small accents—such as dietary markers, subtle dividers, or highlight badges. Never use Warm Amber for body text or large backgrounds, as it lacks sufficient contrast on light surfaces.
- **Neutral (`#221E1F` — Near-Black):** Used for all body copy, headings, and plain text links.
- **Background (`#FAF6F0` — Warm Off-White):** The default canvas color across all pages, evoking unbleached paper.

## Typography

Typography pairs an editorial serif with a straightforward sans-serif:

- **Headings (`Newsreader`):** Brings warmth, literary character, and craft to page titles, menu group headers, and catering package names. Use `display-lg-mobile` below `768px` so hero headlines fit cleanly on narrow phone screens.
- **Body & Labels (`Work Sans`):** Keeps menu descriptions, prices, opening hours, and navigation crisp and effortless to scan. Tabular numerals should be enabled for menu prices and hours tables so columns align cleanly.

## Layout & Spacing

This design system uses a **mobile-first fluid grid** that caps at a comfortable reading width on larger screens.

- **Mobile (`< 768px`):** Single-column layout with `1.25rem` (`20px`) outer margins. Critical information—such as opening hours and the Chalk Lane address—must sit above the fold without horizontal scrolling.
- **Tablet & Desktop (`>= 768px`):** Content centers within a `1040px` maximum container width with `1.25rem` gutters.
  - **Menu page:** Expands from one column on mobile to a maximum of two columns on desktop.
  - **Catering page:** Stacks the three packages vertically on mobile and places them side-by-side in a 3-column row on desktop.
- **Rhythm:** Use `space-xl` (`2.5rem`) between major page sections and `space-md` (`1rem`) between related items like menu rows.

## Elevation & Depth

Hierarchy is conveyed through **low-contrast outlines** and **tonal warmth** rather than drop shadows.

- **No drop shadows:** Cards, catering packages, and hours tables sit flush on the `#FAF6F0` canvas, separated by `1px` hairline borders in a muted warm-gray (`rgba(34, 30, 31, 0.14)`).
- **Hero photography:** Full-width imagery uses a subtle dark gradient scrim (`rgba(34, 30, 31, 0.45)`) behind white overlay text to guarantee legibility without feeling heavy.

## Shapes

UI elements use a **Soft (`1`)** corner radius (`0.25rem` / `4px` base, `0.5rem` for larger cards and containers). This subtle softening feels approachable and handcrafted without looking overly rounded or digital.

## Components

- **Primary Button:** Solid Deep Fig Purple (`#4A2C4D`) background with `#FAF6F0` text, `label-lg` typography, `0.25rem` radius, and generous horizontal padding (`space-lg`). Only **one** primary button appears per page (e.g., "Find us" on Home, "Order catering" on Catering).
- **Plain Links:** All secondary navigation and text links use Near-Black (`#221E1F`) with a simple `1px` underline. No pill backgrounds or button styling.
- **Dietary Markers (Chips):** Compact inline badges (`V`, `VG`, `GF`) styled with a `1px` Warm Amber (`#D9A441`) border and Near-Black (`#221E1F`) `label-sm` text.
- **Menu Lists:** Single-row items with the item name and dietary marker on the left, price right-aligned, and an optional `body-sm` description underneath, separated by `1px` hairline dividers.
- **Catering Package Cards:** Bordered containers (`1px` hairline) with `space-lg` internal padding, displaying the package title in `headline-md`, per-person price, and a concise bulleted list.
- **Hours Table:** Clean two-column key-value rows (day on the left, hours on the right) with `1px` bottom borders for instant scanning on mobile.