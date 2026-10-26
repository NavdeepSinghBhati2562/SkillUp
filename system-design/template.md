# Design: <name>

Practice in 45 minutes, timed. Time budget per section is in brackets.

## 1. Requirements (5 min)
**Functional** (top 3, must-have only):
-

**Non-functional** (scale, latency, availability vs consistency, durability):
-

**Out of scope:**
-

## 2. Estimation (2–3 min, only where it changes a decision)
- Users / DAU:
- Read QPS / write QPS (peak):
- Storage per year:

## 3. Core entities & API (5 min)
**Entities:**
-

**API:**
```
POST /...
GET  /...
```

## 4. High-level design (10 min)
Draw it with boxes and arrows: client → LB → services → data stores. Walk through each
functional requirement end to end.

```
[Client] -> [API Gateway/LB] -> [Service] -> [DB]
```

## 5. Deep dives (15 min)
Pick 2–3 that matter most for *this* problem:
- Scaling the bottleneck (sharding, caching, replicas):
- Consistency / race conditions:
- Failure handling (retries, idempotency, queues):
- Hot spots / celebrity problem:

## 6. Wrap-up (2 min)
- Tradeoffs I made and why:
- What I'd monitor:
- What I'd do with more time:

## Self-review after practice
- Where did I run out of time?
- What did I hand-wave?
- Compare with a reference solution. What did they do differently?
