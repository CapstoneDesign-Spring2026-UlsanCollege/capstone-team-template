# Week 11 MVP Verification Guide

## What This Week Is About

Week 11 is the end of Sprint 3: **MVP Verification + Code Ownership**.

This week, your team must prove the MVP is real.

That means:

- the app runs,
- the core flow works or the broken part is clearly documented,
- bugs are visible,
- AI-assisted work is reviewed,
- each student can explain one meaningful part,
- all evidence is linked in GitHub.

## What Is an MVP Flow?

Your MVP flow is the most important thing your app lets a user do.

Examples:

| Project type | Possible MVP flow |
|---|---|
| Study app | user creates a study card and reviews it |
| Booking app | user searches, selects, and creates a booking |
| Marketplace | user posts an item and another user views it |
| Community app | user logs in, creates a post, and sees it in a feed |
| Game app | player starts a game and completes one round |

Keep it simple. One verified flow is better than five half-working features.

## Definition of Verified

A flow is verified when your team can:

1. run it,
2. demo it,
3. explain it,
4. test or manually check it,
5. debug or document problems,
6. link evidence.

## Your Required GitHub Issue

Create or update one Issue:

```txt
Verify MVP core flow
```

Use this structure:

```md
## Core MVP Flow

Our main user can:
1.
2.
3.
4.

## Definition of Done

- [ ] App runs
- [ ] Main flow works
- [ ] Success state is visible
- [ ] One error or empty state is checked
- [ ] Evidence is linked
- [ ] Bugs are listed
- [ ] Owner can explain the code path

## Evidence

- PR:
- Screenshot/video:
- Test/manual check:
- Docs:

## Known Problems

| Problem | Severity | Owner | Next step |
|---|---|---|---|
|  | P0/P1/P2/P3 |  |  |
```

## What Good Looks Like

```md
Our MVP flow is: user signs up, creates a post, and sees it on the dashboard.

Evidence:
- Issue #24: Verify MVP core flow
- PR #31: Fix create-post validation
- Screenshot: dashboard after successful post
- Bug Issue #32: image upload sometimes fails, P2
- Docs: setup guide updated

Ownership:
- Mina can explain the signup route.
- Joon can explain the post form component.
- Ara can explain the database model.
- Dae can explain the dashboard fetch logic.
```

## What Not To Do

Do not submit:

- “It works” with no link.
- screenshots with no explanation.
- new features that are not part of the core flow.
- AI-generated code no one understands.
- a board full of “Done” cards with no evidence.

## Rule

If the core flow is unstable, stop adding features.

Move extra ideas to `Nice Later` and stabilize what matters.
