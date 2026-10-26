# Hi, I'm Ayman

I build AI outbound and CRM data systems from the sales seat. I'm an Enterprise BDR at an HR-tech SaaS company, and I'm moving into GTM engineering.

## Built at work

- **An AI outbound system.** It plans every call, email and LinkedIn touch, 30-50 a day on a rolling 10-business-day plan, and rewrites the next day's plan every night. A nightly agent reads the day's outcomes, updates records, rebuilds the plan, and checks do-not-call lists, local dial windows and a send gate before anything is published. Nothing is sent unless I approved the person and the copy. Working alone while carrying quota, I designed it and built it with Claude coding agents in Python, with Playwright.
- **CRM hygiene and data-accuracy workflows.** Contact-data audits, book cleanup, and a send gate that emails only verified addresses. It's been a large share of my work as a BDR.
- **A Claude-assisted account-prioritization process** that grew out of that data work. It's shared across the BDR team and has been used to process over 4,000 accounts across the AMER BDR org. BDRs in EMEA reach out to see the setup, and I coach them on the AI workflows.

Ranked in the top 4 of about 20 BDRs on average in FY25 and in the top 3 of 22 in FY26 so far; #1 mid-market BDR in Q2 2026.

## Side projects

Designed and built with AI coding agents:

- **[gtm-engine](https://github.com/AymAbdalla/gtm-engine)** (public): ten vendor-neutral GTM engineering skills, packaged as the `aym-gtm` plugin for Claude Code and Codex, from ICP definition, list cleaning and signal scoring to play building, outreach drafts, daily planning, CRM sync and funnel review. 365 automated tests. Runs on plain files and made-up data, and never writes to live systems.
- **[agent-skills](https://github.com/AymAbdalla/agent-skills)** (public): three plugins of agent skills for Claude Code, Codex and the Claude app. A plan, build, check and ship loop that stops after each phase for a go-ahead; explanations and quizzes; tools for building and pressure-testing skills.
- **outbound-engine-demo:** a runnable outbound engine in Python and SQLite with a send gate, account scoring into four plays, sequences as YAML and a nightly plan, plus two pipelines on the public CMS provider register.
- **daybook:** a Python command-line tool that turns a CRM export into a screened, scored daily plan and a CRM fix-ticket workbook. Built spec-first, with separate agents writing the spec and the code.

outbound-engine-demo and daybook are private. I'm glad to walk through the code in an interview.

## How I build

- Start with the workflow and the person doing it, then decide where AI helps.
- Put the rules that must hold in code: permissions, send gates, dial windows, data checks. Use models for language and judgment, and keep a person approving anything that goes out.
- Test before claiming. A prototype, a tested behavior and a real-world result are three different things.

## Stack

Claude (agents, scheduled runs, MCP connectors), Python, pytest, Playwright, SQLite, REST APIs, n8n, Git and GitHub. Salesforce, Outreach, Orum, ZoomInfo, Apollo and LinkedIn Sales Navigator. Learning now: Clay and SQL for data warehouses.

[LinkedIn](https://linkedin.com/in/aymabd) · [Email](mailto:ayman.k.abdalla@gmail.com)
