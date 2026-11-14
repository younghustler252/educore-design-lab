# EDUCORE — Product Context

## Product

EDUCORE is a multi-tenant school-management SaaS intended to support platform-level administration and day-to-day school operations.

This document captures the working context for design. It is not a replacement for a current backend or product requirements audit.

## Design workflow

1. Inspect existing product/backend capabilities read-only.
2. Identify user roles, modules, and current UI coverage.
3. Design and prototype screens independently using HTML, CSS, and vanilla JavaScript.
4. Review and refine the prototype with the product owner.
5. Only after approval, translate the design into the production Next.js application.

## Product areas identified so far

- Platform administration: schools, plans, subscriptions, audit, platform settings, provisioning, impersonation, and platform overview.
- School operations: school profile/settings, branches, staff, students, and guardians.
- Academics: classes, enrolments, academic sessions, attendance, grades, and report cards.
- Finance: fees, invoices, payments, ledger, expenses, budgets, and payroll.
- Communication: notifications, templates, and automation.
- Security and access: authentication, memberships, roles, permissions, and tenant isolation.

These are product areas identified during an earlier read-only review. Their implementation and UI status must be re-verified before designing detailed workflows. Do not assume every listed capability is complete or exposed in the frontend.

## Current prototype scope

The initial approved prototype contains:
- Dashboard
- Students
- General Settings

Use realistic but fictional demo data only. No live API calls or production credentials.
