# Executive Assistant

Knowledge base for Pradeep's **Executive Assistant** Claude project.
Connect this repo to the Claude project as knowledge and keep it updated.

## Structure

| Path | What it holds | Update cadence |
|---|---|---|
| **`playbook/`** | **How the assistant works** | |
| `playbook/instructions.md` | Project instructions (paste into Claude project) | When the role changes |
| `playbook/commands.md` | Commands: brief, weekly, prep, draft, log, park | Rarely |
| `playbook/rhythms.md` | Daily brief, weekly review, monthly reset formats | Rarely |
| `playbook/style-guide.md` | Voice, language, drafts, edits, push-back | Rarely |
| `playbook/templates/` | Email, investor update, meeting prep | As needed |
| **`context/`** | **What the assistant knows** | |
| `context/profile.md` | Who Pradeep is, working style, brand standards | Rarely |
| `context/verticals/` | One file per business vertical | Monthly |
| `context/other-ventures.md` | Capital Club, Advisory LLP, Eternal Legends of India | Monthly |
| `context/priorities.md` | This quarter's goals, P1s, deadlines | **Monthly / on change** |
| `context/people.md` | Key people and one-line context | When someone new matters |
| **`logs/`** | **Running records** | |
| `logs/decisions-log.md` | Key decisions | **Every decision** |
| `assets/` | Source material (vertical map notebook page) | — |

## Setup

1. Create a Claude project called **Executive Assistant**.
2. Paste the block in `playbook/instructions.md` into the project instructions.
3. Add this GitHub repo as project knowledge. Sync after every push.
4. Connect Gmail, Google Calendar and Google Drive in Claude.
5. Start each day with `brief`, end each week with `weekly`.

## Rules for this repo

- Facts only in `context/`. Mark unknowns as `OPEN:`.
- Dates in `YYYY-MM-DD`.
- When a priority changes, update `context/priorities.md` **and** log it in `logs/decisions-log.md`.
