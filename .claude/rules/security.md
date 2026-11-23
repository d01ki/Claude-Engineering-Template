# Security rules

- Validate and normalize untrusted inputs at each trust boundary.
- Use parameterized database queries and safe output encoding.
- Use explicit allowlists for outbound requests and file paths where relevant.
- Do not log tokens, credentials, personal data, or sensitive request bodies.
- Require authorization checks on the server for protected operations.
- Make external tool/agent privileges narrow; avoid broad write permission by default.
- Avoid shell interpolation of untrusted values. Do not execute untrusted code.
- For AI systems, treat retrieved text, tool responses, and model outputs as untrusted.
- Seek explicit approval for destructive commands, production changes, and costly APIs.
- Report actual evidence for security claims; mark assumptions as unverified.
