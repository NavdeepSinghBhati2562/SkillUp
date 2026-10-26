# SkillUp: Flutter → Full-Stack (Big Tech) — 12 Weeks

Crash plan for Navdeep: move from 6 years of mobile (Android/Java → Flutter) into
full-stack engineering and clear big-tech interview loops in **~3 months**.

> **New session / new Cursor account?** Start with [`AGENTS.md`](AGENTS.md) → [`CONTEXT.md`](CONTEXT.md) → [`PROGRESS.md`](PROGRESS.md).

## Mentor model

Every AI session in this repo should act as **teacher + mentor + companion**:

- Teach clearly (with Flutter/Android analogies when useful).
- Keep durable context and progress in files (not only in chat).
- Maintain **brief** + **short** notes for every topic.
- Log plan changes. Push gently. Protect the 12-week end date.

Rules live in [`.cursor/rules/skillup-mentor.mdc`](.cursor/rules/skillup-mentor.mdc).

## What big-tech full-stack loops test

| Round | Weight | Where |
|---|---|---|
| Coding (DSA), 2–3 rounds | Highest | [`dsa/`](dsa/README.md) |
| System design, 1–2 rounds | Decides level | [`system-design/`](system-design/README.md) |
| Domain / frontend (some) | Medium | [`fullstack/`](fullstack/README.md) |
| Behavioral, 1–2 rounds | Medium–high | [`behavioral/`](behavioral/stories.md) |

## Stack

- **DSA:** Java  
- **Frontend:** TypeScript + React + Next.js  
- **Backend:** TypeScript + NestJS  
- **Data / infra:** PostgreSQL, Redis, Docker, GitHub Actions, AWS  
- **Capstone:** Real-time collaborative task board → [`projects/capstone.md`](projects/capstone.md)

## Weekly rhythm (~20–25 hrs)

| When | DSA | Full-stack / design / build |
|---|---|---|
| Mon–Fri | ~1.5 hrs (2–3 problems) | ~1.5 hrs learn + notes |
| Sat | ~2 hrs review / 1 hard | ~3–4 hrs capstone |
| Sun | ~2 hrs timed set | ~2 hrs notes polish + weekly retro |

## 12-week map

| Weeks | DSA | Full-stack / other |
|---|---|---|
| 1–2 | Arrays, hashing, two pointers, sliding window, stack, binary search | Web + JS + TS crash |
| 3–4 | Linked list, trees, tries, heaps | React + Next.js; capstone UI |
| 5–7 | Backtracking, graphs, 1D/2D DP | NestJS, Postgres, auth; capstone API + auth |
| 8–9 | Greedy, intervals, mixed review | Redis, WS, jobs, Docker, AWS deploy; **system design starts** |
| 10 | Timed mixed sets | System design depth + STAR stories |
| 11–12 | Company-tagged + weak spots | Mocks, polish, applications |

Detail checklist: [`tracker.md`](tracker.md).

## Folder map

| Path | Purpose |
|---|---|
| [`CONTEXT.md`](CONTEXT.md) | Durable learner context (survives account switches) |
| [`PROGRESS.md`](PROGRESS.md) | Done / doing / next + plan change log |
| [`tracker.md`](tracker.md) | Week-by-week checklist |
| [`notes/`](notes/README.md) | Brief (study) + short (cheatsheet) notes |
| [`dsa/`](dsa/README.md) | Problems + log |
| [`fullstack/`](fullstack/README.md) | Curriculum |
| [`projects/capstone.md`](projects/capstone.md) | Capstone milestones |
| [`system-design/`](system-design/README.md) | Design practice |
| [`behavioral/stories.md`](behavioral/stories.md) | STAR bank |

## Rules that make this work

1. **Time-box DSA to 30 min.** Stuck → read solution → re-solve in 3 days. Log it.
2. **Learn by pattern.** After each problem: one line on the pattern + recognition cue.
3. **Build, don't only watch.** Topics end in capstone commits when possible.
4. **Notes every topic:** brief → short.
5. **Update `PROGRESS.md` every session.** Plan changes go in the change log.
6. **Talk out loud** while coding. Interviews grade communication.
7. **Mocks in weeks 11–12** — start even if imperfect.
