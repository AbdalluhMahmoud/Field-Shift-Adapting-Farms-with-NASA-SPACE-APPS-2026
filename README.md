# Field Shift: Adapting Farms with NASA Data

Shared project context for our NASA Space Apps 2026 team at Zewail City, Giza, Egypt. This repository is the team's source of truth for planning, decisions, evidence, implementation, and handoffs.

**Stage:** research and repository preparation; no application has been implemented. **Working proposal:** an Arabic-first, evidence-aware crop-rotation planner, provisionally called “Rotation Rehearsal.” The team has not yet accepted a final product or technology stack.

## Start here

1. Read [AGENTS.md](AGENTS.md), the shared instructions for coding agents.
2. Read [current status and open questions](docs/STATUS.md).
3. Read the [challenge brief](docs/challenge/BRIEF.md) and [verification register](docs/challenge/VERIFICATION.md).
4. Read the [product proposal](docs/product/PRD.md), [data plan](docs/data/DATA_PLAN.md), and [architecture proposal](docs/engineering/ARCHITECTURE.md).
5. Follow [CONTRIBUTING.md](CONTRIBUTING.md); select a scoped task before editing.

## Context map

| Location | Purpose |
| --- | --- |
| [docs/README.md](docs/README.md) | Full documentation index and authority rules |
| [docs/reference/](docs/reference/README.md) | Unmodified supplied strategy guide and original README |
| [docs/team/TEAM.md](docs/team/TEAM.md) | Preserved roster and proposed workstreams |
| [docs/team/HANDOFF_TEMPLATE.md](docs/team/HANDOFF_TEMPLATE.md) | Context transfer between people and agents |
| [docs/decisions/](docs/decisions/README.md) | Accepted decisions and proposal template |
| [docs/delivery/PLAN.md](docs/delivery/PLAN.md) | Ordered backlog, validation and submission checklist |
| [docs/AI_USAGE.md](docs/AI_USAGE.md) | AI assistance and review disclosure log |
| [docs/brand/](docs/brand/README.md) | Empty identity and color files awaiting the team's update |

## Important unknowns

The previous README reports November 13–14; the supplied guide reports November 14–15. Neither is independently verified here. Confirm local kickoff, submission and pitch deadlines in **Africa/Cairo** with the organizer. The exact official challenge URL, resource eligibility, rules, and judging rubric remain pending in the verification register. Candidate NASA products are not automatically approved challenge resources.

Existing event images remain in `assets/`; they are reference assets, not an approved project brand. Existing MIT licensing is retained in [LICENSE](LICENSE); third-party data and assets retain their own terms.

## Repository checks

Requires Python 3.10+; no application dependencies are needed yet.

```sh
python3 scripts/check_repository.py
```

This checks local Markdown file links, required context files, and blank brand placeholders. GitHub Actions runs the same check on pushes and pull requests. Build, app test, deployment, and data-processing commands will be documented when the team selects and implements a stack.
