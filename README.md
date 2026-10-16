# Leevelop Engineering Playbook

A reusable, tool-neutral engineering operating system for Leevelop Studio projects.

## Principles
Read [AGENTS.md](AGENTS.md). Individual repositories own their product decisions and `PROJECT_CONTEXT.md`; the playbook supplies shared standards, workflows, and optional specialist agents. Banking-specific guidance is opt-in, never universal.

## Getting started
1. Copy [templates/AGENTS.md](templates/AGENTS.md) and [templates/PROJECT_CONTEXT.md](templates/PROJECT_CONTEXT.md) to a project.
2. Pin a tagged release or commit of this playbook.
3. Read project context and invoke [workflows/implement-feature.md](workflows/implement-feature.md).
4. Select only relevant specialists from [agents/](agents/).
5. Validate the result and report actual evidence, including remaining risks.

## Boundaries
- `career-os`: public code; `career`: private career data.
- `family-finance-platform`: private financial data.
- `leevelop-auth`: reusable identity candidate, not an authorization model for every business.
- Product capabilities (auth/payments/shipping) are separate from AI engineering agents.
- Do not publish confidential employer documents or secrets.

## Historical material
The original Itaú-centered agent ZIP should be retained privately as a reference, not interpreted as generic defaults.
