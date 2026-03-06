# Agent Rules

These rules keep collaboration simple, visible, and auditable.

## Core Rules

1. Keep scope extremely small.
2. Do one issue at a time.
3. No unnecessary frameworks, services, or tooling.
4. Everything must be written in plain English.
5. All progress must be visible on GitHub (issue, branch, PR, deployment).

## Implementation Rules

- One issue -> one branch -> one pull request.
- Branch naming: `task/<issue-number>-<short-slug>`.
- PR must reference the issue (`Closes #<issue-number>`).
- PR must include a short test/verification note.
- To trigger Cloudine, add label: `cloudine`.

## Review Rules

- Cloudine implements.
- Codex reviews before merge.
- Merge only when PR is approved or review comments are addressed.

## Deployment Rules

- Deploy only from `main`.
- Deployment should run automatically after merge.
- Do not deploy from feature branches.
