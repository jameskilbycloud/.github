# jameskilbycloud

Personal cloud, vSphere, and homelab automation work by James Kilby.

Some of these projects previously lived under the
[`jameskilbynet`](https://github.com/jameskilbynet) user and were moved into
this org as the list grew. Anything still on the personal account is unrelated
to the projects here.

## Projects

| Repo | What it does |
|---|---|
| [packer](https://github.com/jameskilbycloud/packer) | Automated Ubuntu LTS golden-image pipeline for vSphere — Packer + GitHub Actions. Six templates: 22.04 / 24.04 / 26.04, server + desktop. |
| [jkcoukblog](https://github.com/jameskilbycloud/jkcoukblog) | WordPress → static site automation. |

## Scope and expectations

These are personal projects, not commercial software. No SLA, no paid
support, no roadmap published outside of each repo's issues. That said,
they're run in anger — the `packer` pipeline rebuilds the homelab's
templates every week, on a real vCenter — so bug reports and PRs are
welcome when they help the next person hitting the same problem.

Each repo has its own `README.md`, `CONTRIBUTING.md`, `SECURITY.md`, and
issue templates. Read those first.

## Contact

- **Security issues:** open a private advisory via the relevant repo's
  Security tab. Each repo has private vulnerability reporting enabled and
  a `SECURITY.md` describing scope.
- **Bugs and feature requests:** use the issue templates on the repo it
  relates to.
- **Anything that doesn't belong on a public tracker:** `james@jameskilby.cloud`.
