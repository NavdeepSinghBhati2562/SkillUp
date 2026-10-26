# Full-Stack Curriculum

Tick topics as you learn them. Each section should end with something built in the capstone
(see [`../projects/capstone.md`](../projects/capstone.md)).

## Your head start from mobile
You already understand a lot of this, under different names:
- **Declarative UI and state management.** React will feel familiar after Flutter.
- **Async programming.** Dart `Future`/`Stream` map to JS `Promise` and async iterators/observables.
- **Consuming REST APIs, auth tokens, offline caching, performance profiling.**
- **App architecture.** Layers, repositories, and DI carry over to NestJS directly.

What's genuinely new: the browser platform, server-side thinking (concurrency, databases,
security), and running infrastructure.

---

## 1. Web fundamentals (Week 1)
- [ ] HTTP methods, status codes, headers, caching headers (`Cache-Control`, `ETag`)
- [ ] DNS, TLS/HTTPS, what happens when you type a URL
- [ ] Cookies vs localStorage vs sessionStorage
- [ ] HTML semantics, CSS box model, flexbox, grid, responsive design

Resources: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn), [web.dev Learn](https://web.dev/learn)

## 2. JavaScript & TypeScript (Weeks 1–2)
- [ ] Scope, closures, hoisting, `this`, prototypes
- [ ] Event loop: call stack, microtasks vs macrotasks
- [ ] Promises, async/await, error handling
- [ ] ES modules, destructuring, spread, optional chaining
- [ ] TS: types vs interfaces, generics, unions & narrowing, utility types (`Partial`, `Pick`, `Record`)

Resources: [javascript.info](https://javascript.info), [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)

## 3. React & Next.js (Weeks 3–4)
- [ ] Components, props, state, effects, refs, custom hooks
- [ ] Rendering behavior, reconciliation, keys, memoization (`useMemo`, `useCallback`, `React.memo`)
- [ ] Context vs external state (Zustand)
- [ ] Server state with TanStack Query
- [ ] Forms + validation (React Hook Form + Zod)
- [ ] Next.js App Router, server components, SSR / SSG / ISR / CSR tradeoffs
- [ ] Tailwind CSS
- [ ] Testing: Vitest, React Testing Library, Playwright (one end-to-end test)
- [ ] Core Web Vitals (LCP, INP, CLS), code splitting, image optimization
- [ ] Accessibility: ARIA basics, keyboard navigation

Resources: [react.dev](https://react.dev/learn), [nextjs.org/learn](https://nextjs.org/learn), [TanStack Query docs](https://tanstack.com/query/latest)

## 4. Backend with Node.js + NestJS (Week 5)
- [ ] Node event loop, non-blocking I/O, worker threads
- [ ] NestJS: modules, controllers, providers, DI, pipes, guards, interceptors
- [ ] REST design: resource naming, pagination (cursor vs offset), idempotency keys, versioning, error format
- [ ] Input validation, structured logging, config management
- [ ] (Optional) GraphQL basics, gRPC basics

Resources: [docs.nestjs.com](https://docs.nestjs.com), [Node.js docs](https://nodejs.org/en/learn)

## 5. Databases (Week 6)
- [ ] Relational modeling, normalization, when to denormalize
- [ ] Joins, aggregations, window functions, CTEs
- [ ] Indexes (B-tree, composite, covering), reading `EXPLAIN ANALYZE`
- [ ] Transactions, ACID, isolation levels, locking, deadlocks
- [ ] ORM: Prisma, migrations
- [ ] NoSQL overview: document (MongoDB), key-value (Redis/DynamoDB), wide-column (Cassandra), and when to choose each

Resources: [Use The Index, Luke](https://use-the-index-luke.com), [PostgreSQL Tutorial](https://www.postgresqltutorial.com), [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/)

## 6. Auth & security (Week 7)
- [ ] Password hashing (bcrypt/argon2), sessions vs JWT, refresh tokens
- [ ] OAuth2 / OpenID Connect flows (authorization code + PKCE)
- [ ] RBAC / permissions
- [ ] CORS, CSRF, XSS, SQL injection, rate limiting
- [ ] OWASP Top 10

Resources: [OWASP Top 10](https://owasp.org/www-project-top-ten/), [OAuth 2.0 simplified](https://www.oauth.com)

## 7. Caching, queues, realtime (Week 8)
- [ ] Redis data types, cache-aside, TTLs, invalidation strategies, cache stampede
- [ ] Rate limiting algorithms (token bucket, sliding window)
- [ ] Background jobs & queues (BullMQ), retries, dead-letter queues
- [ ] WebSockets vs SSE vs long polling

## 8. DevOps & cloud (Week 9)
- [ ] Docker: images, layers, multi-stage builds, docker-compose
- [ ] CI/CD with GitHub Actions
- [ ] AWS: IAM, EC2 vs ECS/Fargate vs Lambda, RDS, S3, CloudFront, VPC basics
- [ ] Observability: structured logs, metrics, traces (OpenTelemetry), alerts
- [ ] (Optional) Kubernetes fundamentals, Terraform basics

Resources: [Docker Get Started](https://docs.docker.com/get-started/), [AWS Skill Builder: Cloud Practitioner Essentials (free)](https://skillbuilder.aws)
