# Codeium (codeium)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
