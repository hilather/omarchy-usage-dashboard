# Changelog

## Unreleased

- Show a connected OpenCode Go subscription on the dashboard before its first recorded session.
- Compact provider rows and collapsible detail sections keep the dashboard readable on small screens; collapsed state is remembered.
- Devin session history, plan tier, and account-catalog pricing.
- An All overview tab in the bar widget, plus provider tabs that wrap instead of overflowing.
- Named history accounts with multiple folders, account comparisons, and filters.
- Deduplicate mirrored history and flag conflicting account assignments.
- API-value shares and tokens/value per recorded session.
- Grok Build history, recorded API value, model calls, and weekly quota.
- Gemini CLI, general OpenCode, Pi, and Oh My Pi history, with source-route breakdowns.
- Detect active sources on first use and adapt layouts to the enabled providers.
- Refresh Grok quota after login and request fresh limits on manual Refresh.
- Reopen unmapped dashboard windows and focus the correct instance across workspaces.
- Keep provider colors readable on light and dark backgrounds.

## Initial package

Local metric ledger, provider comparisons, period and session drilldowns, API-value estimates, and optional Omarchy bar integration. Includes an offline pricing snapshot, synthetic demo, and user-owned install/rollback workflow.
