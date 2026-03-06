# Hello World Flow Lab

This repository is a tiny test bed to validate a full AI-assisted development flow with maximum clarity and minimum scope.

## Scope

- Build one simple web page
- Display exactly: `Hello World`
- Keep the structure clean for future AI work
- Track progress only through:
  - GitHub Issues
  - Branches
  - Pull Requests
  - Deployed URL

## Repository Structure

- `README.md` — project overview
- `AGENT_RULES.md` — operating rules for humans and AI agents
- `CURRENT_TASK.md` — single source of truth for the active task
- `tasks/` — task specs and archived task notes
- `src/` — web page source files
- `infra/` — minimal deployment and workflow notes

## Workflow (high level)

1. Create one issue with a tiny, explicit scope.
2. Cloudine implements using one branch and one PR.
3. Codex reviews the PR.
4. Merge to `main`.
5. Automatic deployment runs after merge.

## Done for this test

- One merged PR exists
- A URL is live
- Opening the URL shows `Hello World`
