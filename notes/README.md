# Notes System

Two layers so you can **learn deeply** and **review fast**.

| Layer | Folder | When you write it | When you use it |
|---|---|---|---|
| **Brief** | [`brief/`](brief/) | While learning a topic (same day) | Re-learning in 20–40 min after a gap |
| **Short** | [`short/`](short/) | Right after brief, distill to essentials | 5–10 min skim before interviews / weekly review |

## Naming

Use the same slug in both folders:

```
notes/brief/arrays-hashing.md
notes/short/arrays-hashing.md
```

Suggested slugs as you go: `web-fundamentals`, `javascript-core`, `typescript`, `react`, `nextjs`, `nestjs`, `postgres`, `auth-security`, `redis-jobs`, `docker-ci`, `aws-basics`, plus each DSA pattern (`two-pointers`, `sliding-window`, `trees`, `graphs`, `dp-1d`, …) and each system-design topic (`url-shortener`, `chat-system`, …).

## Rules

1. **Brief first, short second.** Never only short — you'll forget the "why".
2. After finishing a tracker topic, notes for that topic should exist (or be updated).
3. Short notes: no long prose. Bullets, complexities, "when to use", common pitfalls.
4. Brief notes: one worked example minimum; Flutter/Android analogies welcome.
5. Use templates in [`_templates/`](_templates/).

## Weekly review ritual (Sunday, ~45 min)

1. Skim all **short** notes from the weeks you've completed.
2. Anything fuzzy → open its **brief** and rewrite the short note.
3. Mark weak topics in `PROGRESS.md` under the weekly retro.
