# Cline (cline)

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
