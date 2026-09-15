# Subscription App Due Diligence instructions

AGENTS.md is the canonical instruction file. CLAUDE.md is a relative symlink to it; edit AGENTS.md and preserve the symlink.

## Scope

This repository contains public Markdown checklists and knowledge content for subscription-app acquisitions and sales. The marketplace application, CRM, and Symfony backend are separate repositories; do not add their runtime configuration or implementation here.

## Content and evidence

- Preserve the distinction between revenue, store proceeds, profit, MRR, valuation inputs, and forecast assumptions. Do not turn forecasts or illustrative examples into verified financial claims.
- Support changes to app-store requirements with current official Apple or Google documentation. Preserve canonical links to the live Approck knowledge pages and update the relevant index when adding or moving content.
- Keep private seller and buyer data, credentials, production exports, and transaction evidence out of this public repository.
- Preserve the existing checklist structure and Creative Commons Attribution 4.0 license. Keep new prose concise and actionable.

## Verification and Git

- Inspect the branch, remote, and working tree before editing; preserve unrelated changes.
- For Markdown changes, run `git diff --check`, verify changed relative links and heading anchors, and confirm CLAUDE.md resolves to AGENTS.md.
- This repository currently has no application build or GitHub Actions workflow. Do not report application tests or CI as passing when none ran.
- Re-read the current head and diff before merging or closing a PR; an earlier review may no longer describe its contents.
- Keep commits and pushes separate from the application repositories. Push and merge only within the scope authorized in the current task.
