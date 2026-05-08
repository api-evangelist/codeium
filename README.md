# Codeium (codeium)

Codeium has been rebranded as **Windsurf**. The codeium.com URL now 301-redirects to windsurf.com. The legacy Codeium product offered AI-powered code completion, search, and chat across IDEs (VS Code, JetBrains, Vim, Emacs, etc.). Codeium for Enterprise lives on as the enterprise / self-host SKU within Windsurf, alongside the Windsurf Editor and Plugins.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/codeium/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=codeium-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, Developer Tools, Code Completion, IDE, Windsurf, Rebranded

## APIs
- **Codeium / Windsurf Plugins** — IDE plugins (VS Code, JetBrains, Vim, Emacs, etc.) surfacing autocomplete, chat, command, and Cascade-style agent edits. No public REST API; plugins call hosted inference over a proprietary protocol.
- **Codeium for Enterprise (Windsurf Enterprise)** — Self-hosted enterprise SKU with admin, SSO, analytics, RBAC.

## Plans, Rate Limits, FinOps
- [Plans](plans/codeium-plans-pricing.yml) — Subscriptions live under Windsurf (Free / Light / Pro $20 / Max $200 / Teams $40/user / Enterprise).
- [RateLimits](rate-limits/codeium-rate-limits.yml) — Per-plan daily/weekly usage allowances.
- [FinOps](finops/codeium-finops.yml) — Subscription + API-priced overages.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://windsurf.com/) (codeium.com redirects)
- [Documentation](https://docs.windsurf.com/)

## Notes
- Codeium does not expose a public REST API for application developers. The plugin/extension surfaces are the only consumer of Codeium's hosted inference.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
