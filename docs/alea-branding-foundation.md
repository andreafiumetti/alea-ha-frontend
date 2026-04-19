# Alea Branding Foundation (Frontend)

## Objective

Establish a safe and repeatable path to transform the upstream frontend into a fully white-label Alea Connect experience for home and enterprise users.

## Branding scope

- Product identity: app name, logos, icons, favicon, splash assets.
- Visual language: color tokens, typography, spacing, elevation.
- Copy and labels: product strings and user-facing references.
- Navigation: home and enterprise-first information architecture.
- Legal surfaces: open-source notices and attribution screens.

## Implementation tracks

### Track 1 - Design tokens

- Introduce Alea token profile in the theme layer.
- Keep upstream token contracts intact to reduce merge friction.
- Add light/dark palettes with accessibility checks.

### Track 2 - Entry points and shell

- Replace product references in app shell and startup surfaces.
- Update logos and favicons across desktop/PWA surfaces.
- Prepare role-based defaults for home and business editions.

### Track 3 - Copy migration

- Inventory and map product-facing strings.
- Replace references through controlled passes by module.
- Add regression checks for untranslated or legacy labels.

### Track 4 - Distribution hardening

- Integrate build profile for Alea distribution artifacts.
- Add CI checks to avoid reintroducing legacy product naming.
- Keep legal notices separate from user-facing branding.

## Non-goals for this branch

- No behavioral changes to automation/entity features.
- No API contract changes.
- No enterprise auth features yet (tracked in backend milestones).

## Definition of done for foundation milestone

- Shared naming conventions approved.
- Token strategy documented.
- String migration backlog created.
- CI guardrails identified for next PR.
