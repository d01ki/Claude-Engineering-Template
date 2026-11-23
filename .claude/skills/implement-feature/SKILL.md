---
name: implement-feature
description: Plan and implement a feature with traceable acceptance criteria and verification.
disable-model-invocation: true
---
# Implement feature

1. Read `CLAUDE.md`, relevant requirements, architecture and existing tests.
2. Restate goal, scope, constraints, and acceptance criteria.
3. For non-trivial work, write a short plan in `docs/plans/`.
4. Inspect similar code and follow established patterns.
5. Implement a minimal vertical slice; preserve backward compatibility unless explicitly changed.
6. Add unit/integration tests covering changed behavior and failure cases.
7. Run applicable verification commands; capture actual results.
8. Review changed files for security, scope, docs, and test coverage.
9. Return a brief summary with evidence and residual risks.

Never invent commands or imply missing tools ran. Ask approval before destructive actions.
