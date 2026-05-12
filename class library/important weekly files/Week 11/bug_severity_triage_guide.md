# Bug Severity Triage Guide

## Purpose

Use this guide to make bugs visible and prioritize work.

A hidden bug is more dangerous than an honest bug.

## Severity Levels

| Severity | Meaning | Example | Required action |
|---|---|---|---|
| P0 | Final demo cannot work | App will not start, login blocks all use | Stop feature work. Fix or create backup demo plan. |
| P1 | Core feature broken or unreliable | User cannot complete MVP flow | Assign owner and fix before polish work. |
| P2 | Important, but workaround exists | Image upload fails, but text post works | Document workaround and schedule fix. |
| P3 | Polish or nice improvement | Button spacing, better message, minor UI issue | Fix after core flow is stable. |

## Bug Issue Template

```md
# Bug: [short title]

## Severity

P0 / P1 / P2 / P3

## What happened?

-

## Steps to reproduce

1.
2.
3.

## Expected result

-

## Actual result

-

## Evidence

- Screenshot/video:
- Error message/log:
- Related PR/commit:

## Owner

-

## Next step

-
```

## Triage Rules

- P0/P1 bugs beat new features.
- Every bug needs an owner.
- Every bug needs evidence.
- “We know about it” is not enough.
- If it affects the final demo, it must be visible in GitHub.

## Common Mistakes

- Calling everything P3 because the team does not want to deal with it.
- Hiding broken core features.
- Reporting a bug with no steps to reproduce.
- Adding new features while P0/P1 bugs are still open.
- Closing a bug without showing evidence that it was fixed.
