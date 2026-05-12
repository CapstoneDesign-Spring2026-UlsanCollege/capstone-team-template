# AI Use + Code Ownership Reminder

## Core Rule

AI-assisted work only counts if your team can:

1. run it,
2. explain it,
3. test it,
4. debug it,
5. link evidence for it.

AI use is allowed.

Poor ownership is the problem.

## Good AI Use

Use AI to:

- explain code,
- inspect a file before editing,
- find likely bug locations,
- suggest small fixes,
- suggest test cases,
- review a PR,
- improve setup docs,
- summarize confusing code,
- suggest refactors for one small area.

## Bad AI Use

Do not ask AI to:

- “fix everything,”
- “make it production ready,”
- add unplanned features,
- rewrite the whole project,
- change unrelated files,
- add dependencies no one understands,
- produce code no one can explain.

## Good Copilot Prompt

```txt
We are working on Issue #18: Fix login error when password is empty.

First, inspect the relevant files and explain the current flow.
Do not edit anything yet.
Then suggest the smallest safe fix.
After that, tell me what tests or manual checks we should run.
```

## Bad Copilot Prompt

```txt
Fix all auth problems and make it better.
```

That is how you summon chaos.

## Required PR AI Use Note

Every PR that used AI should include:

```md
## AI Use Note

- AI tool used:
- What AI helped with:
- What I personally checked or changed:
- How I tested it:
- One part I still do not fully understand:
```

## Week 11 Sprint Packet AI Section

Your team must include:

- AI tools used this week,
- what AI helped with,
- what humans reviewed or changed,
- what code each student can explain,
- what code is still confusing,
- evidence links.

## Final Reminder

AI can help you move faster.

It cannot do the learning for you.
