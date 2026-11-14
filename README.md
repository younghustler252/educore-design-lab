# EDUCORE Design Lab

A dedicated workspace for exploring, prototyping, reviewing, and documenting the EDUCORE multi-school management platform UI.

> **Design and prototype workspace only.** The production application remains in [multi-school-portal](https://github.com/younghustler252/multi-school-portal). Do not place production application code, secrets, credentials, database data, or real student/staff records in this repository.

## Purpose

- Build polished, responsive UI prototypes before implementation.
- Validate navigation, page hierarchy, interactions, and mobile behavior.
- Maintain the approved EDUCORE visual language and reusable design decisions.
- Track screen coverage by role and product module.
- Hand off reviewed designs for later implementation in the production Next.js app.

## Prototype technology

Standalone prototypes use **HTML5, CSS3, and vanilla JavaScript**. Inline SVG or Lucide icons may be used. Do not introduce React, Next.js, Tailwind, Bootstrap, or another frontend framework into standalone prototype deliverables unless the project direction is explicitly changed.

## Current approved baseline

The first design baseline contains three working prototype screens:

1. Dashboard
2. Students
3. General Settings

The approved direction is a premium, friendly, professional SaaS interface with a blue primary brand, white and soft-blue surfaces, clear typography, custom SVG iconography, responsive layouts, and visible mobile navigation.

## Repository map

```text
/
├── README.md
├── docs/
│   ├── PRODUCT_CONTEXT.md
│   ├── DESIGN_SYSTEM.md
│   └── SCREEN_ROADMAP.md
├── prototypes/
│   └── v1-approved/
└── assets/
    ├── icons/
    └── images/
```

## Working agreement

- Keep the production repository read-only during the design/prototype phase.
- Use mock/demo data only.
- Never represent a prototype interaction as a real backend integration.
- Preserve the approved blue design direction; iterate on it rather than restarting without a reason.
- Prioritize mobile usability: navigation must remain discoverable and operable.
- Respect reduced-motion preferences.
- Record meaningful design decisions in `docs/`.

## Status

The repository is being initialized. The current prototype baseline and the next refinement pass will be added under `prototypes/`.
