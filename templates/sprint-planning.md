# Sprint Planning

Plan one sprint in one page: what you will deliver, who owns what, and
what would make the sprint a success. Fill this in together at the start
of the sprint, not by one person alone.

## Sprint details

| Field | Value |
|---|---|
| **Sprint** | _e.g. Sprint 7_ |
| **Dates** | _YYYY-MM-DD to YYYY-MM-DD_ |
| **Sprint goal** | _One sentence: the outcome this sprint must achieve_ |
| **Product owner** | |
| **Scrum master / Facilitator** | |
| **Team members** | |
| **Capacity** | _e.g. 5 people × 8 days, minus 2 days leave = 38 person-days_ |

## Sprint goal

_Why this sprint, in one or two sentences? A sprint without a goal is just
a list of tasks. If priorities clash mid-sprint, the goal decides what
stays and what drops._

Success criteria for this sprint:

1. _e.g. Checkout flow works end to end on staging_
2. _e.g. All P0 bugs from last sprint closed_
3.

## Backlog for this sprint

| # | Item / User story | Owner | Estimate | Priority | Acceptance criteria |
|---|---|---|---|---|---|
| 1 | _e.g. As a user, I can reset my password_ | | _e.g. 3 points_ | _P0_ | _Reset email arrives within 2 minutes; link works once_ |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

Rules that keep a sprint realistic:

- **Estimate before you commit.** If an item is not estimated, it is not
  ready for the sprint.
- **Leave slack.** Plan for about 80% of capacity. Bugs, reviews and
  unplanned questions will take the rest.
- **One owner per item.** Pairing is fine, but one person is accountable
  for finishing it.
- **Acceptance criteria, not just a title.** "Done" means the criteria
  are met and the work is reviewed, not just coded.

## Carried over from last sprint

| Item | Reason it carried over | New plan |
|---|---|---|
| _e.g. Payment export_ | _Blocked on bank API access_ | _Owner to chase access by day 2, else drop_ |
| | | |

> An item carried over twice is a signal, not bad luck. Split it smaller,
> unblock it properly, or drop it — do not just move it again.

## Risks and dependencies

| Risk / Dependency | Impact if it slips | Owner | Mitigation |
|---|---|---|---|
| _e.g. Design mockups due day 2_ | _Frontend items blocked_ | | _Start with wireframes; confirm by day 1_ |
| | | | |

## Daily rhythm

| Ceremony | When | Length | Purpose |
|---|---|---|---|
| Daily stand-up | _e.g. 09:30_ | 15 min | Blockers, progress, plan for the day |
| Mid-sprint check | _Day 5_ | 30 min | Are we on track for the goal? What needs to change? |
| Sprint review | _Last day_ | 45–60 min | Demo what was delivered to stakeholders |
| Retrospective | _Last day_ | 45 min | What to keep, change, and try next sprint (see `retrospective.md`) |

## Definition of done

An item counts as done only when all of these are true:

- [ ] Acceptance criteria met
- [ ] Code / work reviewed by someone else
- [ ] Tested (and test notes recorded where relevant)
- [ ] Documentation updated if behaviour changed
- [ ] Demoed or shown to the product owner

## End-of-sprint check

| Question | Answer |
|---|---|
| Did we meet the sprint goal? | _Yes / Partially / No — why?_ |
| What was delivered? | |
| What was not finished, and why? | |
| What carries into the next sprint? | |

---

**How to use this template**

1. Before planning, agree the sprint goal and the team's real capacity
   (holidays, support duty, meetings included).
2. Pull items from the backlog in priority order until capacity is full,
   then stop. A sprint that starts overloaded ends in rushed work.
3. Write acceptance criteria for every item during planning, while the
   whole team is in the room.
4. At the mid-sprint check, compare progress against the goal, not just
   the task list — if the goal is at risk, re-scope early and tell
   stakeholders straight away.
5. Close the sprint with a review and a retrospective, and carry the
   lessons into the next sprint's planning.
