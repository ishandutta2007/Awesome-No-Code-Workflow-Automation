# Awesome-No-Code-Workflow-Automation

## Top No-Code Workflow Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Visual Workflow Builders, Integration Platforms & Self-Hosted Automation Engines*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **No-Code Workflow Automation**. These tools enable teams to connect applications, automate repetitive tasks, and build multi-step workflows through visual interfaces—without writing code, while optionally extending with custom logic when needed.



**Examples** include Jira Automation, Zapier, Make, Workato, Tray.io, Microsoft Power Automate, n8n, Relay.app, Integrately, and Pipedream (the category leaders).



**Open-source emphasis**: No-Code Workflow Automation is a domain where open-source tooling has **genuinely matured and now offers production-ready alternatives to commercial platforms**. **n8n** is the most established open-source option—a fair-code platform with 400+ integrations, native AI capabilities, and the ability to self-host for full data sovereignty . **Activepieces** is the strongest MIT-licensed alternative, explicitly designed as a Zapier replacement with 500+ integrations, unlimited task execution on paid plans, and a hybrid approach supporting both no-code and custom code . **Windmill** provides a developer-first platform for building workflows, scripts, and UIs in TypeScript, Python, Go, and Bash, with self-hosting via Docker Compose or Kubernetes . **Kestra** offers an event-driven, language-agnostic declarative orchestrator with 500+ plugins and Apache 2.0 licensing . The critical caveat: **no open-source project matches Zapier's 7,000+ integration library**—Activepieces has 500+ , n8n has 400+ , and Kestra has 500+ plugins . Commercial platforms lead on breadth; open-source leads on data control and cost predictability.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global workflow automation and integration platform (iPaaS) market is estimated at **$13.5 billion in 2024–2025 and projected to reach $35+ billion by 2030** (growing at a CAGR of ~20–22%). The sector is **moderately fragmented**: mega-cap cloud incumbents (Microsoft Power Automate) and established leaders (Zapier, Workato) dominate enterprise and broad consumer adoption, but the market features healthy, sustained competition from specialized human-in-the-loop platforms and rapidly expanding self-hosted open-source ecosystems.

## SaaS/Hosted Platforms

