# Optional hooks

No executable hooks are installed by default. Hooks can block work or run commands automatically; adding them without reviewing command safety and platform compatibility is risky.

If adding a hook:
1. Choose a narrow event and documented matcher.
2. Prefer read-only, deterministic checks with clear timeout and error behavior.
3. Do not send source, secrets, or telemetry to external endpoints without approval.
4. Test locally and document the failure/override behavior.
5. Keep project-specific lint/test checks in CI as the primary enforcement layer.

Do not assume that prompt rules or hooks replace a sandbox, GitHub branch protection, or server-side authorization.
