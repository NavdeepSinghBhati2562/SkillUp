# Capstone: Real-Time Collaborative Task Board

A mini Trello/Linear that you build incrementally from week 5 to week 14. It's your proof of
full-stack ability on your resume, and the thing you'll talk about in interviews
("tell me about something you built", "how would you scale it?").

## Why this project
It naturally forces every skill interviewers probe: auth, relational data, caching, realtime,
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

## Milestones

| # | Week | Milestone | Done |
|---|---|---|---|
| 1 | 5 | Monorepo set up (`apps/web`, `apps/api`), Next.js skeleton with routing and layout | [ ] |
| 2 | 6 | Full UI on mocked data: boards, columns, drag-and-drop cards | [ ] |
| 3 | 10 | NestJS CRUD API + Postgres schema + migrations; frontend wired to real API | [ ] |
| 4 | 11 | Auth (sessions or JWT + refresh), Google OAuth, role-based permissions | [ ] |
| 5 | 12 | Realtime board updates via WebSockets, Redis cache for board reads, notification job queue | [ ] |
| 6 | 13 | Docker Compose for everything; GitHub Actions running lint + unit + integration tests | [ ] |
| 7 | 14 | Deployed on AWS with HTTPS, logs, basic metrics/alerts | [ ] |
| 8 | 17 | README with architecture diagram, tradeoffs, and "how I'd scale to 1M users"; 2-min demo video | [ ] |

## Interview talking points to prepare (fill in as you build)
- Hardest bug and how you found it:
- A tradeoff you made (for example, JWT vs sessions, or optimistic UI vs server-confirmed):
- How realtime updates stay consistent when two users move the same card:
- What breaks first at 100x traffic and how you'd fix it:
