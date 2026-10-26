# Production systems — case studies

The code for these systems is **private** (client and employer systems), so this repo documents what I built instead — the real architecture, domain models and decisions, written from the codebases themselves.

I designed, built and still operate both **alone**: my architecture, my code, my pager.

| Case study | Scale | Size | Core stack |
|---|---|---|---|
| [**The Two Rivers** — university ERP](./two-rivers-erp.md) | six colleges · 200+ staff daily | 7 apps · 73 models · ~48k LOC | Django 4 · PostgreSQL · HTMX · docxtpl |
| [**KMS** — plant operations platform](./kms-maintenance-platform.md) | 2 power plants · 200+ engineers each | 11 apps · ~90 models · 900 commits | Django 4.2 · PostgreSQL · Docker |
| [Claude Code worktree tooling](./claude-code-worktree-tooling.md) | my daily workflow | — | Claude Code · git worktrees |

Highlights if you only have two minutes:
- Two Rivers: multi-tenant across six colleges of the university, with a self-audit that found and fixed **12 cross-tenant data leaks** in production, locked in with regression tests
- KMS: a **Permit-To-Work safety interlock** (6 permit state machines gating work-order start/completion/printing) and an **OAuth2 MCP server** exposing plant analytics to AI clients

**Day job:** full stack developer at [Apicbase](https://apicbase.com) (multi-tenant food-tech SaaS, 500+ client locations) — event-driven inventory pipeline on Amazon SQS + Celery, per-object authorization across every tenant, CI from 2h to 49min.

**Before that (2021-2023):** Head of the Software Systems & Networks Unit at Al-Hadi University College — built V1 of the college management platform solo (4,000+ new students a year), then led the 3-engineer team.

📫 hussinthamer211@gmail.com · [LinkedIn](https://www.linkedin.com/in/hosin211)
