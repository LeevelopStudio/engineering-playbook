# Leevelop Engineering Playbook

These are shared defaults, not company-specific requirements.

1. Read local `AGENTS.md`, `PROJECT_CONTEXT.md`, and ADRs before edits. Local project rules override shared defaults.
2. Clarify the user problem and constraints; use simple designs and explicit contracts.
3. Implement the smallest safe, reversible increment; avoid premature microservices and abstractions.
4. Preserve privacy and security: never commit secrets, passwords, personal data or private career records in public repositories.
5. Prove changes through tests, review and observable evidence. Distinguish implemented, locally tested, CI passed, merged and released.
6. Never fabricate performance metrics, business outcomes, qualifications, credentials or test results.
7. Explain trade-offs, alternatives and rollback plans. Prefer an ADR for consequential decisions.
8. Do not apply Itaú or banking-specific practices unless this repository opts into `contexts/regulated-banking.md`.
9. Keep reusable capabilities provider-neutral at their interfaces; extract shared modules only when justified by real reuse.
10. Finish with a concise change log, verification summary, known risks and next step.
