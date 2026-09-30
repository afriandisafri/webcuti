---
name: Pro-HR Leave System
colors:
  surface: '#fff9eb'
  surface-dim: '#e7db9c'
  surface-bright: '#fff9eb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff4c4'
  surface-container: '#fcefae'
  surface-container-high: '#f6e9a9'
  surface-container-highest: '#f0e3a4'
  on-surface: '#201c00'
  on-surface-variant: '#5c403c'
  inverse-surface: '#373102'
  inverse-on-surface: '#fff2b1'
  outline: '#906f6b'
  outline-variant: '#e5beb9'
  surface-tint: '#bb1718'
  primary: '#97000a'
  on-primary: '#ffffff'
  primary-container: '#be1a1a'
  on-primary-container: '#ffd1cb'
  inverse-primary: '#ffb4aa'
  secondary: '#b51c0c'
  on-secondary: '#ffffff'
  secondary-container: '#d93723'
  on-secondary-container: '#fffbff'
  tertiary: '#725c0d'
  on-tertiary: '#ffffff'
  tertiary-container: '#c5a955'
  on-tertiary-container: '#4e3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#930009'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a7'
  on-secondary-fixed: '#400100'
  on-secondary-fixed-variant: '#920700'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e2c46d'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fff9eb'
  on-background: '#201c00'
  surface-variant: '#f0e3a4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-margin: 24px
  gutter: 16px
  section-gap: 32px
  card-padding: 20px
---

## Brand & Style

This design system is built for enterprise efficiency and administrative trust. The visual language balances the authority of a corporate tool with the accessibility required for daily employee use.

The style is **Corporate / Modern**, leaning on clear structural hierarchies, high-contrast typography, and a "Flat-Plus" aesthetic. It avoids unnecessary flourishes, focusing instead on clarity, speed of task completion, and data integrity. The primary objective is to make complex HR workflows—such as balance tracking and multi-level approvals—feel organized and manageable.

## Colors

The palette uses a dominant red core to signal importance and brand identity, tempered by a warm, paper-like background.

- **Primary Red (#BE1A1A):** Used for key actions (Primary Buttons), active navigation states, and critical branding.
- **Secondary Red (#D0311E):** Used for hover states and secondary interactive elements to provide subtle depth.
- **Light Gold (#F7D87F):** Acts as a functional accent for highlights, "Pending" status indicators, and subtle dividers.
- **Cream Background (#F8EBAB):** The foundational surface color. It reduces eye strain compared to pure white and provides a sophisticated, professional "stationery" feel.
- **Surface Neutrals:** Use low-opacity tints of the Primary Red for subtle background fills in tables or disabled states to maintain color harmony.

## Typography

Inter is the sole typeface for this design system to ensure maximum readability and a systematic feel. 

- **Hierarchy:** Use `Headline-MD` for dashboard card titles and `Headline-LG` for page headers. 
- **Readability:** `Body-MD` is the standard for form labels and table data. 
- **Utility:** `Label-MD` should be used for table headers and small metadata, utilizing its uppercase styling to differentiate from interactive text. 
- **Color:** Use high-contrast dark grays (e.g., `#1A1A1A`) for text on the cream background to ensure WCAG AA accessibility compliance.

## Layout & Spacing

The design system utilizes a **Fixed Grid** on desktop (1200px max-width) and a **Fluid Grid** on mobile devices. 

- **Grid:** 12-column layout for desktop, 4-column for mobile.
- **Rhythm:** An 8px base unit (linear scaling) governs all padding and margins.
- **Density:** High-density data tables are preferred for HR reporting. Use 8px-12px vertical padding for table rows to maximize information density without sacrificing touch targets.
- **Sidebar:** A fixed 260px left-hand navigation is standard for desktop views to allow quick switching between "My Requests," "Team Calendar," and "Reports."

## Elevation & Depth

This design system uses **Tonal Layering** and **Low-Contrast Outlines** rather than heavy shadows to maintain a clean, professional look.

- **Level 0 (Base):** The Cream background (#F8EBAB).
- **Level 1 (Cards):** White surfaces with a 1px border (#E5D8A0) and a very subtle 4px blur shadow (Opacity 5%, Black). This is used for dashboard summaries.
- **Level 2 (Modals/Popovers):** White surfaces with a medium shadow (12px blur, 10% opacity) to provide clear focus.
- **Interactive States:** Buttons lift slightly on hover (shadow increases) while maintaining their solid primary color.

## Shapes

To convey professionalism and structure, the system uses a "Soft" corner radius.

- **Standard Elements:** Buttons, input fields, and checkboxes use a 0.25rem (4px) radius.
- **Containers:** Dashboard cards and large modals use 0.5rem (8px) for a modern but grounded appearance.
- **Status Badges:** Use a fully rounded pill shape (100px) to distinguish them clearly from interactive buttons.

## Components

### Buttons
- **Primary:** Solid #BE1A1A with white text. 
- **Secondary:** Outlined with #BE1A1A, 1px border.
- **Ghost:** No border, primary red text, for less critical actions like "Cancel."

### Status Badges
- **Approved:** Green background (10% opacity of Success Semantic) with solid Green text.
- **Pending:** Light Gold (#F7D87F) background with Dark Brown text.
- **Rejected:** Light Red (10% opacity of Primary) with Primary Red text.

### Data Tables
- Header: Light Gold (#F7D87F) at 30% opacity or a soft gray.
- Rows: White background with a 1px bottom border. Hover state should use the Cream (#F8EBAB) color at 50% opacity.

### Forms & Inputs
- Fields use white backgrounds to pop against the Cream layout.
- Border: 1px #E5D8A0.
- Focus State: 2px solid #BE1A1A.

### Dashboard Cards
- Header: Bold Inter, 16px.
- Value: Large numeric display (32px) for "Days Remaining" or "Pending Approvals."
- Footer: A text link or small button for "View Details."