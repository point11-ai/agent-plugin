---
name: point11
description: "Run Point11 operations for your organization: Inspector, Discovery, Alpha, Research, and more. Use when the user asks for Point11 or one of its products."
---

# Point11

The `point11` MCP server (https://point11.ai/api/mcp) does what the Point11 dashboard does, as the signed-in person, in the organizations they belong to and within their role.

1. Call `list_accessible_organizations` first, then pass the organization the user means as `organizationId` to every other tool. Ask the user when more than one could fit.
2. Follow each tool's description: it names its arguments, the tool that follows long work, and when the user finishes a step in the dashboard.
3. For anything else, read the guide (https://point11.ai/docs/mcp/overview) or the API reference (https://point11.ai/api/reference).

## Products

- **Inspector** (`inspector_*` tools): Scan a website, benchmark it against competitors, and read every check and result.
- **Discovery** (`discovery_*` tools): Launch Discovery campaigns and read what they find: market, brand, competitor, customer, channel and product reports, maps, rosters and saved reports.
- **Alpha** (`alpha_*` tools): Work with Alpha, your AI marketing assistant: chats, generated files and ads, brand kits, landing pages and their leads, and the apps you connect.
- **Research** (`research_*` tools): Design and launch Research studies, preview interviews, and read conversations and results.
- **Experience** (`experience_*` tools): Run Experience campaigns that use your website and app the way real customers do, and read their journeys and analytics. Manage the test accounts and app builds they use.
- **Business profiles** (`business_*` tools): Manage what Point11 knows about your business: your products (revenue lines in this API), customers, audiences, goals, CRM connections and imports, and the calendar rules your campaigns follow.
- **Sites** (`sites_*` tools): Create and manage hosted sites and their custom domains.
- **Agents** (`agents_*` tools): Create and manage your voice and chat agents, and read their conversations and analytics.
- **Campaigns** (`campaigns_*` tools): See every campaign in one place (calendar, summaries, activity), and pause, resume, archive or delete any of them.
- **Organization and members** (`account_*` tools): Manage your organization, members and invitations, API keys, branding, notifications, AI settings and the audit log.
- **Billing** (`billing_*` tools): See your usage and credits, and manage subscriptions and payment methods.
- **Progress and reports** (`platform_*` tools): Follow long-running work to completion (every `202` answer points here), and read admin reports.
- **Comments** (`collaboration_*` tools): Comment on results, mention teammates, and follow threads.
- **Support** (`support_*` tools): Message Point11 support, or open your in-app Help guide.
- **Reports** (`reports_*` tools): Build reports over Discovery, Experience and Research results: list the datasets each product offers, read and export a report's table, and save, list, archive and delete reports.
