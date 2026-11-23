---
name: root-cause-analysis
description: Investigate recurring bugs and convert verified causes into durable preventive controls.
disable-model-invocation: true
---
# Root cause and correction

1. Capture reproducible symptoms and expected behavior.
2. Form hypotheses and collect evidence; do not assume the first explanation is correct.
3. Identify the root cause and the boundary where it should have been prevented.
4. Fix the defect with a regression test.
5. Prefer enforceable controls (types, validators, lint rules, tests, CI) over a reminder prompt.
6. If a durable instruction is needed, propose a minimal update to the relevant rule or skill.
7. Record evidence, verification results and prevention in docs/agent-engineering/lessons-learned.md.
Do not silently rewrite organization policy or weaken existing checks.
