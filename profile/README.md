<div align="center">

# Onetap Sports

**Technizer Edge's delivery workspace for [Playora](https://playoraindia.com)** — a unified
sports-management platform for institutes, sports directors, and student-athletes.

This org holds the active codebase and delivery docs. The client's own historical org —
frozen as the handover record — is [@One-Tap-Sports](https://github.com/One-Tap-Sports).

</div>

---

## Repositories

| Repo | What it is |
|---|---|
| [`playora-api`](https://github.com/onetap-sports/playora-api) | Backend — NestJS multi-tenant API |
| [`playora-campus`](https://github.com/onetap-sports/playora-campus) | Admin web app — React + Vite, for institute staff and platform admins |
| [`playora-athlete`](https://github.com/onetap-sports/playora-athlete) | Mobile app — Flutter, for students |
| [`docs`](https://github.com/onetap-sports/docs) | **Start here.** Handover documentation, local-setup runbook, and engineering notes |
| [`playora-india-site`](https://github.com/onetap-sports/playora-india-site) | The public marketing site — [playoraindia.com](https://playoraindia.com) |

## Environments

| | Staging | Production |
|---|---|---|
| Host | Render | AWS (Elastic Beanstalk / S3 + CloudFront) |
| Deploy | Automatic on push to `staging` | Manual only — `workflow_dispatch` |
| URL | `staging.playoraindia.com` | `app.playoraindia.com` |

Full branch/deploy workflow, including how `staging` and `main` relate: see
[`docs/notes/branch-workflow-and-deploys.md`](https://github.com/onetap-sports/docs/blob/master/notes/branch-workflow-and-deploys.md).

## New to this project?

1. Read [`docs/README.md`](https://github.com/onetap-sports/docs) for an index of everything.
2. Follow [`docs/runbook/00-overview.md`](https://github.com/onetap-sports/docs/blob/master/runbook/00-overview.md) to get the full stack running locally.
3. Read the branch-workflow notes above before opening your first PR.
