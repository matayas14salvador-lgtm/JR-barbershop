---
name: Nocturnal Heritage
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e9c176'
  primary: '#e9c176'
  on-primary: '#412d00'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#775a19'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#a7a5a5'
  on-tertiary-container: '#3b3b3b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
---

## Brand & Style

This design system embodies a fusion of **Neo-Noir Minimalism** and **Classical Luxury**. It is tailored for high-end audiences seeking exclusivity, sophistication, and a sanctuary of digital calm. The aesthetic is "Ultra-Premium": every interaction should feel deliberate, quiet, and substantial.

The style leverages deep, void-like blacks and dark navies to create an infinite sense of depth, contrasted by precise gold accents that mimic light reflecting off high-end hardware. Whitespace is used not as a gap, but as a luxury—giving content ample "room to breathe" against the dark canvas. The result is a moody, intellectual environment that feels more like an editorial piece or a high-end gallery than a standard application.

## Colors

The palette is anchored by **True Black (#000000)** to ensure absolute depth on OLED screens and **Dark Navy (#0a0a0a)** for subtle structural variance. 

- **Primary (Gold):** #c5a059. Used sparingly for calls to action, high-level indicators, and brand moments.
- **Secondary (Pure White):** #ffffff. Reserved for primary headings and critical text to ensure maximum legibility and "pop."
- **Tertiary/Muted:** #888888. Used for secondary text and decorative lines to maintain the moody atmosphere.
- **Surface Tiers:** Backgrounds transition from #000000 (base) to #0a0a0a (cards/containers) to #1a1a1a (hover states/elevated elements).

## Typography

The typography strategy relies on a high-contrast pairing of a classic serif and a precision-engineered sans-serif.

- **Headlines:** Uses *Playfair Display*. This brings a literary, editorial authority to the interface. Headlines should use "Optical Sizing" where possible.
- **Body & UI:** Uses *Manrope*. Its modern, balanced proportions provide a technical cleanliness that prevents the design from feeling overly "antique."
- **Styling Note:** For high-end headers, use gold (#c5a059) sparingly on a single keyword to draw the eye. All labels and overlines should be in uppercase with generous letter spacing (0.1em) to mimic luxury watch or fashion branding.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 

The spacing philosophy is "Expansive." We prioritize large margins and deep vertical gutters to prevent the dark background from feeling claustrophobic. 
- **Desktop:** 64px outer margins provide a "frame" effect for the content.
- **Rhythm:** Use an 8px base unit. Most components should use 24px or 32px of internal padding to maintain the premium, spacious feel.
- **Alignment:** Content is generally center-aligned for landing experiences to maintain a symmetrical, balanced weight, while functional dashboards utilize a left-aligned, structured layout.

## Elevation & Depth

In a luxury dark theme, traditional drop shadows are often invisible. Instead, we use **Tonal Layering** and **Luminous Outlines**:

1.  **Tonal Tiers:** Surfaces are defined by color shift rather than shadow. Level 0 is #000000; Level 1 is #0a0a0a; Level 2 is #141414.
2.  **Luminous Outlines:** Interactive cards and buttons use a subtle 1px border. For resting states, use #ffffff at 10% opacity. For hover/active states, use the primary gold (#c5a059) at 40-60% opacity.
3.  **Inner Glows:** To create a sense of the screen "emitting" light from the gold accents, use a very soft, low-spread gold glow (blur: 20px, opacity: 15%) behind primary buttons.

## Shapes

The shape language is **Soft (0.25rem)**. This "near-sharp" approach communicates precision and architectural rigor. 

- Large containers and cards should use `rounded-lg` (0.5rem) to feel approachable but never "bubbly."
- Buttons use the base `rounded` (0.25rem) to maintain a crisp, professional edge. 
- Avoid pill shapes or circles except for user avatars, as the structural integrity of rectangles better suits the "Heritage" narrative.

## Components

### Buttons
- **Primary:** Solid gold background (#c5a059) with black text (#000000). No shadow, but a subtle inner-bevel light effect on the top edge.
- **Secondary:** Transparent background with a 1px border (#ffffff at 20%). On hover, the border becomes gold and text brightens.

### Cards
- **Construction:** Background of #0a0a0a with a 1px border of #1a1a1a. 
- **Interaction:** On hover, the background shifts to #141414 and the border lightens.

### Input Fields
- **Style:** Underline-only or very subtle ghost-box (background #050505).
- **Focus:** The underline or border transitions to gold (#c5a059). Placeholder text should be a muted gray (#555555).

### Lists & Dividers
- Dividers should be extremely subtle (1px, #ffffff at 5% opacity). 
- List items should have generous vertical padding (minimum 16px) to maintain the editorial rhythm.

### Icons
- Use thin-stroke (Light or Regular weight) icons. 
- Primary icons are white; decorative or "feature" icons are gold. Avoid filled icon sets to keep the interface light and airy despite the dark color palette.