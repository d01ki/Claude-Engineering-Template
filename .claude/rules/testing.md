---
description: Verification and regression-testing guidelines
globs:
  - "src/**/*"
  - "tests/**/*"
---
# Testing rules

- Cover happy path, errors, boundaries, and authorization-sensitive behavior.
- Prefer fast deterministic unit tests with integration tests at real boundaries.
- Mock external services where tests should not cause real side effects.
- For bug fixes, add a regression test when feasible.
- Never change a test solely to hide a genuine failure.
- Record commands and outcomes; distinguish not run from passed.
- CI should execute the same documented checks used locally.
