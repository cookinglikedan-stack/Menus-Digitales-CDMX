---
name: Artisanal Culinary System
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f2'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e1'
  on-surface: '#1a1c1b'
  on-surface-variant: '#424843'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#727972'
  outline-variant: '#c2c8c1'
  surface-tint: '#496551'
  primary: '#496551'
  on-primary: '#ffffff'
  primary-container: '#98b69f'
  on-primary-container: '#2d4836'
  inverse-primary: '#afceb6'
  secondary: '#8e4c31'
  on-secondary: '#ffffff'
  secondary-container: '#ffa988'
  on-secondary-container: '#793c22'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#b0aeae'
  on-tertiary-container: '#424242'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cbead1'
  primary-fixed-dim: '#afceb6'
  on-primary-fixed: '#052011'
  on-primary-fixed-variant: '#324d3a'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#71361c'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
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
  section-padding: 80px
  card-gap: 32px
---

## Brand & Style

This design system embodies an **Artisanal Minimalism** aesthetic, specifically tailored for high-end culinary and hospitality experiences. It prioritizes clarity, elegance, and an "airy" atmosphere that allows food photography and curated content to remain the focal point.

The brand personality is sophisticated yet approachable, evoking the feeling of a modern boutique restaurant. By utilizing a soft, nature-inspired palette and generous whitespace, the UI creates a sense of calm and effortless luxury. The visual language avoids decorative clutter, relying instead on high-quality typography and subtle depth to guide the user.

## Colors

The palette is rooted in an earthy, organic spectrum that suggests freshness and craftsmanship.

*   **Sage Green (Primary):** Used for primary actions and key brand moments. It represents growth and freshness.
*   **Terracotta (Secondary):** An accent color used for secondary interactions, highlights, or links to provide warmth and contrast against the cooler greens.
*   **Charcoal (Tertiary):** The core color for typography and structural elements, providing deep contrast and readability without the harshness of pure black.
*   **Off-White/Bone (Neutral):** The canvas color. It is slightly warm to prevent the UI from feeling clinical, reinforcing the organic brand narrative.

## Typography

The typography uses **Plus Jakarta Sans** for its modern, clean, yet friendly geometric letterforms. The hierarchy is designed to be editorial in nature, with tight tracking on large headings and generous line-heights for body copy to ensure a premium reading experience.

Headlines should be set in Charcoal (#333333) to maintain strong visual weight. Secondary labels and "View" links can utilize the Terracotta or Sage accents to denote interactivity.

## Layout & Spacing

The design system employs a **Fluid-to-Fixed Grid** model. On desktop, content is contained within a 1200px centered wrapper using a 12-column grid. On mobile, the layout shifts to a single column with 20px side margins.

Key spacing principles:
*   **Airy Whitespace:** Large vertical gaps (80px+) between major sections to prevent visual fatigue.
*   **Proximity:** Related elements (like a restaurant title and its description) should be kept close (8-12px), while distinct blocks (like the card and the header above it) require significant clearance (48px+).
*   **Grid Consistency:** All horizontal spacing should be multiples of 8px.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Tonal Layering** and **Subtle Ambient Shadows**.

*   **Primary Surface:** The background is a flat neutral (#F9F9F7).
*   **Floating Elements:** Cards and interactive containers use a pure white background (#FFFFFF) to lift them off the neutral base.
*   **Shadow Profile:** Use a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.04)) only on hovered or active states to signify depth without adding visual weight.
*   **Outlines:** Use low-contrast 1px borders (#E5E5E1) to define boundaries where shadows aren't appropriate, maintaining a crisp, architectural look.

## Shapes

The design system uses a **Rounded** shape language to feel approachable and organic, echoing the soft edges of plates and natural ingredients.

*   **Standard Radius:** 8px for cards and input fields.
*   **Large Radius:** 16px for prominent imagery containers or featured sections.
*   **Pill Shape:** Used exclusively for buttons and tags to distinguish them as primary interactive elements.

## Components

### Buttons
Primary buttons are pill-shaped with a solid Sage Green background and white text. Secondary buttons utilize a ghost style with a Sage Green border and text. Hover states should involve a subtle shift in saturation or a light shadow.

### Cards
Restaurant cards feature a top-aligned image with a 0px radius on the top corners and a 16px radius on the overall container (clip the image). Content below the image should have generous padding (24px) and include a clear, Terracotta-colored text link for "View Menu."

### Input Fields
Forms should be clean with 1px light gray borders and 8px rounded corners. Labels should use the `label-sm` typographic style for a professional, organized look.

### Chips & Tags
Used for cuisine types or price points. These should have a light Sage or Neutral background with dark text, using a full pill radius and small, legible typography.

### Dividers
Horizontal dividers should be 1px thick and use a very faint gray (#EEEEEE) to separate footer content or distinct content groups without breaking the flow of the page.