# SkillUp: Flutter Engineer → Full-Stack Engineer (Big Tech)

A 20-week plan to move from 6 years of mobile (Android/Java → Flutter) into full-stack
engineering and clear big-tech interview loops.

## What big-tech full-stack loops actually test

| Round | Weight | Where it's covered |
|---|---|---|
| Coding (DSA), 2–3 rounds | Highest. Usually decides the outcome | [`dsa/`](dsa/README.md) |
| System design (backend/distributed), 1–2 rounds | Decides your level (mid vs senior) | [`system-design/`](system-design/README.md) |
| Domain / frontend round (some companies) | Medium | [`fullstack/`](fullstack/README.md) |
| Behavioral, 1–2 rounds | Medium–high at senior level | [`behavioral/`](behavioral/stories.md) |

Most big-tech companies interview full-stack candidates on the general SWE loop, so DSA and
system design matter most. The full-stack skills and the capstone project give you
credibility for the role switch and something concrete to talk about.

## Stack choices

- **DSA language: Java.** You already know it. It's accepted everywhere and verbose enough that interviewers can follow it.
- **Frontend: TypeScript + React + Next.js.** Dart → TypeScript is a short jump, and React is the industry default.
- **Backend: TypeScript + Node.js (NestJS).** One language across the stack lets you ship faster while learning.
  - *Alternative:* Java + Spring Boot if you target Java-heavy companies (Amazon, banks). Swap it in during weeks 8–13.
- **Data: PostgreSQL + Redis.**
- **Infra: Docker, GitHub Actions, AWS.**

## Weekly rhythm (~22 hrs)

| When | DSA | Full-stack / System design |
|---|---|---|
| Mon–Fri | 1.5 hrs (2 problems) | 1 hr (learn) |
| Sat | 2 hrs (review + 1 hard) | 3 hrs (build capstone) |
| Sun | 2 hrs (timed set) | 3 hrs (build / design practice) |

From week 14 onward, system design replaces part of the full-stack time.

## Phases at a glance

| Weeks | DSA | Full-stack | Later tracks |
|---|---|---|---|
| 1–3 | Arrays, two pointers, sliding window, stack, binary search | Web fundamentals, JavaScript, TypeScript | Behavioral: list story candidates |
| 4–7 | Linked list, trees, tries, heaps | React, Next.js, frontend testing & performance | Capstone frontend |
| 8–13 | Backtracking, graphs, DP, greedy, intervals | Node/NestJS, PostgreSQL, auth, Redis, WebSockets, Docker, CI | Capstone backend |
| 14–17 | Mixed timed sets, company-tagged | AWS deploy, observability | System design + STAR stories |
| 18–20 | Mocks + weak spots | Polish capstone + resume | Mock interviews, applications |

## Folder map

- [`tracker.md`](tracker.md): week-by-week checklist. **Start here every Monday.**
- [`dsa/README.md`](dsa/README.md): problem list by pattern (~130 problems) plus a log template.
- [`fullstack/README.md`](fullstack/README.md): curriculum checklist with resources.
- [`projects/capstone.md`](projects/capstone.md): the portfolio project spec and milestones.
- [`system-design/README.md`](system-design/README.md): concepts, practice prompts, and an answer template.
- [`behavioral/stories.md`](behavioral/stories.md): STAR story bank.

## Rules that make this work

1. **Time-box DSA problems to 30 min.** If you're stuck, read the solution, understand it, and re-solve it 3 days later from scratch.
2. **Learn by pattern, not by count.** After each problem, write one line on *which pattern* it was and *how you'd recognize it*.
3. **Build, don't just watch.** Every full-stack topic should end with code committed in the capstone.
4. **Talk out loud** while solving. Interviews grade communication, not just correct code.
5. **Start mocks earlier than feels comfortable** (week 16–18, not week 20).
