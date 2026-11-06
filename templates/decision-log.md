# Decision Log

A decision nobody writes down gets re-argued. A decision log is the
project's memory: what was decided, when, by whom, why, and what it
cost to change later. It is short on purpose. If an entry takes more
than a few lines, the decision probably needs a proper document of
its own, with a link from here.

## How to use this template

- Log a decision on the day it is made, not at the end of the month.
  The reason is obvious then; later it is guesswork.
- One row per decision. Record options that were rejected too, so
  nobody reopens a settled question without new information.
- Review open and reversible decisions at each phase gate. A decision
  marked "reversible" is cheap to revisit; one marked "hard to reverse"
  needs a change request (see `change-request.md`) before it moves.
- Keep the log where the whole team can read it. A private decision
  log is just a diary.

## Log

| # | Date | Decision | Decided by | Context / problem | Options considered | Why this option | Reversible? | Impact if changed | Status |
|---|---|---|---|---|---|---|---|---|---|
| 1 | _YYYY-MM-DD_ | _e.g. Use tool X for time tracking_ | _PM + sponsor_ | _Team was logging hours in three different spreadsheets_ | _Tool X (paid, integrates with payroll); Tool Y (free, manual export); keep spreadsheets_ | _Payroll integration removes a weekly manual step; cost fits the budget_ | _Yes, at month end_ | _One day to migrate data back_ | _Active_ |
| 2 | | | | | | | | | |
| 3 | | | | | | | | | |

## Status values

- **Active** — the decision stands and the project follows it.
- **Superseded** — replaced by a later decision; note the new row
  number in the old row so the chain is traceable.
- **Reversed** — undone, with the reason recorded in the row. Do not
  delete reversed rows: the fact that it was tried, and why it failed,
  is itself useful.
- **Pending** — proposed but not yet approved; nothing should be built
  on a pending decision without saying so.

## Decisions that must be logged

Not every choice belongs here. Log decisions that:

- change scope, budget, timeline, or team structure;
- commit the project to a supplier, tool, or technology;
- set a standard the team must follow (naming, quality bar, process);
- were hard to reach or are likely to be questioned later.

Day-to-day task choices live in meeting notes and tickets, not here.

## Example entries

| # | Date | Decision | Decided by | Why this option |
|---|---|---|---|---|
| 1 | 2026-03-04 | Weekly demo to the sponsor every Friday at 10:00 | PM + sponsor | Problems surfaced while still cheap to fix; a fixed slot stopped demos slipping |
| 2 | 2026-03-11 | Freeze scope in writing at kick-off | Sponsor | Late changes in the last project cost two weeks; every later change now needs a cost and date impact first |

## Review checklist

- [ ] Every decision has a date, a decider, and a reason.
- [ ] Rejected options are recorded, not just the winner.
- [ ] Reversible decisions are marked, so the team knows what can move.
- [ ] Superseded decisions point to the row that replaced them.
- [ ] The log was shared with the team and the sponsor after each update.
