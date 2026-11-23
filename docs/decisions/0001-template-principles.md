# ADR-0001: Stack-agnostic and verification-first template

- Status: Accepted
- Date: 2026-11-23

## Context
The repository should accelerate new Claude Code projects without forcing a framework or pretending a placeholder app has been tested.

## Decision
Provide a short CLAUDE.md, scoped rules, optional specialized agents, opt-in workflow skills, lightweight documentation, and explicit security defaults. Do not ship fake application files, automatic deployment, or unconditional install scripts.

## Consequences
Each generated project must choose its stack, define real verification commands, and configure CI for those commands. This adds a small bootstrap step but avoids false confidence and inappropriate dependencies.
