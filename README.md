# Ayman Abdalla

**I build GTM systems, AI workflows and full-stack apps with AI-assisted development, and I test them before I ship them.** I come from enterprise tech sales, so I know the revenue workflows I automate from the inside.

**Open to full-time roles:** GTM Engineer, Forward-Deployed Engineer, Solutions Engineer and AI-forward software engineering. New York metro, Eastern time. [LinkedIn](https://linkedin.com/in/aymabd) · [Email](mailto:ayman.k.abdalla@gmail.com)

## Results from the sales seat

- Top 3 of 22 BDRs in FY26 so far, #1 mid-market BDR in Q2 2026, and $7M in sourced pipeline ARR since January 2025.
- Built an AI account-prioritization workflow, shared across my BDR team and used on more than 4,000 accounts.
- Built an AI outbound system that plans 30-50 calls, emails and LinkedIn touches a day on a rolling 10-business-day plan and rebuilds it every night. Nothing goes out unless I approved the person and the copy.
- Built CRM hygiene and data-accuracy workflows, including a send gate that emails only verified addresses.

## Projects

- **[account-scoring-engine](https://github.com/AymAbdalla/account-scoring-engine)**: scores 1,800 Salesforce accounts every weekday, built for a 60-BDR team, with 448 tests. Five readable rules, A-D tiers with every reason shown, territory-mismatch flags and a Needs review queue, written by a dedicated integration user that can't delete accounts, with a dashboard for each BDR and one for their manager. [See the dashboards](https://github.com/AymAbdalla/account-scoring-engine#dashboards).
  _Python · Salesforce REST API and CLI · GitHub Actions_
- **[founder-hq](https://github.com/AymAbdalla/founder-hq)**: a full-stack web app for running several projects at once, with sign-in by email link, code or GitHub, and each account's data walled off by Postgres row-level security. 281 tests (200 unit and integration, 81 browser) passed an independent check. Early build. [See the screens](https://github.com/AymAbdalla/founder-hq#screens).
  _TypeScript · Next.js · Supabase (Postgres) · Vercel_
- **[spend-app](https://github.com/AymAbdalla/spend-app)**: a native iPhone spending journal that logs a purchase from the Action Button in seconds, keeps totals exact to the cent across time zones and daylight saving, and never sends data off the phone. 56 tests; v0.1.0 runs on my iPhone.
  _Swift · SwiftUI · SwiftData · App Intents_
- **[gtm-engine](https://github.com/AymAbdalla/gtm-engine)**: ten GTM engineering skills for AI coding agents, from ICP definition and data quality to signal scoring, plays, outreach drafts, daily plans, CRM sync and funnel review. Works on plain files and never writes to a live system. 365 tests, and 49 of 50 pressure-test cases passed.
  _Python · agent skills · GitHub Actions_
- **[agent-skills](https://github.com/AymAbdalla/agent-skills)**: my build process as three plugins: plan, build, independent check and ship, one phase at a time. 91 tests.
  _Python · agent skills_

## How I build

- Spec and plan first, then small slices, each re-run by a separate checker session (169 checks on the scoring engine so far, 25 of them failed and sent back for fixes).
- Hard rules live in tested code: permissions, send gates, data checks. AI handles language and judgment, and a person approves anything that goes out.
- Every claim says where it's proven: a Salesforce Developer org, sample data, a test copy or my own phone.

## Stack

- **Languages:** Python, TypeScript, Swift, SQL
- **Web and data:** Next.js, React, Supabase (Postgres, row-level security, Auth), Vercel, SQLite, REST APIs
- **GTM and CRM:** Salesforce (REST API, metadata deploys with the Salesforce CLI, reports and dashboards), Outreach, Orum, ZoomInfo, Apollo, LinkedIn Sales Navigator
- **AI and testing:** Claude Code, Codex, Claude agents and MCP connectors, pytest, Vitest, Playwright, XCTest, GitHub Actions
