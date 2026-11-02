# Budget Tracker

Track a project budget on one page: what was planned, what was actually
spent, and where the variance needs a decision. Update it at least once a
week, and always after a purchase or a scope change. A budget that is only
checked at the end of a project is a report, not a control.

## Budget summary

| Field | Value |
|---|---|
| **Project** | |
| **Project manager** | |
| **Budget owner / Approver** | |
| **Currency** | _e.g. EUR_ |
| **Total approved budget** | |
| **Total spent to date** | |
| **Total committed (ordered, not yet invoiced)** | |
| **Remaining budget** | _Approved minus spent minus committed_ |
| **Forecast final cost** | _Spent + committed + expected remaining spend_ |
| **Forecast variance** | _Forecast final cost minus approved budget_ |
| **Last updated** | _YYYY-MM-DD_ |

Rule of thumb: if the forecast variance is more than 10% over budget, or
the remaining budget will not cover the remaining work, escalate it to
the budget owner in the same week. Do not wait for the next status
meeting.

## Budget by category

Plan the budget in categories first, then track spend against each one.
This is where overruns usually hide: the total can look fine while one
category is already overspent.

| Category | Planned | Spent | Committed | Remaining | Forecast | Variance |
|---|---|---|---|---|---|---|
| _e.g. Internal labour_ | | | | | | |
| _e.g. External contractors_ | | | | | | |
| _e.g. Software and licences_ | | | | | | |
| _e.g. Hardware and equipment_ | | | | | | |
| _e.g. Travel_ | | | | | | |
| _e.g. Training_ | | | | | | |
| _e.g. Contingency_ | | | | | | |
| **Total** | | | | | | |

How to fill each column:

- **Planned:** the approved amount for this category, agreed at project
  start. Change it only through the change log below.
- **Spent:** invoiced and paid amounts only.
- **Committed:** ordered or contracted amounts that are not yet invoiced.
  Counting these now is what stops surprise overruns.
- **Remaining:** Planned minus Spent minus Committed.
- **Forecast:** Spent plus Committed plus what the rest of the work in
  this category is realistically expected to cost.
- **Variance:** Forecast minus Planned. Positive means over forecast.

## Spend log

One row per cost, in date order. Small costs add up, so log them all,
not just the large invoices.

| Date | Item / Description | Category | Supplier / Person | Planned | Actual | Variance | Status |
|---|---|---|---|---|---|---|---|
| _YYYY-MM-DD_ | _e.g. Design contractor, sprint 1_ | _External contractors_ | | | | | _Paid / Committed / Planned_ |
| | | | | | | | |
| | | | | | | | |
| | | | | | | | |
| | | | | | | | |

## Budget changes

Never edit the planned figures silently. Every change to the approved
budget gets a row here, with who approved it.

| Date | Change | Amount | New total budget | Reason | Approved by |
|---|---|---|---|---|---|
| _YYYY-MM-DD_ | _e.g. Added contingency for extra testing_ | | | | |
| | | | | | |

## Monthly check

At the end of each month, answer these four questions in writing:

1. **Are we on track?** Compare forecast final cost with the approved
   budget, not just spend to date.
2. **What changed this month?** Largest new costs, and any category
   that moved by more than 10%.
3. **What is at risk?** Uncommitted work with no budget left, supplier
   price changes, or scope that was added without a budget change.
4. **What decision is needed?** Extra budget, scope cut, or reallocation
   between categories, and who needs to approve it.

## Tips

- **Keep contingency visible.** Hold 5 to 10% of the budget as
  contingency in its own category, and release it only for genuine
  unknowns, not for planned work that was under-budgeted.
- **Separate committed from spent.** A project can look under budget
  while thousands are already committed. Always show both.
- **Track labour honestly.** If internal time is charged to the project,
  include it. A budget that ignores labour hides the real cost.
- **Reconcile with finance.** Once a month, compare this tracker with
  the official finance figures and note any difference. The tracker is
  the project view; finance is the record.
