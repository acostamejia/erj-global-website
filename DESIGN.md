---
name: ERJ Global Design System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#43474f'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#006e25'
  on-secondary: '#ffffff'
  secondary-container: '#80f98b'
  on-secondary-container: '#007327'
  tertiary: '#1c1f20'
  on-tertiary: '#ffffff'
  tertiary-container: '#313435'
  on-tertiary-container: '#9a9c9d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#83fc8e'
  secondary-fixed-dim: '#66df75'
  on-secondary-fixed: '#002106'
  on-secondary-fixed-variant: '#00531a'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  title-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
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
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  section-padding-v: 5rem
  section-padding-v-mobile: 3rem
  stack-gap: 1rem
  grid-columns: '12'
---

## Brand & Style

The visual identity is anchored in the intersection of heavy-duty engineering and sustainable progress. The design system project an image of technical precision, institutional stability, and environmental responsibility. 

The aesthetic follows a **Modern Corporate** movement with a "Technical-Humanist" twist. It utilizes expansive whitespace to denote clarity and organization, high-contrast typography to convey authority, and a disciplined application of geometric accents. The interface should feel constructed rather than merely assembled, mirroring the architectural and engineering excellence of the firm.

## Colors

The palette is strategically limited to reinforce a professional engineering aesthetic.

*   **Primary (Navy Blue):** Used for structural elements, top-level navigation, and headings. It represents the "foundational" aspect of the business.
*   **Secondary (Sustainability Green):** Reserved for action-oriented elements and highlights related to renewable energy or growth. Use this sparingly to maintain high impact.
*   **Backgrounds:** The primary canvas is Pure White (#FFFFFF). Light Gray (#F8F9FA) is used exclusively as a section delimiter to break up long-form content on the single-page layout without introducing heavy visual weight.
*   **Typography:** Dark Gray (#333333) ensures optimal legibility for body copy, while Navy Blue is used for titles to create a distinct visual hierarchy.

## Typography

This system uses a dual-font approach to balance technical impact with readability.

**Montserrat** is used for all headings and display text. Its geometric construction mirrors the precision of engineering blueprints. **Inter** is utilized for body text and functional labels due to its exceptional legibility and systematic appearance at smaller scales.

For the one-page landing environment, utilize `display-lg` for the hero section and `headline-md` for major section transitions. `label-caps` should be used for small overlines or categorization tags above headings.

## Layout & Spacing

The layout follows a **Fixed-Fluid Grid** hybrid. Content is contained within a 1280px maximum width for desktop readability but utilizes a fluid 12-column system for internal positioning.

*   **Rhythm:** Use an 8px base grid for all internal component spacing (padding, gaps). 
*   **Sections:** Vertical spacing between major sections must be significant (`section-padding-v`) to provide the requested "high whitespace" feel.
*   **Mobile:** On devices below 768px, the 12-column grid collapses into a single-column stack. Margins reduce to 1rem while maintaining generous vertical padding between sections to prevent the content from feeling cramped.

## Elevation & Depth

To maintain a "Professional Engineering" aesthetic, the system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

*   **Surfaces:** Use flat white surfaces on Light Gray (#F8F9FA) backgrounds to denote interactive modules or featured cards.
*   **Shadows:** When depth is required (e.g., hover states on cards), use a "Technical Shadow": 0px 4px 20px rgba(0, 51, 102, 0.08). The blue tint in the shadow maintains brand consistency and feels more sophisticated than neutral gray.
*   **Delimiters:** Use 1px borders in Light Gray (#E9ECEF) for subtle separation between list items or grid elements.

## Shapes

The shape language is primarily **Geometric and Soft**. While the brand is technical, overly sharp corners can feel aggressive. A standard `0.25rem` radius (Soft) is applied to buttons and inputs to provide a modern, accessible feel. 

Large-scale containers or image frames may use larger radii (`rounded-lg`) to soften the visual impact of heavy industrial photography. Avoid pill-shaped buttons; rectangular buttons with soft corners maintain the "Construction/Engineering" metaphor more effectively.

## Components

*   **Buttons:**
    *   *Primary:* Navy Blue background with White text. Bold weight.
    *   *CTA (Call to Action):* Sustainability Green background with White text. Used for "Request a Quote" or "Contact Us."
    *   *Ghost:* Transparent background with Navy Blue border and text.
*   **Cards:** Use a white background, a 1px Light Gray border, and the Technical Shadow on hover. Card headers should use Navy Blue for titles.
*   **Input Fields:** Structured with a 1px border (#DEE2E6). Focus state should use a 2px Navy Blue border. Use Inter for placeholder text.
*   **Icons:** Use a consistent stroke weight (Medium). Primary icons should be Navy Blue, while icons specifically representing environment or renewables should use Sustainability Green.
*   **Section Headers:** Center-aligned for a one-page "Editorial" feel, or left-aligned when paired with a side description. Always preceded by a `label-caps` overline.
*   **Progress Indicators:** Use the Sustainability Green for any "Project Completion" or "Impact" metrics to associate successful outcomes with the brand's green initiatives.