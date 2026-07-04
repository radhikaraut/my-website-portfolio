---
name: Executive FinTech Portfolio
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#43474e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#040607'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1f21'
  on-tertiary-container: '#848789'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  grid-gutter: 24px
  container-max-width: 1200px
---

## Brand & Style
The design system is engineered for a senior techno-functional executive within the high-stakes Banking and FinTech sectors. The brand personality is **authoritative, precise, and visionary**, balancing deep institutional trust with modern technological agility. 

The aesthetic follows a **Refined Minimalist** movement. It prioritizes clarity and high-value density through generous whitespace, ensuring that the executive’s career achievements and strategic insights remain the focal point. By stripping away decorative excess, the UI reflects a "signal-over-noise" philosophy essential for C-suite and board-level communication. Emotional responses should range from total reliability to forward-thinking innovation.

## Colors
This design system utilizes a high-contrast palette to establish immediate hierarchy and professional gravity.

- **Primary (Deep Navy):** Used for global navigation, structural headers, and primary branding elements. It signifies stability and legacy banking authority.
- **Accent (Burnt Orange):** Reserved strictly for high-impact calls to action (CTAs), progress indicators, and critical highlights. Its warmth offsets the coolness of the navy.
- **Surface (Subtle Gray):** Layered over the crisp white background to define logical groupings such as project cards or skill clusters without the weight of heavy borders.
- **Text (Charcoal):** Set to #1A1A1A to ensure maximum accessibility and a softer, more sophisticated look than pure black.

## Typography
The typography system uses **Geist** for headlines and interactive elements to provide a precise, technical feel, while **Inter** is utilized for body copy to ensure world-class readability across long-form executive summaries and case studies.

- **Scale:** High contrast between display sizes and body text to create a clear information architecture.
- **Line Height:** Generous leading (1.7) is applied to body text to facilitate effortless scanning of complex technical descriptions.
- **Letter Spacing:** Headlines utilize slight negative tracking for a "locked-in" professional appearance, while labels use expanded tracking for clarity at small scales.

## Layout & Spacing
The design system employs a **12-column fixed grid** on desktop, transitioning to a fluid single-column layout on mobile devices. 

- **Vertical Rhythm:** Sections are separated by significant vertical gaps to allow content to "breathe," mirroring the layout of high-end editorial journals.
- **Alignment:** All content follows a strict baseline grid. Projects and skill blocks are organized in a 2 or 3-column configuration on desktop to maintain a balanced, structured appearance.
- **Breakpoints:**
  - **Mobile:** < 768px (16px margins, 16px gutter)
  - **Tablet:** 768px - 1024px (32px margins, 24px gutter)
  - **Desktop:** > 1024px (Auto margins, 1200px max-width)

## Elevation & Depth
Depth is signaled through **Subtle Ambient Shadows** rather than physical borders. This preserves the minimalist ethos while creating a clear stack order.

- **Level 0 (Background):** Pure White (#FFFFFF).
- **Level 1 (Cards/Surfaces):** Very subtle light gray (#F8FAFC) with a 1px soft stroke (#E2E8F0) to define boundaries.
- **Level 2 (Interactive):** Elements like "Project Cards" utilize a diffused shadow (Y: 4px, Blur: 20px, 4% Opacity) that intensifies slightly upon hover to provide tactile feedback.
- **Backdrop Blurs:** Used sparingly behind navigation bars (10px blur) to maintain context during scrolling.

## Shapes
The shape language is **geometric and precise**. 

- **Standard Elements:** Buttons and input fields use a "Soft" (0.25rem) radius, reflecting a controlled and modern environment.
- **Profile Imagery:** The primary executive portrait must be contained within a perfect circle. This acts as a visual "anchor" and a soft counterpoint to the otherwise rectangular grid.
- **Project Thumbnails:** Use the `rounded-lg` (0.5rem) setting to distinguish content containers from functional UI components like buttons.

## Components
- **Buttons:** Primary buttons are solid Deep Navy with white text. Secondary buttons are outlined with the Accent Orange. Both use a medium-weight Geist font for clarity.
- **Project Cards:** Feature a background-fill transition on hover. They display a "Category" label using the `label-caps` style above the main title.
- **Skill Chips:** Subtle gray backgrounds with Deep Navy text, used to categorize technical proficiencies. No borders; use 4px padding.
- **Input Fields:** Minimalist design with only a bottom-border visible in a neutral state, transforming into a full Deep Navy outline when focused.
- **Profile Section:** Hero section featuring a large circular image (min 240px) on the left or center, with the display-lg headline providing immediate impact.
- **Data Visualization:** Any charts or metrics should use the Primary Navy for the baseline and the Accent Orange for the "Success" or "Growth" metric to drive the executive narrative.