| Platform | Company Size / Valuation | Starting Price | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power Automate](https://powerautomate.microsoft.com/)** | ~$3.1T Market Cap (Microsoft) / >$140B ARR Cloud | $15/user/month (Power Automate Premium) | Free with Windows 11/Microsoft 365 (desktop flows only); Cloud automated flows offer a 90-day free trial with full premium connector access | Microsoft's automation platform with RPA capabilities, extensive connectors across Microsoft and third-party services, and deep integration with the Power Platform ecosystem. |
| **[Jira Automation](https://www.atlassian.com/software/jira/guides/automation/overview)** | ~$45B Market Cap (Atlassian) / >$4B ARR | Included in Jira paid tiers (Standard from $7.75/user/month) | Free tier includes up to 10 users and 100 automated rule runs/month across single projects (or 14-day free trial of Jira Cloud Premium) | Native automation within Jira; rule-based triggers and actions for issue transitions, field updates, and notifications without external tools. |
| **[Workato](https://www.workato.com/)** | $5.7B Valuation / >$150M ARR | $10,000/year base platform fee + per-recipe pricing | 30-day guided enterprise free trial with access to connectors and pre-built community recipes | Enterprise automation platform with AI-powered recipe building, low-code connectors, and comprehensive security compliance (PCI-DSS, ISO 27001, SOC 2, HIPAA). |
| **[Zapier](https://zapier.com/)** | $5.0B Valuation / >$250M ARR | $19.99/month (Starter plan, billed annually) | 100 tasks/month, 5 active single-step Zaps, 15-minute update frequency (14-day Professional trial with unlimited steps) | The market-leading no-code automation platform with **7,000+ integrations**; trigger-and-action workflows (Zaps) for connecting SaaS tools without engineering effort. |
| **[Make](https://www.make.com/)** | Celonis subsidiary (Parent valued at $13B, Make ARR >$50M) | $9/month (Core plan, 10,000 operations, billed annually) | 1,000 operations/month, 2 active scenarios, 15-minute minimum interval, 100MB data transfer limit | Visual automation platform with 3,000+ pre-built apps; Scenario Builder with If-Else, Merge, and iterators for complex data transformation. Optimized for rapid deployment with comprehensive pre-built integrations. |
| **[Tray.io](https://tray.ai/)** | $600M+ Valuation / >$30M ARR | $600/month (Pro tier starting tier) | 14-day full platform free trial with access to visual builder, standard connectors, and sandbox test runs | Low-code automation platform with powerful data transformation capabilities; workspaces and custom connector builder for complex enterprise workflows. |
| **[Pipedream](https://pipedream.com/)** | ~$100M Valuation / >$5M ARR | $29/month (Basic plan, billed annually) | 100 daily credits (approx. 3,000 credits/month), unlimited workflows, 3 concurrent executions | Developer-focused automation platform with SDKs for 3,000+ APIs, source-available component registry, and support for AI agents and workflow builders. |
| **[Relay.app](https://www.relay.app/)** | Early-stage VC-backed (~$15M–$30M Valuation) | $9/user/month (Starter tier, billed annually) | 100 runs/month, unlimited workflows, 1-minute run delay, standard human-in-the-loop approvals | No-code automation platform focused on human-in-the-loop workflows; designed for multi-step processes where human judgment is required at specific points. |
| **[Integrately](https://integrately.com/)** | Bootstrapped / >$3M ARR | $19.99/month (Starter plan, billed annually) | 100 tasks/month, 5 active 1-to-1 automations, 15-minute update frequency (14-day trial of paid plan) | No-code automation platform with pre-built automation templates and a focus on simplicity for small businesses. |

## Open-Source GitHub Projects

The following table lists leading open-source workflow automation platforms, self-hosted integration engines, and orchestrators, sorted in descending order by GitHub stargazers:

| Platform | Stars | License | Architecture & Focus | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[n8n](https://github.com/n8n-io/n8n)** | [![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | Fair-code (Sustainable Use) | Visual node-based workflow builder | The **most established open-source workflow automation platform**. Combines visual building with custom JavaScript/Python code; **400+ integrations** and 9,000+ workflow templates; native AI agent workflows with full self-hosting and data sovereignty. |
| **[Huginn](https://github.com/huginn/huginn)** | [![GitHub stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | MIT | Agent-based event monitoring & scrapers | Hackable event-driven automation platform ("build an open-source Yahoo! Pipes or IFTTT"). Runs online agents that monitor web feeds, parse DOM elements, scrape sites, and execute automated actions on custom events. |
| **[Kestra](https://github.com/kestra-io/kestra)** | [![GitHub stars](https://img.shields.io/github/stars/kestra-io/kestra?style=social&color=white)](https://github.com/kestra-io/kestra/stargazers) | Apache 2.0 | Declarative YAML orchestration | An **event-driven, declarative orchestration platform**. Defines workflows in YAML; executes tasks across any runtime (SQL, Python, shell, Go, Java, Docker); features **500+ plugins**, namespace isolation, and real-time execution tracking. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![GitHub stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | MIT | Visual Zapier/Make alternative | The **strongest MIT-licensed Zapier alternative**. Features **500+ integrations** (pieces), unlimited task executions on self-hosted instances, and a hybrid visual builder allowing seamless TypeScript extension. |
| **[Temporal](https://github.com/temporalio/temporal)** | [![GitHub stars](https://img.shields.io/github/stars/temporalio/temporal?style=social&color=white)](https://github.com/temporalio/temporal/stargazers) | MIT | Durable execution workflow engine | Open-source **durable execution platform** for mission-critical, long-running stateful workflows. Workflows are defined in code (Go, Java, TypeScript, Python) with automatic replay, persistence, and distributed state recovery. |
| **[Node-RED](https://github.com/node-red/node-red)** | [![GitHub stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | Apache 2.0 | Low-code flow-based programming | Low-code browser-based visual programming tool for wiring together hardware devices, APIs, and online services. Highly extensible ecosystem with thousands of community nodes (palettes). |
| **[Windmill](https://github.com/windmill-labs/windmill)** | [![GitHub stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers) | AGPL-3.0 | Developer-first workflow & UI engine | Build multi-step workflows, scripts, and internal user interfaces in **TypeScript, Python, Go, and Bash**. Features visual flow composition, Workflow-as-Code, fast execution runtimes, cron scheduling, and webhooks. |
| **[Trigger.dev](https://github.com/triggerdotdev/trigger.dev)** | [![GitHub stars](https://img.shields.io/github/stars/triggerdotdev/trigger.dev?style=social&color=white)](https://github.com/triggerdotdev/trigger.dev/stargazers) | Apache 2.0 | Developer background jobs & workflows | Modern background jobs and orchestration platform built for TypeScript. Handles long-running jobs, real-time logging, retries, step delays, and serverless execution without timeouts. |
| **[Automatisch](https://github.com/automatisch/automatisch)** | [![GitHub stars](https://img.shields.io/github/stars/automatisch/automatisch?style=social&color=white)](https://github.com/automatisch/automatisch/stargazers) | AGPL-3.0 | Pure no-code Zapier alternative | Privacy-focused business automation tool allowing teams to connect software services without writing a single line of code. Designed specifically for full GDPR compliance and on-premise execution. |
| **[Pipedream](https://github.com/pipedreamhq/pipedream)** | [![GitHub stars](https://img.shields.io/github/stars/pipedreamhq/pipedream?style=social&color=white)](https://github.com/pipedreamhq/pipedream/stargazers) | Apache 2.0 (Component registry) | Integration component registry & SDK | Open repository of integration components and actions across thousands of APIs for Pipedream's serverless visual workflow automation platform. |
| **[Inngest](https://github.com/inngest/inngest)** | [![GitHub stars](https://img.shields.io/github/stars/inngest/inngest?style=social&color=white)](https://github.com/inngest/inngest/stargazers) | Apache 2.0 | Event-driven durable step functions | Developer orchestration engine that turns any codebase into durable event-driven workflows with zero infrastructure setup. Supports step-level retries, scheduling, and concurrency management. |

## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- No-code workflow automation platforms handling business data and credentials must comply with applicable privacy regulations and organizational security policies; **self-hosted solutions place full responsibility for security patches, backups, and uptime on the operator**.

- **Open-source no-code automation is mature but licensing varies significantly**—**Activepieces is MIT-licensed** (fully permissive for commercial use) , **n8n uses a fair-code license** (not OSI-approved, with resale restrictions), **Windmill uses AGPL-3.0** (copyleft for network use) , and **Kestra uses Apache 2.0** . Choose based on whether permissive licensing (Activepieces), community size (n8n), developer flexibility (Windmill), or declarative orchestration (Kestra) matters most.

- Verify license terms for commercial use; Activepieces uses MIT , n8n uses fair-code , Windmill uses AGPL-3.0 , and Kestra uses Apache 2.0 .



---



**Made for operations teams, automation builders, and organizations choosing their workflow automation stack.**  

Let's make no-code workflow automation more open, but with clear eyes about the integration library breadth that commercial platforms still hold.
