# AI Automation Tools Summary

---

Clay is best for the GTM-specific automation. n8n is the fastest-growing, riding open-source + AI tailwinds. Make is the solid mid-tier player, but modest relative to the AI-fueled rocketships.

1. **Make** — strong agency / partner ecosystem, many "Make consultants" and agencies.
2. **n8n** — self-host, can white-label, growing ecosystem of businesses built around it.
3. **Clay** — niche to GTM / sales, vast ecosystem "Claygencies" building workflows. 

Zapier remains a leader in general-purpose no-code automation ($400M ARR). 


## Clay.com

---

 Sales / GTM automation, not general-purpose. Enriches prospect data, automates outbound workflows, and personalizes outreach with AI. A spreadsheet with leads, live data and AI agents.

- **Clients:** sales, growth, and marketing, B2B tech first (OpenAI, Canva, Intercom, Rippling).
- **Hard numbers:** $200M at $3.1B valuation, 10K customers, $1M → $100M ARR in 2 years.

Essentially, a vertical tool for sales. Doesn't automate Slack-to-Jira pipelines or sync CRMs with billing. It finds prospects, enriches data, and helps write personalized outbound at scale.

## n8n.io

---

Open-source workflow automation for tech teams with AI tools and comprehensive scenarios. Essentially an alternative to Zapier, with full control, self-hosting, and code-level customization.

- **Clients:** tech, IT, devs, mid-to-large (Delivery Hero, Decathlon, KPMG, Vodafone, Twitch).
- **Hard numbers:** $250M at $2.5B, ARR < $40M, 3K enterprises, 200K users, 70K GH stars.

The developer's choice. Self-hosting, code-level control, fair-code licensing, and the ability to build genuinely complex multi-agent AI workflows. Trades ease-of-use for power and flexibility.

## Make.com

Visual no-code workflow automation. Stronger than Zapier for complex, branching workflows with loops, conditionals, data transformations, and error handling. + AI Agents and MCP support.

- **Clients** SMBs, agencies, ops teams, technically-inclined users (between Zapier and n8n.
- **Hard numbers:** acquired by Celonis for $100M, $50M ARR, ~650 employees.

The power-user's Zapier alternative. More visual, more flexibility, better data handling, cheaper. Smaller integration library, steeper learning curve. Enterprise process orchestration.

## Ecosystem Perspective

For the automation backbone, **n8n is the strongest**: self-hosted, full infrastructure control, no per-operation payments. Fair-code license allows internal use and client services. Standardized workflow templates become your IP. AI capabilities are the most mature for complex automation.

**Make is a solid alternative** if your clients are less technical and you want them to eventually self-serve inside a visual interface. But you're building on rented land — Celonis owns it, you can't self-host, and your margins get squeezed by per-operation costs as you scale.

Clay is too narrow unless you're specifically building a GTM/outbound agency.

## Implementation

**Phase 1 — Productized service:** pick one repeatable marketing function (e.g., content-to-distribution pipeline or lead qualification and nurturing). Build the workflow in n8n with AI agents doing the heavy lifting via direct API calls. Deliver results, not tools. Charge $2-5K/month.

**Phase 2 — Standardize and templatize:** as you see patterns across clients, harden your workflows into reusable modules. Build a lightweight dashboard (just a Notion or Retool) where clients can see what's happening without touching the automation.

**Phase 3 — Platform:** once you have proven, repeatable workflows that work across 20+ clients, _that's_ your product. You can either keep running it as a managed service (higher margin than agency, lower than SaaS) or build a proper product layer on top.

---
