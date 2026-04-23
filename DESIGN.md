---
name: Contadora en Línea
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006e2f'
  on-secondary: '#ffffff'
  secondary-container: '#6bff8f'
  on-secondary-container: '#007432'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6bff8f'
  secondary-fixed-dim: '#4ae176'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005321'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style

The design system is anchored in the concept of "Digital Integrity." It balances the sobriety of traditional accounting with the agility of modern SaaS. The brand personality is professional, precise, and empowering, designed to evoke immediate trust in small business owners and freelancers.

The aesthetic follows a **Corporate / Modern** direction with a strong emphasis on **Minimalism**. Every interface element serves a functional purpose, utilizing generous whitespace to reduce cognitive load during complex financial tasks. Visual interest is generated through high-quality typography and strategic "growth" accents rather than decorative flourishes.

**Key visual principles:**
- **Clarity over Ornament:** Avoid gradients or complex patterns that distract from data.
- **Trust through Precision:** Use sharp alignment and consistent mathematical spacing.
- **Micro-interactions:** Subtle transitions (200ms) on hover and state changes to provide a responsive, high-end feel.

## Colors

The palette is strategically weighted to prioritize authority and legibility.

- **Primary (Deep Blue):** Used for core branding, navigation backgrounds, and primary headings to establish a foundation of stability and trust.
- **Secondary (Vibrant Green):** Reserved exclusively for growth-related data, success states, and primary Call-to-Action (CTA) buttons. This creates a psychological link between the service and financial prosperity.
- **Neutral (Slate):** A range of cool grays used for body text, borders, and secondary UI elements to maintain a clean, modern atmosphere.
- **Semantic Colors:** Warning (Amber) and Error (Rose) are used sparingly for alerts, ensuring they stand out against the blue and green foundation.

## Typography

This design system utilizes **Inter** for its entire typographic scale. Inter provides the necessary neutrality for a financial tool while offering exceptional legibility at small sizes (crucial for spreadsheets and data tables).

- **Headlines:** Use tighter letter spacing and bold weights to command attention.
- **Body Text:** Uses a slightly increased line height (1.6) to ensure long-form reports and financial disclosures remain readable.
- **Numerical Data:** For tables and balances, use the `tabular-nums` OpenType feature to ensure digits align vertically, aiding in quick financial comparisons.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop views to maintain a high-trust, "organized" feel. 

- **Grid:** A 12-column grid system with 24px gutters. 
- **Rhythm:** All spacing is based on a 4px baseline unit. 
- **Dashboard Layouts:** Utilize a persistent left-hand navigation (240px) with a fluid content area that caps at 1280px to prevent excessive line lengths in data tables.
- **Section Padding:** Large vertical paddings (80px–120px) are used on marketing pages to emphasize key value propositions and prevent visual clutter.

## Elevation & Depth

To maintain a professional SaaS aesthetic, this design system uses **Ambient Shadows** and **Tonal Layers** rather than heavy borders.

- **Level 0 (Flat):** Used for the main background (White) and inactive input fields.
- **Level 1 (Low):** Subtle borders (1px, #E2E8F0) for cards and containers to define structure without adding weight.
- **Level 2 (Mid):** Used for hover states on interactive cards. A soft, diffused shadow (0px 4px 12px rgba(15, 23, 42, 0.05)).
- **Level 3 (High):** Reserved for modals and dropdown menus. A more pronounced shadow to indicate temporary overlay (0px 12px 24px rgba(15, 23, 42, 0.1)).

Depth is also communicated through color; sidebars use the Primary Deep Blue or a light Slate tint to differentiate the navigation from the workspace.

## Shapes

The shape language is **Soft**. This choice provides a modern, approachable feel while maintaining the structural rigidity expected of a financial service.

- **Standard Radius (4px):** Applied to buttons, input fields, and small UI components.
- **Large Radius (8px):** Applied to cards, containers, and modals.
- **Pill (100px):** Used exclusively for status chips (e.g., "Paid," "Pending") and secondary "Ghost" buttons to create a clear visual distinction from primary action buttons.

## Components

### Buttons
- **Primary:** Solid Vibrant Green background with White text. 4px border radius. Used for the main conversion goal.
- **Secondary:** Solid Deep Blue or White with a Deep Blue border.
- **Tertiary/Ghost:** No background, Deep Blue text, underline on hover.

### Input Fields
- High-contrast labels (Deep Blue) positioned above the field.
- 1px Slate borders that thicken and turn Deep Blue on focus.
- Error states utilize a Rose border and caption text for immediate feedback.

### Cards & Data Displays
- Cards use a White background with a 1px Slate-200 border. 
- Data tables should include subtle row striping (Slate-50) and clear column headers in Deep Blue.

### Feedback & Notifications
- **Success Chips:** Vibrant Green background (10% opacity) with dark green text.
- **Progress Bars:** Use Vibrant Green to indicate completion or positive financial trends.

### Specialized Components
- **Metric Tiles:** Large-format cards displaying a single financial figure (e.g., Total Revenue) with a trend indicator icon (Green arrow up/Red arrow down).
- **Document Uploaders:** Drag-and-drop zones with dashed Slate borders and a centered Green icon.