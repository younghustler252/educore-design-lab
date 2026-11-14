# EDUCORE Design System — Working Baseline

This is the current approved design direction. Treat values as visual guidance until they are extracted and consolidated from the approved prototype.

## Brand and personality

- Product personality: modern, friendly, approachable, and professional.
- Primary direction: blue.
- Overall feel: premium, calm, clear, and trustworthy.
- Avoid generic admin-template styling and unnecessary visual noise.

## Surfaces and color

- Use white as the primary content surface.
- Use soft blue and cool neutral tones for supporting surfaces.
- Use deep, readable text colors and restrained secondary text.
- Use blue for primary actions and active navigation.
- Use green, amber, and red only for meaningful status or feedback states.
- Maintain accessible contrast for text, controls, focus states, and status indicators.

## Layout and navigation

- Mobile-first responsive behavior.
- Navigation must never disappear without an obvious replacement.
- Mobile navigation should provide a clear, accessible drawer or bottom-navigation pattern.
- Keep page hierarchy and primary actions easy to scan.
- Use consistent spacing, borders, radii, and subtle shadows.

## Typography

- Use a clean, highly legible sans-serif.
- Establish clear hierarchy between page title, section title, body, metadata, and helper text.
- Avoid excessively small text, especially in tables and mobile cards.

## Components

Create consistent patterns for:
- App shell, sidebar, top bar, and mobile navigation
- Page headers and primary actions
- Metric/stat cards
- Search, filters, and tables
- Mobile record cards
- Forms, inputs, selects, and validation
- Tabs, dialogs, dropdowns, and toasts
- Empty, loading, success, warning, and error states

## Interaction and accessibility

- Provide visible hover, active, focus, and disabled states.
- Keyboard users must be able to reach and operate interactive controls.
- Dialogs and drawers should support appropriate focus behavior and Escape-to-close.
- Keep ARIA state in sync with toggles, tabs, and disclosure controls.
- Honor `prefers-reduced-motion`.
- Animations should be subtle and purposeful, never required to understand the interface.

## Prototype constraints

- HTML5 + CSS3 + vanilla JavaScript.
- Inline SVG or Lucide icons are acceptable.
- No React, Next.js, Tailwind, Bootstrap, or frontend frameworks in standalone prototype files.
- All data is local mock data; explicitly label simulated behavior where needed.
