# Hi, I'm Ayman

I build and ship working software with AI-assisted development. I came to it from sales, where I'm an Enterprise BDR building tools for my own work. Now I build across GTM systems, AI automation, web apps and iPhone apps, and I'm moving into a full-time builder role.

## Projects

- **[account-scoring-engine](https://github.com/AymAbdalla/account-scoring-engine)**: my flagship. Scores 1,800 sample accounts for 60 fictional BDRs on five readable rules, gives each a tier and every reason behind it, flags accounts outside their BDR's territory, and writes it all into a Salesforce Developer org on a weekday schedule. 448 automated tests.
  _Python, Salesforce REST API and CLI, GitHub Actions_
- **[founder-hq](https://github.com/AymAbdalla/founder-hq)**: a web app for people running several projects at once, with projects, to-dos, reminders and ideas in one place, email and GitHub sign-in, and each account's data kept apart by Postgres row-level security. Early build on test data; 200 unit and integration tests and 81 browser tests passed an independent check.
  _TypeScript, Next.js, Supabase (Postgres), Vercel, Vitest, Playwright_
- **[spend-app](https://github.com/AymAbdalla/spend-app)**: SPEND., a native iPhone spending journal. Press the Action Button, log a purchase, and see today, week and month totals by category and by planned or impulse. Nothing leaves the phone. 56 automated tests; runs on my own iPhone, not the App Store.
  _Swift, SwiftUI, SwiftData, App Intents, XCTest_
- **[gtm-engine](https://github.com/AymAbdalla/gtm-engine)**: ten GTM engineering skills, packaged as a plugin for Claude Code and Codex, that take outbound from ICP definition and list cleaning to plays, message drafts, daily plans, CRM sync and funnel review. Works on plain files and never writes to a live system. 365 automated tests.
  _Python, Markdown agent skills, GitHub Actions_
- **[agent-skills](https://github.com/AymAbdalla/agent-skills)**: my build process as three plugins for Claude Code and Codex. It plans, builds, checks and ships one phase at a time and stops for a go-ahead after each, plus explanations, quizzes and tools for building and testing skills. 91 automated tests.
  _Python, Markdown agent skills_

## From the sales seat

Built for my own job, alone, while carrying quota:

- **An AI outbound system** that plans every call, email and LinkedIn touch on a rolling 10-business-day plan and rewrites the next day's plan every night. Nothing is sent unless I approved the person and the copy.
- **An AI account-prioritization workflow**, shared across the BDR team and used on more than 4,000 accounts.
- **CRM hygiene and data-accuracy workflows**, including a send gate that emails only verified addresses.

Top 3 of 22 BDRs in FY26 so far; #1 mid-market BDR in Q2 2026.

## How I build

- Start with the person and the workflow, then decide where software and AI help.
- Write the spec and the plan first, then build in small slices, each with a check I can see.
- On my recent builds, a separate checker session re-runs each slice and logs what passed and what failed.
- Put the rules that must hold in code (permissions, send gates, data checks), and keep a person approving anything that goes out or can't be undone.
- Say what's proven and what isn't: sample data, a Developer org, a test copy or my own phone, never "production".

## Tools I've built with

- **Languages:** Python, TypeScript, Swift, SQL
- **Web and data:** Next.js, React, Supabase (Postgres, row-level security, Auth), Vercel, SQLite, REST APIs
- **iPhone:** SwiftUI, SwiftData, App Intents
- **GTM systems:** Salesforce (REST API, metadata deployed with the Salesforce CLI, reports and dashboards), Outreach, Orum, ZoomInfo, Apollo, LinkedIn Sales Navigator
- **Testing and shipping:** pytest, Vitest, Playwright, XCTest, GitHub Actions, Git and GitHub
- **AI:** Claude agents, scheduled runs and MCP connectors; Claude Code and Codex as coding agents
- **Learning now:** Clay, SQL for data warehouses

[LinkedIn](https://linkedin.com/in/aymabd) · [Email](mailto:ayman.k.abdalla@gmail.com)
