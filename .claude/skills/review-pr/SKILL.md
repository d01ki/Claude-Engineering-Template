---
name: review-pr
description: Perform evidence-based code review for an existing branch or pull request.
disable-model-invocation: true
---
# Review pull request

1. Identify base and head; obtain the actual diff.
2. Read changed files plus surrounding logic and tests.
3. Check correctness, authorization, injection, secrets, error handling, and regressions.
4. Run relevant read-only checks if feasible, without changing files.
5. Group findings by severity; reference exact file/line and explain impact.
6. Separate confirmed findings, optional improvements, and unverified risks.
7. Summarize tests observed and gaps. Do not automatically merge or publish.
