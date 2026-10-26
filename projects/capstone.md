# Capstone: Real-Time Collaborative Task Board

A mini Trello/Linear built across **Weeks 3–11** of the 12-week plan. Proof of full-stack
ability on your resume, and the story you'll tell in interviews
("tell me about something you built", "how would you scale it?").

## Why this project

It forces the skills interviewers probe: auth, relational data, caching, realtime,
background jobs, containers, CI, and cloud deploy. It also gives you a real system to reason
about in system design rounds.

## Features

- Sign up / log in (email + password, plus Google OAuth)
- Workspaces → boards → columns → cards; invite members with roles (owner, editor, viewer)
- Drag-and-drop cards; changes appear live for everyone on the board
- Comments and @mentions → email/in-app notifications (background job)
- Activity history per card
- Search cards across a workspace

## Stack

Next.js (App Router) + TypeScript + Tailwind · NestJS · PostgreSQL + Prisma · Redis · BullMQ ·
WebSockets (Socket.IO) · Docker Compose · GitHub Actions · AWS (ECS Fargate or EC2, RDS, S3)

## Milestones (12-week schedule)

| # | Week | Milestone | Done |
|---|---|---|---|
| 1 | 3 | Monorepo (`apps/web`, `apps/api`), Next.js skeleton with routing and layout | [ ] |
| 2 | 4 | Full UI on mocked data: boards, columns, drag-and-drop cards | [ ] |
| 3 | 6 | NestJS CRUD API + Postgres schema + migrations; frontend on real API | [ ] |
| 4 | 7 | Auth (sessions or JWT + refresh), Google OAuth, role-based permissions | [ ] |
| 5 | 8 | Realtime board updates via WebSockets, Redis cache, notification job queue | [ ] |
| 6 | 9 | Docker Compose; GitHub Actions (lint + unit + integration tests) | [ ] |
| 7 | 9 | Deployed on AWS with HTTPS, logs, basic metrics/alerts | [ ] |
| 8 | 11 | README with architecture diagram, tradeoffs, "scale to 1M users"; 2-min demo | [ ] |

Crash note: if a milestone slips, log it in `PROGRESS.md` Plan Change Log and pull scope
(e.g. drop Google OAuth or search) rather than silently extending past week 12.

## Interview talking points (fill in as you build)

- Hardest bug and how you found it:
- A tradeoff you made (JWT vs sessions, or optimistic UI vs server-confirmed):
- How realtime updates stay consistent when two users move the same card:
- What breaks first at 100x traffic and how you'd fix it:
