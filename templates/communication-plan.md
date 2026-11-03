# Communication Plan

Who gets told what, when, and how — agreed up front, so nobody finds
out about a delay from a hallway conversation. A project that
communicates badly looks disorganised even when the work itself is
on track, and a project that communicates well can survive bad news.

## Project details

| Field | Value |
|---|---|
| **Project** | |
| **Project manager** | |
| **Sponsor** | |
| **Start / end date** | |
| **Version / last updated** | _Update this plan whenever the audience or the cadence changes_ |

## Communication principles

Agree these with the sponsor before the project starts, and hold
yourself to them:

- **No surprises.** Bad news goes to the sponsor first, before it
  reaches anyone else.
- **One source of truth.** Status lives in one document (see
  `status-report.md` in this repo), not in five different chats.
- **Right level, right people.** Executives get decisions and impact;
  the team gets detail. Sending everyone everything helps no one.
- **Written beats verbal for decisions.** A decision made in a
  meeting is not real until it is written down, with an owner.
- **Silence is also a message.** If there is nothing new, say so on
  schedule — a missed update reads as a problem.

## Stakeholder communication matrix

List every group that needs information, not just the people you
like talking to. Use `stakeholder-map.md` in this repo to identify
the groups first, then fill in this table.

| # | Audience / stakeholder | What they need to know | Channel | Frequency | Owner |
|---|---|---|---|---|---|
| 1 | _e.g. Sponsor_ | _Decisions needed, risks, budget status_ | _Steering meeting + status report_ | _Monthly_ | _PM_ |
| 2 | _e.g. Project team_ | _Tasks, blockers, priorities_ | _Daily stand-up + task board_ | _Daily_ | _PM / Lead_ |
| 3 | _e.g. Client / customer_ | _Progress, milestones, change requests_ | _Status email + demo_ | _Bi-weekly_ | _PM_ |
| 4 | _e.g. End users_ | _What changes for them, and when_ | _Announcement + training_ | _At milestones_ | |
| 5 | | | | | |
| 6 | | | | | |

Rules for filling this in:

- **One owner per row.** If nobody owns an update, it will not happen.
- **Frequency is a promise.** Only commit to a rhythm you can keep;
  a monthly report that arrives every month beats a weekly report
  that stops after three weeks.
- **Separate "inform" from "decide".** If a meeting needs a decision,
  say so in the invite, with the options and your recommendation.

## Regular communications

### Status report

- **Audience:** _sponsor, steering group_
- **Frequency:** _e.g. every Friday, or monthly_
- **Format:** `status-report.md` in this repo — progress, RAG status,
  risks, decisions needed.
- **Sent by:** _PM_
- **Rule:** Send it on time even when there is no progress. "No
  change this week" is a valid update; a missing report is not.

### Team stand-up

- **Audience:** project team
- **Frequency:** _daily, 15 minutes maximum_
- **Format:** What did you finish, what are you doing today, what
  is blocking you. No problem-solving in the stand-up — park it
  and solve it afterwards with only the people involved.
- **Rule:** If a blocker is raised, the PM owns getting it unblocked
  the same day, or escalating it (see below).

### Steering / sponsor meeting

- **Audience:** sponsor, key stakeholders
- **Frequency:** _e.g. monthly, or at phase gates_
- **Agenda:** decisions needed, risks and issues, budget, next
  milestones. Send the agenda and the status report in advance so
  the meeting is for decisions, not for reading slides.
- **Output:** decisions and actions recorded in `meeting-notes.md`.

### Milestone and release communications

| Event | Audience | Channel | Timing |
|---|---|---|---|
| _e.g. Milestone reached_ | _Client, team, sponsor_ | _Email + demo_ | _Within 1 working day_ |
| _e.g. Go-live / release_ | _End users, support team_ | _Announcement + release notes_ | _At least 1 week before, then on the day_ |
| _e.g. Delay to a milestone_ | _Sponsor first, then client_ | _Call, then written confirmation_ | _As soon as it is known_ |

## Channels — and what each one is for

Agree this once, and stop the "which channel do I use?" confusion:

| Channel | Use it for | Do NOT use it for |
|---|---|---|
| _e.g. Email_ | _Formal updates, decisions, anything that needs a record_ | _Urgent blockers_ |
| _e.g. Chat (Teams / Slack)_ | _Quick questions, daily coordination_ | _Decisions — move them to email or the meeting notes_ |
| _e.g. Task board_ | _Task status, ownership, deadlines_ | _Discussions that need a decision_ |
| _e.g. Shared documents_ | _The single source of truth for plans and reports_ | _Chasing people — use chat or a call_ |

## Escalation path

When a problem cannot be solved at team level, it goes up — fast,
and with a proposed solution, not just a complaint.

| Level | Who | When to escalate | Response time |
|---|---|---|---|
| 1 | _Project manager_ | _Blocker affecting one task_ | _Same day_ |
| 2 | _Sponsor_ | _Blocker affecting a milestone, budget, or scope_ | _Within 2 working days_ |
| 3 | _Steering group / client decision-maker_ | _Decision needed on scope, budget, or timeline_ | _At next steering meeting, or sooner if urgent_ |

Escalation template — use this wording, in a call first and then
in writing:

> **Issue:** _what is blocked, in one sentence_
> **Impact:** _what slips, and by how much, if it is not resolved_
> **Options:** _A / B, with your recommendation_
> **Decision needed by:** _date — after that, the impact grows_

## Change and crisis communication

- **Scope or timeline changes:** Sponsor first, then the client,
  then the team, then wider audiences — in that order, and in
  writing. Never let the team hear about a change from the client.
- **Incidents or outages:** One named communicator, one status
  message, updated at a fixed interval (e.g. every 30 minutes)
  until resolved — even if the update is "still investigating".
- **Confidential information:** Mark it, limit the audience, and
  never share it in a general channel. If in doubt, ask the sponsor
  before sending.

## Language and accessibility

- Write for the reader, not for yourself: short sentences, no
  jargon without explanation, numbers with context ("2 weeks late
  against the 1 June milestone", not just "delayed").
- If stakeholders work in more than one language, agree which
  language is used for formal documents and which for day-to-day
  chat, and keep the formal record in one language only.
- Agree response-time expectations (e.g. acknowledge within one
  working day) so a slow reply is not mistaken for disagreement.

## Reviewing this plan

| Field | Value |
|---|---|
| **Review frequency** | _At each phase gate, and whenever the audience changes_ |
| **Last reviewed** | |
| **Changes made** | _What changed, and why — so the plan stays a living document_ |

---

**How to use this template**

1. Fill in the stakeholder matrix with the sponsor, before the
   project kick-off. An empty matrix means you have not thought
   about who needs to hear from you.
2. Agree the channels and the cadence in the kick-off meeting, and
   write them down here — verbal agreements about communication
   are forgotten within a week.
3. Use it together with `status-report.md` (the actual updates),
   `meeting-notes.md` (decisions), and `stakeholder-map.md`
   (who matters and why). This plan says how you communicate;
   those documents are the communication itself.
4. Review it at every phase gate. A plan written at kick-off that
   nobody revisits will be wrong by the middle of the project.
