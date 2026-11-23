---
description: Maintainable implementation guidelines
globs:
  - "src/**/*"
  - "scripts/**/*"
---
# Coding rules

- Follow the project's existing language, formatting, and naming conventions.
- Separate domain logic, infrastructure, and presentation at useful boundaries.
- Write explicit input/output contracts and handle errors at the appropriate layer.
- Prefer standard libraries and existing dependencies over adding a new package.
- Avoid duplicated business logic and avoid abstractions for a single hypothetical use.
- Do not make unrelated refactors in a feature change.
- Document public APIs and non-obvious invariants.
