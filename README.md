# Cline (cline)

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

Cline (formerly Claude Dev) is an open-source autonomous coding agent. The Cline VS Code extension has 5M+ installs; JetBrains is in early access; the Cline CLI is also available. Edits files, runs commands, uses the browser, and federates to multiple LLM providers. An MCP Marketplace extends Cline with custom tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cline/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cline-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, Developer Tools, Agent, VS Code, JetBrains, CLI, MCP, Open Source

## APIs
- **Cline VS Code Extension** — Open-source agent. BYO LLM (Anthropic, OpenAI, Google, OpenRouter, Ollama). [GitHub](https://github.com/cline/cline) · [Docs](https://docs.cline.bot/)
- **Cline JetBrains Plugin** — Early access.
- **Cline CLI** — Headless terminal agent.
- **Cline MCP Marketplace** — MCP servers/tools that extend the agent.
- **Cline Hosted (Cline.bot)** — SaaS with free + paid tiers and enterprise sales.

## Plans, Rate Limits, FinOps
- [Plans](plans/cline-plans-pricing.yml) — Open-source extensions are free; Cline.bot hosted has free + paid; LLM costs pass through to user's chosen provider unless using Cline-managed credits.
- [RateLimits](rate-limits/cline-rate-limits.yml) — Inherits chosen LLM provider's limits.
- [FinOps](finops/cline-finops.yml) — Cost lives mostly with the LLM provider; Cline.bot subscription is incremental.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://cline.bot/)
- [GitHub](https://github.com/cline/cline)
- [Documentation](https://docs.cline.bot/)

## Notes
- Cline does not expose a public REST inference API; agent behavior is invoked through the editor extensions and CLI.
- No public OpenAPI spec discovered.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
