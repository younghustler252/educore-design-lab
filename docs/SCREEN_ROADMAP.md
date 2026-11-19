# Screen Roadmap

## Phase 1 — Approved baseline

| Screen | Status | Next action |
|---|---|---|
| Dashboard | Approved baseline | Polish responsive behavior and interactions |
| Students | Approved baseline | Fix mobile search parity; complete add-student demo flow |
| General Settings | Approved baseline | Validate tabs, form feedback, and responsive layout |

## Phase 2 — Baseline quality pass

- Verify every screen at mobile, tablet, and desktop widths.
- Ensure mobile navigation is always discoverable.
- Check table-to-card responsive transformations.
- Validate search and filtering on desktop and mobile.
- Complete meaningful local demo interactions for primary actions.
- Add accessible focus, keyboard, and dialog behavior.
- Add reduced-motion support and tasteful transitions.
- Remove or clearly label controls that are not implemented in the prototype.
- Run HTML/CSS/JavaScript checks and manually inspect in a browser.

## Phase 3 — Product and role coverage

Before expanding into more screens:
1. Re-audit the production repository read-only.
2. Confirm actual roles, permissions, routes, and module coverage.
3. Classify each capability as implemented, partial, planned, or unknown.
4. Map workflows to the correct role and tenant context.
5. Prioritize screens based on user value and product dependencies.

Potential areas to map include platform administration, school operations, academics, finance, communication, and access/security. Do not treat this list as a committed implementation order.

## Review gates

A screen is ready for approval when:
- Its purpose and primary user are clear.
- Desktop and mobile layouts are usable.
- Main interactions work within the mock prototype.
- Empty/error/loading/success states are considered where relevant.
- Accessibility basics are addressed.
- It follows the approved EDUCORE visual language.
- It does not imply a backend integration that does not exist.

## Phase 4 — Authentication & onboarding

| Screen / journey | Status | Next action |
|---|---|---|
| Login and account-path selection | First prototype built | Review role labels and login states against production auth |
| School self-registration | First prototype built | Confirm required fields, verification, and approval policy |
| Staff invitation / access request | First prototype built | Align invitation and membership flows with backend |
| Student account activation | First prototype built | Confirm matching fields and guardian-assisted activation |
| Parent / guardian linking | First prototype built | Confirm family-link and relationship verification rules |
| Email OTP verification | First prototype built | Match production delivery, expiry, resend, and rate-limit behavior |
| Forgot / reset password | First prototype built | Match production recovery endpoints and security rules |
| Pending / approved states | First prototype built | Confirm review statuses and notification behavior |

Prototype location: `prototypes/auth-flow/index.html`.

All journeys are mock-only. The prototype does not authenticate users, send email, create school tenants, validate invitations, or approve accounts. Account-path selection is not permission assignment.
