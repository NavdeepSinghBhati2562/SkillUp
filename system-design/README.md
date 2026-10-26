# System Design

Starts in week 14 and runs to the end. At your experience level this round decides whether
you come in as mid-level or senior, so give it real effort.

Use [`template.md`](template.md) for every practice design. Save each design as
`system-design/designs/<name>.md`.

## Resources
- [Hello Interview: System Design in a Hurry](https://www.hellointerview.com/learn/system-design/in-a-hurry/introduction) (start here)
- [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer)
- *System Design Interview Vol. 1 & 2* by Alex Xu
- *Designing Data-Intensive Applications* by Martin Kleppmann (chapters 1–9 are the core)
- [GreatFrontEnd: front-end system design](https://www.greatfrontend.com/front-end-system-design-playbook) for frontend-focused rounds

## Concepts checklist

### Fundamentals (Week 14)
- [ ] Back-of-envelope estimation (QPS, storage, bandwidth)
- [ ] Vertical vs horizontal scaling, stateless services
- [ ] Load balancers (L4 vs L7), reverse proxies, API gateways
- [ ] Caching layers: client, CDN, application (Redis), database; eviction policies
- [ ] CDNs and static asset delivery

### Data & scaling (Week 15)
- [ ] SQL vs NoSQL: how to choose and justify it
- [ ] Replication (leader-follower, multi-leader), read replicas, replication lag
- [ ] Partitioning / sharding strategies, consistent hashing, hot keys
- [ ] CAP theorem, consistency models (strong, eventual, read-your-writes)
- [ ] Message queues & streams (SQS, Kafka): delivery semantics, idempotency
- [ ] Blob storage (S3) and presigned URLs
- [ ] Search indexes (Elasticsearch basics)

### Reliability & operations (Weeks 15–16)
- [ ] Rate limiting, circuit breakers, retries with backoff + jitter
- [ ] Unique ID generation (Snowflake, UUIDv7)
- [ ] Distributed transactions: 2PC vs saga pattern, outbox pattern
- [ ] Monitoring, SLIs/SLOs, graceful degradation
- [ ] Multi-region basics

## Practice prompts (in suggested order)
- [ ] URL shortener (Week 16)
- [ ] Rate limiter (Week 16)
- [ ] News feed / timeline (Week 16)
- [ ] Chat system: WhatsApp / Slack (Week 17)
- [ ] Notification system (Week 17)
- [ ] File storage & sync: Dropbox / Google Drive (Week 17)
- [ ] Typeahead / autocomplete (Week 18)
- [ ] Video streaming: YouTube / Netflix (Week 18)
- [ ] Ride sharing: Uber (Week 19)
- [ ] Ticket booking: Ticketmaster (Week 19)
- [ ] Web crawler (Week 20)
- [ ] Your own capstone at 1M users (Week 20)

### Frontend system design (for full-stack loops that include one)
- [ ] Autocomplete component
- [ ] Infinite-scroll news feed
- [ ] Image carousel / photo gallery
- [ ] Collaborative editor (Google Docs, high level)

**Your edge:** you've built offline-first, performance-sensitive mobile clients for years.
In any design, call out the client side (pagination, caching, optimistic updates, retries,
push vs poll). Many backend-only candidates skip it.
