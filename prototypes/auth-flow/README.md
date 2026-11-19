# EDUCORE Authentication & Onboarding Prototype

A standalone, responsive HTML/CSS/Vanilla JavaScript prototype for the EDUCORE sign-in, registration, verification, and onboarding experience.

## Open the prototype

Open `index.html` in a browser or use GitHub's repository file view:
https://github.com/younghustler252/educore-design-lab/blob/main/prototypes/auth-flow/index.html

## Included journeys

- Login with account-path selection: Staff, Student, Parent/Guardian, and restricted Platform Admin.
- School self-registration in three steps: school details, administrator account, and application review.
- Email verification screen with six-digit OTP interaction.
- Staff access request / invitation pathway.
- Student account activation pathway.
- Parent/guardian family-link pathway.
- Forgot password and reset password screens.
- Pending review, verified, and request-status states.
- Responsive desktop split layout and mobile-first single-column layout.

## Demo behavior

- This is a frontend-only prototype. No authentication, email delivery, school lookup, account creation, invitation validation, or approval API is connected.
- Use OTP `123456` on the verification screen.
- Login and access request outcomes are intentionally labelled as demo interactions.
- School registration demonstrates the intended flow; the live product must verify the email and review the school before activating its workspace.

## Product rules represented

- Choosing an account pathway does not grant a role or permissions.
- Staff job roles and permissions are assigned by an authorised school administrator.
- Student activation must match a school-held student record.
- Parent/guardian access requires school-verified relationship or invitation.
- Platform administration remains restricted and is not an open self-registration pathway.

## Next quality pass

Manually inspect desktop, tablet, and mobile breakpoints; improve inline validation and keyboard accessibility; then review the journeys against the live backend's actual authentication and onboarding endpoints before any production implementation.
