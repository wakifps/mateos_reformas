---
name: Arquitectura Pura
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#4d4540'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#7e756f'
  outline-variant: '#cfc4bd'
  surface-tint: '#635d5a'
  primary: '#181512'
  on-primary: '#ffffff'
  primary-container: '#2d2926'
  on-primary-container: '#96908b'
  inverse-primary: '#cdc5c0'
  secondary: '#934938'
  on-secondary: '#ffffff'
  secondary-container: '#ffa08b'
  on-secondary-container: '#793425'
  tertiary: '#201200'
  on-tertiary: '#ffffff'
  tertiary-container: '#382609'
  on-tertiary-container: '#a78c67'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9e1dc'
  primary-fixed-dim: '#cdc5c0'
  on-primary-fixed: '#1e1b18'
  on-primary-fixed-variant: '#4b4642'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a4'
  on-secondary-fixed: '#3c0701'
  on-secondary-fixed-variant: '#763223'
  tertiary-fixed: '#feddb3'
  tertiary-fixed-dim: '#e1c299'
  on-tertiary-fixed: '#281801'
  on-tertiary-fixed-variant: '#584324'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  headline-display:
    fontFamily: Playfair Display
    fontSize: 84px
    fontWeight: '700'
    lineHeight: 92px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 128px
---

## Brand & Style
The design system embodies a **Minimalist and Elegant** aesthetic tailored for a high-end architectural studio. The brand personality is sophisticated, precise, and authoritative, yet grounded by natural warmth. It targets a discerning clientele seeking structural integrity and artistic vision.

The visual language is characterized by:
- **Spatial Clarity:** Excessive whitespace is treated as a structural element, allowing architectural photography to breathe and command attention.
- **Modern Editorial:** A blend of high-fashion editorial layouts with the technical precision of architectural drafting.
- **Emotional Response:** The UI evokes a sense of calm, timelessness, and professional trust, mirroring the experience of entering a well-designed physical space.

## Colors
The palette is rooted in structural materials and natural landscapes. 

- **Primary (Obsidian):** A deep, near-black gray used for primary text and structural lines, representing iron and slate.
- **Secondary (Terracotta):** A warm, clay-inspired earth tone used sparingly for accents, call-to-actions, and active states.
- **Tertiary (Sand/Oak):** Subtle tones used for secondary backgrounds and dividers to soften the high-contrast transitions.
- **Neutral (Alabaster):** A crisp, warm white that serves as the canvas for the entire system.

Use high-contrast pairings (Obsidian on Alabaster) for maximum legibility and impact, reserving the earth tones for warmth and focus.

## Typography
The typography strategy utilizes a "Classic meets Modern" approach. 

**Playfair Display** is used for all headings to provide an authoritative, literary, and high-end feel. Use it in large scales for project titles and editorial sections. **Montserrat** provides a clean, geometric contrast for body copy and navigation, ensuring technical clarity and readability in Spanish.

For the Spanish language, ensure proper handling of accents (tildes) and wide character widths in button labels. Always maintain generous line heights to preserve the airy, minimalist feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy within a centered container for desktop, transitioning to a fluid model for mobile.

- **Desktop:** A 12-column grid with a maximum width of 1440px. Use wide 64px margins to frame the content like a gallery piece.
- **Section Gaps:** Use significant vertical spacing (128px+) between major sections to emphasize the "Minimalist" aesthetic.
- **Rhythm:** All spacing must be a multiple of the 8px base unit.
- **Reflow:** On mobile, columns collapse to a single stack. Margins reduce to 20px to maximize the impact of architectural photography on small screens.

## Elevation & Depth
This design system avoids traditional shadows to maintain a flat, architectural drafting feel. Depth is communicated through:

- **Tonal Layering:** Using the Sand/Oak tertiary colors to differentiate background surfaces from the main canvas.
- **Low-Contrast Outlines:** Use 1px solid borders in a light gray (e.g., #E0E0E0) to define structural containers or image frames without adding visual weight.
- **Image Overlaps:** Use subtle negative margins to allow images to overlap slightly into neighboring sections, creating a sophisticated 2D layered effect.
- **Interaction:** State changes are signaled by color shifts (e.g., Terracotta fills) rather than elevation or "lift."

## Shapes
The shape language is **Sharp (0)**. In alignment with structural architectural principles, all UI elements—including buttons, input fields, and image containers—feature 90-degree corners. This evokes a sense of precision, blueprints, and monolithic construction. Circular elements are reserved strictly for functional icons or specific decorative brand marks.

## Components
- **Buttons:** Primary buttons are obsidian rectangles with white uppercase text. Secondary buttons use a 1px obsidian border with no fill. Transitions should be instant or very fast (150ms).
- **Input Fields:** Bottom-border only design (drafting style) with labels using the `label-caps` style positioned above the line.
- **Cards:** Used for project portfolios. No borders or shadows; the image fills the width of the container, with the title and "Año" (Year) placed in a clean lockup below.
- **Chips/Tags:** Small, sharp-edged rectangles with a light Sand background and obsidian text, used for categorizing architectural styles (e.g., "Residencial", "Sostenible").
- **Lists:** Bulletless lists using a thin horizontal divider (1px) between items, mimicking an index or table of contents.
- **Project Navigation:** Large-scale "Next Project" footers that use `headline-lg` typography to encourage immersive browsing.