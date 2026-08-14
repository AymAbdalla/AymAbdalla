<!--
This is the source for github.com/AymAbdalla's profile README.

To publish: create a PUBLIC repo named exactly `AymAbdalla` (same as the username),
put this file in it as `README.md`, and GitHub renders it on the profile page.

Keep it in sync here. This file is the master; the repo is the copy.
Nothing in it signals a job search, by design. Aym is employed.
-->

## Ayman Abdalla

I carry an Enterprise sales quota and build the automation that runs underneath it.

The work is GTM infrastructure: account qualification, live enrichment, buying committee mapping,
benchmark-grounded copy, and sequence tracking, built on Claude and MCP and running across the 18-rep
US sales org I sit in.

**How I build, stated plainly:** I write the spec, direct AI coding agents to implement it, review and
test what comes back, and make the architecture calls. I do not hand-write production code. The 241
passing tests and the backtest harness in these repos exist because I required them, not because a
model volunteered them. If that distinction matters to you, it should, and this is the honest version
of it.

### Repositories

**[gtm-ai-engine](https://github.com/AymAbdalla/gtm-ai-engine)**
A production AI prospecting system, built and run against a live quota rather than a demo dataset.
12 custom agent skills with explicit triggers, precedence rules, and checklist gates. MCP connectors
across 5 data sources with graceful degradation, which stopped being theoretical the day one source
dropped mid-stream and downstream behavior did not change. Self-customizing install: Claude interviews
the adopting rep and rewrites the skills for their territory before install.

**[account-scorer-v2](https://github.com/AymAbdalla/account-scorer-v2)**
A Python scoring engine built to answer one question: does AI scoring actually beat a deterministic
baseline, or does it just feel better? Two-axis FIT plus WIN scoring kept independent and never
averaged, continuous lookalike matching against won customers, a recently-entrenched suppressor with
resurface dates, and a backtest harness that doubles as an eval benchmark. Config-driven product and
territory JSON, so it adapts to another SaaS motion without a rewrite. 241 passing tests across
15 files.

### How I think about this work

- **Spec before code.** Ambiguity in the spec becomes confident nonsense in the output.
- **Guardrails as validation nodes, not wiki pages.** "None found" has to be a valid answer, or the
  system invents. Nothing sends autonomously.
- **Measure against a baseline you can lose to.** I had ten weeks of full Claude access before I built
  anything, and it produced no lift. The gain arrived phase by phase as the system shipped. The
  engineering was the variable, not the tool. A result you cannot attribute is not a result.
- **A failure mode you have not written down is a failure mode you will ship.**

### Background

Business Development Representative at HiBob (Enterprise since July 2026, Mid-Market before that).
Financial analyst work at Casper before that: forecast models, driver analysis, and the habit of
checking a number before repeating it. B.S. Finance, Rutgers Business School, cum laude.

Currently learning SQL, Clay, and cloud deployment properly, in that order.

Reach me at ayman.k.abdalla@gmail.com
