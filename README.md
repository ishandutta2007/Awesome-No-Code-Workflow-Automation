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



## SaaS/Hosted Platforms



- **[Jira Automation](https://www.atlassian.com/software/jira/guides/automation/overview)**  

  Native automation within Jira; rule-based triggers and actions for issue transitions, field updates, and notifications without external tools.



- **[Zapier](https://zapier.com/)**  

  The market-leading no-code automation platform with **7,000+ integrations** ; trigger-and-action workflows (Zaps) for connecting SaaS tools without engineering effort.



- **[Make](https://www.make.com/)**  

  Visual automation platform with 3,000+ pre-built apps; Scenario Builder with If-Else, Merge, and iterators for complex data transformation. Optimized for rapid deployment with comprehensive pre-built integrations .



- **[Workato](https://www.workato.com/)**  

  Enterprise automation platform with AI-powered recipe building, low-code connectors, and comprehensive security compliance (PCI-DSS, ISO 27001, SOC 2, HIPAA).



- **[Tray.io](https://tray.ai/)**  

  Low-code automation platform with powerful data transformation capabilities; workspaces and custom connector builder for complex enterprise workflows.



- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**  

  Microsoft's automation platform with RPA capabilities, extensive connectors across Microsoft and third-party services, and deep integration with the Power Platform ecosystem.



- **[Relay.app](https://www.relay.app/)**  

  No-code automation platform focused on human-in-the-loop workflows; designed for multi-step processes where human judgment is required at specific points.



- **[Integrately](https://integrately.com/)**  

  No-code automation platform with pre-built automation templates and a focus on simplicity for small businesses.



- **[Pipedream](https://pipedream.com/)**  

  Developer-focused automation platform with SDKs for 3,000+ APIs, source-available component registry, and support for AI agents and workflow builders .



## Open-Source GitHub Projects



### All-in-One Automation Platforms (Zapier/Make Alternatives)



- **[n8n](https://github.com/n8n-io/n8n)**  

  The **most established open-source workflow automation platform** (fair-code license). Combines visual building with custom code; **400+ integrations** and 9,000+ workflow templates ; native AI capabilities for building multi-step agents with model flexibility. **Self-hosting provides maximum flexibility and data sovereignty** . **Best for teams wanting a mature, widely-adopted platform** with a large community and template library—but the fair-code license is not OSI-approved and has restrictions on resale.



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  The **strongest MIT-licensed Zapier alternative** . Features: **500+ integrations** (60% built by the community); **unlimited task execution on paid plans** eliminating usage anxiety; **hybrid approach** supporting both no-code visual building and code customization; self-hostable for data control. Backed by Y Combinator with active development. **Caveats**: fewer integrations than Zapier (500+ vs 7,000+); smaller community and less documentation than n8n; self-hosting requires DevOps expertise . **Best for teams wanting a permissive MIT license** with full commercial use and modification rights—the safest open-source choice if licensing freedom is a priority.



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  A **developer-first open-source workflow engine and platform** (AGPL-3.0) . Build endpoints, workflows, and UIs in **TypeScript, Python, Go, and Bash**; features a built-in web IDE, **visual flow builder** with branches/loops/approvals/retries, **Workflow-as-Code** (express a workflow as a single script), cron scheduling, webhook triggers, and error handling. **Self-hosting**: Helm charts for Kubernetes or Docker Compose . **Best for development teams** wanting a unified interface for APIs, background jobs, and UIs with multi-language support—but it is more developer-oriented than pure no-code platforms.



- **[Kestra](https://github.com/kestra-io/kestra)**  

  An **event-driven, declarative orchestration platform** (Apache 2.0) . Defines workflows in YAML; executes tasks in **any language** (SQL, Python, shell, Go, Java, containers); features **500+ plugins**, event-driven triggers, namespace isolation, RBAC, audit logs, and deployment anywhere. Positioned as an alternative to Zapier, Rundeck, Camunda, and Airflow . **Best for platform teams** supporting diverse users who need language-agnostic orchestration with declarative configuration—but YAML verbosity becomes painful for complex branching logic.



### Code-First Workflow Engines



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open-source **durable execution platform** (MIT) for reliable, long-running workflows . Workflows are code (Go, Java, TypeScript, Python, .NET) with automatic state persistence, replay, and retry—no visual modeling required. Handles distributed transactions, fan-out/fan-in, and human-in-the-loop approvals with timeouts. **Best for complex, long-running business processes** where code-first orchestration and replayable state matter more than visual building—but it is not a no-code tool and requires developer involvement.



### Additional Strong Open-Source Options



- **Pipedream** — Developer-focused automation platform with a source-available component registry . Provides triggers and actions for thousands of integrated apps; developers can use components as no-code building blocks or scaffold code for customization. **Best for developers** wanting API orchestration with source-available components—but the core platform is not fully open source.



**Frameworks for building custom systems**: For a **mature, widely-adopted automation platform**, n8n . For **MIT licensing with unlimited tasks and community integrations**, Activepieces . For **developer-first multi-language workflows with a built-in IDE**, Windmill . For **declarative YAML orchestration with 500+ plugins**, Kestra . For **durable code-first execution**, Temporal . No open-source project matches **Zapier's 7,000+ integration library**—Activepieces (500+), n8n (400+), and Kestra (500+ plugins) lead on data control and cost predictability, but commercial platforms lead on breadth.



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
