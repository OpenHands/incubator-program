# Project Lifecycle

This document describes the requirements for each project class and the process for moving between them.

## Requirements by Class

| Requirement | Sandbox | Incubator | Graduated |
|---|---|---|---|
| `LICENSE` | ✅ | ✅ | ✅ |
| `README` | ✅ | ✅ | ✅ |
| Status badge in README | ✅ | ✅ | — |
| Tests | — | ✅ | ✅ |
| Architecture review | — | ✅ | ✅ |
| Documentation | — | ✅ | ✅ |
| Slack `#proj-` channel | — | ✅ | ✅ |
| SLO | — | — | ✅ |

## Requesting a Class Change

All class changes require Tech Council approval. To request a change:

1. Ensure your project meets all requirements for the target class (see table above).
2. Open an issue in this repo using the [Class Change Request](../../../issues/new) template.
3. Tech Council will review and respond within two weeks.

Tech council must also approve any change between open and closed source, at any stage.

## Sample Lifecycle

The following illustrates a typical project journey:

1. **Robert** creates a kanban-style interface for the agent-server. He puts it in a new private repo at `OpenHands/kanban`.
2. Robert wants to socialize it with the community. He requests Tech Council approval to open source it as a **Sandbox** project. Tech Council asks him to add a `LICENSE` and status badge to the README.
3. A small number of community members start using it regularly.
4. Robert requests **Incubator** status. Tech Council rejects based on code quality concerns.
5. Robert spends ~1 day improving the project: runs a `codereview-roasted` architecture review, fixes glaring issues, adds comprehensive tests, and adds a `docs/` folder.
6. Robert reapplies. Tech Council approves.
7. Months later, the kanban view is incorporated into the main OpenHands UI.
8. Tech Council recognizes the production usage and moves the project to **Graduated**.

## SLO (Graduated Projects)

Graduated projects must maintain the following SLO:

- **Critical bugs**: acknowledged within 2 business days, resolved within 1 week.
- **Security issues**: acknowledged within 1 business day, resolved within 72 hours.

_SLO details may be refined by Tech Council over time._