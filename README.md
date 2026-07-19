# Production systems — case studies

The code for these systems is **private**: they are client and employer systems (a university ERP, a power-plant maintenance platform, a college platform). I cannot open-source them, so this repo documents what I built instead — architecture, scale, and the decisions behind them.

I designed, built and still operate the first three **alone**: my architecture, my code, my pager.

| Case study | Scale | Stack core |
|---|---|---|
| [Two Rivers ERP](./two-rivers-erp.md) | 200+ university staff daily | Django · PostgreSQL · Celery |
| [KMS — plant maintenance platform](./kms-maintenance-platform.md) | 2 power plants · 400+ users | Django · PostgreSQL · Vue |
| [College management platform](./college-platform.md) | 2,000+ students | Django · PostgreSQL |
| [Claude Code worktree tooling](./claude-code-worktree-tooling.md) | my daily workflow | Claude Code · git worktrees |

**Day job:** backend engineer at [Apicbase](https://apicbase.com) (multi-tenant food-tech SaaS, 500+ client locations) — event-driven inventory pipeline on Amazon SQS + Celery, per-object authorization across 500+ tenants, CI from 2h to 49min.

📫 hussinthamer211@gmail.com · [LinkedIn](https://www.linkedin.com/in/hosin211)
