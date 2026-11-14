# ⚡ Agentic Anatta

### Agents talk. Work ships.

We are the agentic engineering team at [Anatta](https://anatta.io), the Shopify and D2C agency.
We build AI agents and the platform they run on, so that Shopify themes, apps and storefronts
go from a written task to a reviewed pull request, with people deciding what ships.

[agenticanatta.com](https://agenticanatta.com)

---

## 🏭 The factories

Agents that turn a task description into working code, then hand it over as a pull request.

| | |
| --- | --- |
| **Theme Factory** | Shopify theme engineering: context, plan, build, validate and preview, from a task file, a repo and an optional Figma link. |
| **App Factory** | The same idea for Shopify apps and extensions, built against Shopify's live docs and schemas. |
| **WordPress Factory** | A lean port of Theme Factory for WordPress themes. |
| **Plugins** | Knowledge packages that give the factories domain expertise without growing their core. |

## 🧠 The platform

| | |
| --- | --- |
| **Vision** | Our internal home for agent work: tasks, the "Ask Vision" assistant, factory runs, previews and storefront monitoring. |
| **Code** | An agent framework on Cloudflare Workers and Durable Objects, with a sandboxed Linux workspace per conversation. |
| **Anatta ID** | Single sign-on for every internal service. |
| **MCP gateway** | One Model Context Protocol server that exposes our services as tools, filtered by role. |

## 🛰️ Keeping it honest

| | |
| --- | --- |
| **Wong** | AI review on every pull request: inline findings, a required check, and auto-merge only for clean agent work. |
| **Heimdall** | The webhook gateway: every external event is verified and recorded before anything acts on it. |
| **Hawkeye** | Watches the hand-offs between systems, so a silent failure gets noticed. |

## 📣 Growth

| | |
| --- | --- |
| **Fury** | An agentic marketing engine: create, distribute, measure. |
| **Nick Fury** | The CRM and coordination brain for account-based campaigns. |
| **Natasha** | A conversational agent that helps D2C brands describe what they need. |

---

## 🛠️ How we work

**Context → Plan → Build → Validate → Ship.** AI is most useful when it has the right context, tools,
domain knowledge and feedback loops, and when people stay in charge of what reaches production.

- Every change is a pull request, reviewed by Wong and by CI.
- Infrastructure is code: Cloudflare and GitHub are managed with Terraform.
- Everything runs on Cloudflare's edge.

---

_Built by the Agentic Anatta team at Anatta._
