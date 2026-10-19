# Risk Register

Track risks openly from day one. Review this table in every status meeting — a risk register nobody looks at is decoration.

**Scoring:** Probability × Impact, each on a 1–5 scale. Score = P × I (max 25). Anything scoring **12+** needs a mitigation owner and a review date.

## Template

| # | Risk | Probability (1–5) | Impact (1–5) | Score | Mitigation | Owner | Review date |
|---|---|---|---|---|---|---|---|
| 1 | [Risk description] | [1–5] | [1–5] | [=P×I] | [What we do about it] | [Name] | [YYYY-MM-DD] |
| 2 | | | | | | | |

## Example rows

| # | Risk | Probability (1–5) | Impact (1–5) | Score | Mitigation | Owner | Review date |
|---|---|---|---|---|---|---|---|
| 1 | Key developer unavailable during launch week | 3 | 4 | 12 | Cross-train a backup developer by [date]; freeze holidays that week | Project Lead | 2026-11-01 |
| 2 | Client feedback rounds take longer than planned | 4 | 3 | 12 | Agree a 3-working-day feedback SLA in the charter; escalate after 5 days | Project Lead | 2026-10-25 |
| 3 | Third-party API changes break integration | 2 | 5 | 10 | Pin API version; add contract tests in CI | Developer | 2026-11-15 |

## When a risk materializes

1. Move it to the issue/blocker list in the status report.
2. Note the date it occurred and what it cost (time, budget).
3. After resolution, record the lesson — that is how the next project's register gets better.
