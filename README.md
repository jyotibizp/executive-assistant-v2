# Executive Assistant — Playbook

Context data for Pradeep's **Executive Assistant** Claude project.
The repo is the single source of truth: connect it to the Claude project as knowledge,
keep it updated, and the assistant always works from current context.

## Structure

| File | What it holds | Update cadence |
|---|---|---|
| `00-instructions.md` | Project instructions (paste into Claude project) | When the role changes |
| `01-profile.md` | Who Pradeep is, working style, brand standards | Rarely |
| `02-verticals/` | One file per business vertical — scope, P1s, status | Monthly |
| `03-other-ventures.md` | Capital Club, Advisory LLP, Eternal Legends of India | Monthly |
| `04-priorities.md` | This quarter's goals, P1s, deadlines | **Monthly / on change** |
| `05-people.md` | Key people and one-line context | When someone new matters |
| `06-rhythms.md` | Daily brief, weekly review, monthly reset formats | Rarely |
| `07-templates/` | Email, investor update, meeting prep, follow-up | As needed |
| `08-decisions-log.md` | Running log of key decisions | **Every decision** |
| `assets/` | Source material (vertical map notebook page) | — |

## Setup

1. Create a Claude project called **Executive Assistant**.
2. Paste the block in `00-instructions.md` into the project instructions.
3. Connect this GitHub repo as project knowledge (or upload the files).
4. Connect Gmail, Google Calendar and Google Drive in Claude.
5. Start each day with `brief`, end each week with `weekly`.

## Rules for this repo

- Facts only. No speculation in context files — mark open questions as `OPEN:`.
- Dates in `YYYY-MM-DD`.
- When a priority changes, update `04-priorities.md` **and** log it in `08-decisions-log.md`.
