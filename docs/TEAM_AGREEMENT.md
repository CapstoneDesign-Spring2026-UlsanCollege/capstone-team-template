<!--
TEAM AGREEMENT (aka team constitution)

How to use:
- Fill this out in Week 1.
- Commit it to the repo.
- Revisit it when there’s friction (conflict, missed work, unclear decisions).
- If you change it, use a PR and explain what changed + why.
-->

# Team Agreement (Constitution)

## 0) Team identity
- Team name:
- Product name:
- Repo link:
- Primary communication channel: (Discord / Kakao / Slack / other)
- Meeting time(s): (day/time)
- Time zone assumptions:

## 1) Our purpose (1–2 sentences)
Why are we building this? What do we want to be proud of?

## 2) Norms (how we work)
### Communication
- We reply to team messages within: **__ hours** (during weekdays)
- If someone is stuck for more than **__ minutes**, they will:
  1) Post a Risk/Blocker Issue, and
  2) Tag the team, and
  3) Ask for help with specifics (error message, screenshot, link)

### Meetings
- Weekly planning happens: (day/time)
- Weekly retro happens: (day/time)
- If you miss a meeting, you must:
  - Read the Sprint Packet, and
  - Post your receipts anyway

### Work habits
- We work through GitHub:
  - Issues for tasks + decisions
  - Branches + PRs for changes
  - `main` stays demoable
- We do not push directly to `main` (unless instructor explicitly allows it).

## 3) Roles (rotate weekly)
Pick who is responsible this week (rotate next week):
- PM (keeps board clean, owns Sprint Packet completeness)
- Scribe (writes demo script + notes, captures decisions)
- Build/Integration owner (keeps main working, resolves merge pain)
- QA/testing owner (ensures “how tested” is real)

## 4) Definition of Done (our default)
A task is **Done** only if:
- It’s merged via PR (not just committed somewhere)
- It has an Issue link (planned work)
- It passes whatever checks we use (manual or CI)
- It doesn’t break the demo
- It updates docs when needed (`docs/PROJECT.md`)

## 5) Evidence & accountability (no drama)
**Rule:** If it isn’t linked, it didn’t happen.

Each student posts weekly receipts (2–3 links) as a comment on the Sprint Packet:
- PR(s) you authored or meaningfully contributed to
- Issue(s) you closed
- Review comment(s) you wrote
- CI run(s) you fixed
- Docs/screenshot evidence in repo

## 6) Decision-making
We use this decision rule:
- **Small decisions:** the owner decides after hearing concerns.
- **Big decisions (scope/architecture/tooling):** write a Decision Issue and agree as a team.

Tie-breaker if we deadlock:
- PM decides **or** we do a quick vote after 10 minutes of debate.

## 7) Conflict handling (procedural)
If conflict happens, we do this:
1) Identify the specific problem (behavior + impact, no mind-reading)
2) Agree on one change for next week
3) Document it in the Sprint Packet retro notes

If it repeats twice:
- Create a “Risk/Blocker” Issue tagged **blocker** and ask instructor for intervention.

## 8) Freeloading / missing work (also procedural)
If someone has no receipts or repeatedly misses tasks:
1) Week 1: private message + clear expectation
2) Week 2: documented in Sprint Packet risk notes + task reassignment
3) Week 3: instructor escalation (links included)

## 9) Tools & standards (what we agree to)
- Branch naming: `feature/<short-name>` or `fix/<short-name>`
- PR size: small enough to review (prefer < 300 lines changed when possible)
- Commit messages: readable (no “asdf”, no “final_final”)
- AI use: allowed only if you can explain the code and you cite what you used (prompt/tool) in the PR notes when relevant

## 10) Amendments (how we change this agreement)
To change this document:
- Open a PR titled: `Update Team Agreement — <summary>`
- Explain: what changed + why
- Team approves (at least 2 approvals recommended)

## Sign-off (Week 1)
- Member 1:
- Member 2:
- Member 3:
- Member 4:
