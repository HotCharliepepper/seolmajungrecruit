---
name: Heritage Modernist
colors:
  surface: '#fdf9f1'
  surface-dim: '#dddad2'
  surface-bright: '#fdf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3eb'
  surface-container: '#f1ede6'
  surface-container-high: '#ece8e0'
  surface-container-highest: '#e6e2da'
  on-surface: '#1c1c17'
  on-surface-variant: '#4e4542'
  inverse-surface: '#31302b'
  inverse-on-surface: '#f4f0e8'
  outline: '#807571'
  outline-variant: '#d1c4bf'
  surface-tint: '#675c58'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#221a17'
  on-primary-container: '#8e817d'
  inverse-primary: '#d3c3be'
  secondary: '#7e5719'
  on-secondary: '#ffffff'
  secondary-container: '#fec880'
  on-secondary-container: '#795214'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2f1500'
  on-tertiary-container: '#ae784e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#efdfda'
  primary-fixed-dim: '#d3c3be'
  on-primary-fixed: '#221a17'
  on-primary-fixed-variant: '#4f4541'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#f2bd76'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#f8b98a'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#673c17'
  background: '#fdf9f1'
  on-background: '#1c1c17'
  surface-variant: '#e6e2da'
  deep-burgundy: '#4a1817'
  warm-beige: '#fffaf2'
  ivory-white: '#fffdf8'
  muted-gold: '#dcc9af'
  text-description: '#655850'
typography:
  hero-title:
    fontFamily: hankenGrotesk
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.06em
  section-title:
    fontFamily: hankenGrotesk
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.3'
    letterSpacing: -0.055em
  card-heading:
    fontFamily: hankenGrotesk
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1.4'
    letterSpacing: -0.02em
  body-main:
    fontFamily: hankenGrotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.035em
  eyebrow:
    fontFamily: hankenGrotesk
    fontSize: 12px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: 0.12em
  label-sm:
    fontFamily: hankenGrotesk
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0em
  hero-title-mobile:
    fontFamily: hankenGrotesk
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 860px
  section-gap: 2.5rem
  grid-gutter: 1rem
  card-padding: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 1.5rem
---

## Brand & Style

The design system is crafted for a premium Korean dining recruitment experience that balances traditional heritage with a contemporary, trendy aesthetic. It targets 20-30s applicants who value professionalism, workplace culture, and high-end brand associations.

The visual style is a blend of **Minimalism** and **Tactile Modernism**. It utilizes generous whitespace and a rigid 860px max-width container to create an editorial, magazine-like feel. The interface feels "warm-premium"—avoiding the coldness of typical corporate tech sites by using organic tones, soft layered shadows, and subtle glassmorphism. The goal is to evoke a sense of pride and belonging, framing the employment opportunity as a "lifestyle" choice rather than just a job.

## Colors

The palette is rooted in an "Earth & Gold" philosophy. 

- **Primary (Deep Charcoal):** Used for core text and dark hero backgrounds to establish authority and high-contrast sophistication.
- **Secondary (Brand Gold):** Reserved for high-importance highlights, logo elements, and primary call-to-actions to signify the "premium" nature of the brand.
- **Tertiary (Accent Brown):** Used for category labels (eyebrows) and iconography to bridge the gap between the dark text and the light background.
- **Neutral (Page Background):** A soft, warm off-white that prevents eye fatigue and maintains a welcoming, "neat" atmosphere.

Avoid pure blacks or greys. All neutral shades must contain a hint of warmth (yellow/red) to maintain the brand’s hospitable character.

## Typography

This design system uses a high-performance sans-serif stack to ensure a "trendy" and "sophisticated" feel. The core characteristic is **weight contrast**: pairing very heavy headlines (ExtraBold 800) with clean, airy body text (Regular 400).

- **Headlines:** Use tight letter spacing to create a dense, impactful visual block.
- **Eyebrows:** Always in uppercase with generous letter spacing to act as a structural anchor for sections.
- **System Font Fallback:** In production, prioritize *Pretendard* or *Apple SD Gothic Neo* for optimized Korean character rendering, maintaining the specific weights defined.

## Layout & Spacing

The layout is a **fixed-width, centered container** optimized for job platforms and mobile-first viewing. 

1.  **Container:** The content is strictly capped at 860px to ensure an editorial, readable line length.
2.  **Rhythm:** An 8px/4px base grid governs all components. Section gaps are intentionally large (approx. 36-40px) to provide "breathing room" between disparate info blocks (Positions vs. Benefits).
3.  **Grids:**
    *   **Positions:** 2-column grid on desktop, 1-column on mobile.
    *   **Benefits:** 3-column grid on desktop, 2-column on mobile.
4.  **Responsive Reflow:** On mobile devices, side margins shrink to 16px. Complex grid layouts (like the Hero Triptych) should stack or simplify into a single focused image with centered text.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Tinted Shadows**. 

- **Tonal Layers:** The background is `neutral`. Content is housed in `ivory-white` cards to create a subtle lift.
- **Shadows:** Avoid grey shadows. Use a "Warm Umber" shadow (`rgba(64,42,24,.08)`) to maintain the earthy aesthetic. Shadows should be diffused and soft, with a significant vertical offset to simulate a light source from above.
- **Glassmorphism:** Use for labels placed directly over high-quality imagery. A 6px backdrop blur with a semi-transparent dark-brown fill ensures legibility while maintaining the premium "depth."

## Shapes

The shape language is **Rounded**, conveying approachability.

- **Primary Cards:** Use a 22px-24px radius (`rounded-lg` or `rounded-xl` equivalent) to feel soft and modern.
- **Hero/Header:** Features a distinctive 28px bottom-only radius to "cradle" the content below.
- **Buttons & Chips:** Use 18px radius or pill-shapes for interactive elements to make them feel "clickable" and tactile.
- **Separators:** Use 1px dashed borders in `tertiary` colors for internal card divisions to add a touch of craft and "tailored" detail.

## Components

- **Buttons:** Primary CTAs use the `deep-burgundy` gradient with white text. They should have a subtle inner glow or border to enhance the premium feel.
- **Information Cards:** Utilize the `ivory-white` surface. They must include a `1px` low-contrast warm border to define their edges against the page background.
- **Position Chips:** Small, high-contrast labels (e.g., "Full-time", "D-7") using the `brand-gold` or `accent-brown`.
- **Image Placeholders:** All images must have a 24px corner radius and a subtle dark-to-transparent linear gradient overlay (bottom-to-top) to ensure white typography remains legible.
- **Recruitment Process:** A horizontal or vertical list using "Pill" shaped step numbers in `accent-brown` with `white` text.
- **Checklists:** Use a custom icon (e.g., a stylized check or the `✓` character) in `accent-brown` rather than default browser styling.