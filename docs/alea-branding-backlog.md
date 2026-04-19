# Alea Branding Backlog (Frontend)

## Priority P0

- Replace app title and shell product labels.
- Replace core logos/icons/favicons in build artifacts.
- Introduce Alea theme token set and default activation.
- Add CI grep checks for forbidden user-facing legacy names.

## Priority P1

- Rework default dashboard landing and navigation groups.
- Add Home vs Business profile entry behavior.
- Align onboarding copy and authentication screens.
- Add legal notices entry point from settings/help.

## Priority P2

- Add screenshot tests for branded shell states.
- Add visual regression tests for dark/light themes.
- Add localization QA pass for high-traffic languages.

## Risk controls

- Keep all branding changes behind dedicated commits by module.
- Avoid broad refactors in same PR as label replacement.
- Rebase frequently on upstream `dev`.
- Validate accessibility contrast before merging.
