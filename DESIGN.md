---
name: Luminous Engineering
colors:
  surface: '#15121b'
  surface-dim: '#15121b'
  surface-bright: '#3c3742'
  surface-container-lowest: '#100d16'
  surface-container-low: '#1d1a24'
  surface-container: '#221e28'
  surface-container-high: '#2c2833'
  surface-container-highest: '#37333e'
  on-surface: '#e8dfee'
  on-surface-variant: '#ccc3d8'
  inverse-surface: '#e8dfee'
  inverse-on-surface: '#332f39'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d2bbff'
  primary: '#d2bbff'
  on-primary: '#3f008e'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#732ee4'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ffb784'
  on-tertiary: '#4f2500'
  tertiary-container: '#a15100'
  on-tertiary-container: '#ffe0cd'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb784'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#713700'
  background: '#15121b'
  on-background: '#e8dfee'
  surface-variant: '#37333e'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: SpaceGrotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  code-snippet:
    fontFamily: JetBrainsMono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system establishes a premium, high-tech identity for a back-end specialist. The brand personality is rooted in technical mastery, precision, and the "invisible architecture" of high-end software. It aims to evoke a sense of calm authority and futuristic sophistication.

The visual style is **Modern Dark Mode with Glassmorphism**. This aesthetic utilizes deep, oceanic blacks to represent the stability of the back-end, while vibrant gradients and frosted glass elements represent the light of innovation and clean code surfacing through the dark. The UI relies on depth, translucency, and light-refraction effects to differentiate from traditional flat portfolios.

## Colors

The palette is designed for deep immersion and visual comfort during long sessions.
- **Surface Strategy:** The primary canvas uses a deep navy-black to provide maximum contrast for the accent elements.
- **Accents:** A "Command Gradient" (Purple-to-Cyan) is used sparingly for interactive states, progress indicators, and focal points.
- **Typography Tiers:** Pure white is reserved for headings and primary actions. Muted silver (Slate-400) is used for body text and metadata to reduce eye strain and establish a clear hierarchy.
- **Glass Shimmer:** Surfaces are not solid; they are semi-transparent with a subtle white tint to catch the light, simulating frosted glass.

## Typography

This design system uses a dual-font strategy to balance human-centric design with technical precision.
- **Primary Face:** **Inter** provides a clean, geometric foundation that feels contemporary and highly legible across all weights.
- **Technical Face:** **Space Grotesk** is used for labels and secondary headings to inject a subtle "tech-industrial" feel.
- **Monospace:** For a back-end developer, code is a primary asset. **JetBrains Mono** is utilized for all code blocks and technical specifications to ensure maximum readability and a professional developer aesthetic.
- **Scale:** High-contrast sizing is used to guide the viewer's eye through the portfolio narrative, with massive display headers for project titles.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid with Generous Whitespace**. 
- **The Grid:** A 12-column desktop grid with wide gutters allows the glassmorphic cards to breathe and prevents the UI from feeling cluttered.
- **Rhythm:** An 8px base unit governs all dimensions. Vertical spacing between sections is intentionally large (120px+) to create a "gallery" feel where each project or skill-set is viewed as a distinct exhibit.
- **Responsive Adaption:** On mobile, the layout collapses to a single column with 20px side margins, while headline sizes are scaled down by 30% to maintain visual balance and prevent awkward wrapping.

## Elevation & Depth

Depth is the cornerstone of this design system. Instead of traditional shadows, depth is communicated through:
- **Backdrop Blurs:** All container elements use a `20px` to `40px` backdrop-filter blur. This creates a sense of "physical distance" between the UI layer and the animated background.
- **Luminous Borders:** Containers feature a top-and-left oriented white border at `0.1` opacity, simulating a light source hitting the edge of a glass pane.
- **Ambient Glows:** High-priority elements (like active project cards) feature a soft, colored outer glow that matches the accent gradient (Purple/Cyan), suggesting that the element is "energized."

## Shapes

The shape language is refined and "Soft-Tech." 
- **Containers:** We use a base roundedness of `0.5rem` (8px) for cards and inputs. This provides a modern, approachable feel without being overly "bubbly."
- **Interactive Elements:** Buttons and tags utilize a higher roundedness (`1rem`) to distinguish them as clickable objects from structural layout elements.
- **Progress Bars:** Animated bars use fully rounded caps (Pill) to emphasize fluid movement.

## Components

### Buttons
- **Primary:** Gradient background (Purple-to-Cyan) with white text. On hover, the glow intensity increases.
- **Secondary/Ghost:** A thin glass border with no fill. On hover, a subtle cyan tint fills the background.

### Project Cards
The hero component of the portfolio. Features a high-blur glass background, a subtle 1px border, and a "hover-lift" animation where the card scales by 1.02x and the backdrop blur increases.

### Form Fields (Floating Labels)
Inputs appear as a simple underline or a very faint glass plate. Upon focus, the label shrinks and floats above the field, transitioning from muted silver to cyan.

### Chips & Tags
Used for tech stacks (e.g., "Node.js", "PostgreSQL"). These are small, semi-transparent capsules with a subtle purple border to keep them distinct but secondary to the primary content.

### Animated Progress Bars
Used to visualize skill proficiency or project completion. These should feature a "shimmer" effect moving across the gradient fill to indicate activity and life within the back-end systems.