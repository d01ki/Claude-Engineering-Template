---
name: verify-change
description: Verify a code change with evidence, covering tests, security and regression risks.
disable-model-invocation: true
---
# Verify change

1. Identify changed files, acceptance criteria and affected interfaces.
2. Find actual project verification commands in CLAUDE.md, CI and package manifests.
3. Run relevant format/lint/type/test checks where safe and available. Do not fabricate commands.
4. Inspect the diff for accidental edits, hardcoded secrets, input validation, authorization, and error handling.
5. If checks fail, distinguish pre-existing failures from regressions and propose the smallest fix.
6. Re-run checks after fixes; report exact commands, exit status, evidence and checks not run.
7. Never deploy, merge, or bypass checks to make the report green.
