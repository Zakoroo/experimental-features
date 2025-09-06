# Contributing

## Workflow
1. Create a short-lived feature branch from `main`.
2. Commit using Conventional Commits (e.g., `feat: add X`).
3. Open a PR and fill the template. Tag a reviewer in #reviews.
4. Address review comments; keep the PR small if possible.

## Review SLA
Aim for review within 24h (weekdays). If you need more time, acknowledge with an ETA in the PR thread.

## Approvals
- 1 reviewer for routine code.
- 2 reviewers for risky areas (security, DB schema, public APIs).
- The author cannot self-approve. CODEOWNERS may enforce extra reviewers.

## Definition of Done
- CI green (formatter/linter/tests/static analysis once stack is set)
- Approved PR
- Docs updated (inline + README/wiki as needed)
- Issue linked (use “Closes #123”)
- No secrets/keys in repo; use env/secret manager

## Style & Tooling
- Auto-formatter + linter enforced via CI once the stack is selected.
- EditorConfig and line ending normalization are already set in this repo.

## Hotfixes
Urgent fixes may fast-track with pair review and a retro PR documenting follow-ups.

