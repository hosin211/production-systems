# Production systems — case studies

The code for these systems is **private**: they are client and employer systems (a university ERP and a power-plant maintenance platform). I cannot open-source them, so this repo documents what I built instead — architecture, scale, and the decisions behind them.

I designed, built and still operate both **alone**, since 2023: my architecture, my code, my pager.

| Case study | Scale | Stack |
|---|---|---|
| [The Two Rivers — university ERP](./two-rivers-erp.md) | 5 colleges · 200+ staff daily | Django 4 · PostgreSQL · HTMX · docxtpl |
| [KMS — plant maintenance platform](./kms-maintenance-platform.md) | 2 power plants · 400+ users | Django 4.2 · PostgreSQL · Docker |
| [Claude Code worktree tooling](./claude-code-worktree-tooling.md) | my daily workflow | Claude Code · git worktrees |

**Day job:** backend engineer at [Apicbase](https://apicbase.com) (multi-tenant food-tech SaaS, 500+ client locations) — event-driven inventory pipeline on Amazon SQS + Celery, per-object authorization across 500+ tenants, CI from 2h to 49min.

**Before that (2021-2023):** Head of the Software Systems & Networks Unit at Al-Hadi University College — built V1 of the college management platform solo (2,000+ students: digital admissions with electronic payments, student self-service portal, document automation), then led the 3-engineer team.

📫 hussinthamer211@gmail.com · [LinkedIn](https://www.linkedin.com/in/hosin211)
