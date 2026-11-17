# Agents talk. Work ships.

We are the agentic engineering team of a Shopify and D2C agency. We build AI
agents and the platform they run on. A Shopify theme, app or storefront task
goes from a written description to a reviewed pull request. People decide
what ships.

## Factories

Agents that turn a task file into working code and hand it over as a pull
request.

| Project | What it does |
| --- | --- |
| **Theme Factory** | Shopify theme engineering: it reads a task file, a repo and an optional Figma link, then plans, builds, validates and previews the change. |
| **App Factory** | The same flow for Shopify apps and extensions, built against Shopify's live docs and schemas. |
| **WordPress Factory** | A lean port of Theme Factory for WordPress themes. |
| **Theme Factory Plugins** | Knowledge packages that give the factories domain expertise for third-party apps. |

## Platform

| Project | What it does |
| --- | --- |
| **Vision** | The internal home for delivery work: tasks, the Ask Vision assistant, QA runs and integrations. |
| **Code** | An agent framework on Cloudflare Workers and Durable Objects, with a Linux sandbox per conversation. |
| **Identity service** | Single sign-on for every internal service. |
| **MCP gateway** | One Model Context Protocol server that exposes internal services as tools, filtered by role. |
| **Storefront monitoring** | Captures storefront errors and friction, and groups them into issues for Vision. |
| **Uatu** | A Shopify app that audits a store and produces a readiness report. |

## Delivery and operations

| Project | What it does |
| --- | --- |
| **Wong** | GitHub Actions workflows: AI review on every pull request, deploys to dev and staging, and the release pull request every 8 hours. |
| **releases** | One file that sets what each app runs in dev, staging and production. |
| **infrastructure** | Terraform for Cloudflare and GitHub, planned on each pull request and applied on merge. |
| **Heimdall** | The webhook gateway: it verifies and records every external event before anything acts on it. |
| **Hawkeye** | Watches the hand-offs between systems, so a silent failure gets noticed. |

## Growth

| Project | What it does |
| --- | --- |
| **Fury** | An agentic marketing engine: create, distribute, measure. |
| **Nick Fury** | The CRM and coordination layer for account-based campaigns. |
| **Natasha** | A conversational agent that helps D2C brands describe what they need. |

## How we work

**Context, plan, build, validate, ship.** AI is most useful when it has the
right context, tools, domain knowledge and feedback loops, and when people
stay in charge of what reaches production.

- Every change is a pull request, reviewed by Wong and by CI.
- Production changes only through a pull request in `releases`.
- Infrastructure is code: Cloudflare and GitHub are managed with Terraform.
- Everything runs on Cloudflare.
