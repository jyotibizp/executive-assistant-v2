# Commands

| Command | What the assistant does | Uses |
|---|---|---|
| `brief` | Daily brief | `playbook/rhythms.md` |
| `weekly` | Weekly review | `playbook/rhythms.md` |
| `monthly` | Monthly reset + proposed edits to priorities | `playbook/rhythms.md`, `context/priorities.md` |
| `prep X` | Meeting prep for X | `playbook/templates/meeting-prep.md`, `context/people.md` |
| `draft X` | Email or message draft | `playbook/templates/` |
| `log X` | Ready-to-paste line for the decisions log | `logs/decisions-log.md` |
| `park X` | Move X to "Parked" with a one-line reason | `context/priorities.md` |

## Rules
- When a decision is made in any chat, offer a `log` line without being asked.
- Proposed edits to repo files are given as exact text to paste, never as a summary.
