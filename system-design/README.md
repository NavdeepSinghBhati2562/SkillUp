# System Design

Starts in **Week 8** of the 12-week plan. At your experience level this round often decides
mid vs senior, so give it real effort even on a crash timeline.

Use [`template.md`](template.md) for every practice design. Save each as
`system-design/designs/<name>.md`. Distill a **short** note after each design.

## Resources

- [Hello Interview: System Design in a Hurry](https://www.hellointerview.com/learn/system-design/in-a-hurry/introduction) (start here)
- [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer)
- *System Design Interview Vol. 1 & 2* by Alex Xu
- *Designing Data-Intensive Applications* by Martin Kleppmann (chapters 1–9)
- [GreatFrontEnd: front-end system design](https://www.greatfrontend.com/front-end-system-design-playbook)

## Concepts checklist

### Fundamentals (Week 8)

- [ ] Back-of-envelope estimation (QPS, storage, bandwidth)
- [ ] Vertical vs horizontal scaling, stateless services
- [ ] Load balancers (L4 vs L7), reverse proxies, API gateways
- [ ] Caching layers: client, CDN, application (Redis), database; eviction policies
- [ ] CDNs and static asset delivery

### Data & scaling (Week 9)

- [ ] SQL vs NoSQL: how to choose and justify it
- [ ] Replication (leader-follower, multi-leader), read replicas, replication lag
- [ ] Partitioning / sharding, consistent hashing, hot keys
- [ ] CAP theorem, consistency models (strong, eventual, read-your-writes)
- [ ] Message queues & streams (SQS, Kafka): delivery semantics, idempotency
- [ ] Blob storage (S3) and presigned URLs
- [ ] Search indexes (Elasticsearch basics)

### Reliability & operations (Weeks 9–10)

- [ ] Rate limiting, circuit breakers, retries with backoff + jitter
- [ ] Unique ID generation (Snowflake, UUIDv7)
- [ ] Distributed transactions: 2PC vs saga, outbox pattern
- [ ] Monitoring, SLIs/SLOs, graceful degradation
- [ ] Multi-region basics

## Practice prompts (suggested order)

- [ ] URL shortener (Week 10)
- [ ] Rate limiter (Week 10)
- [ ] News feed / timeline (Week 10)
- [ ] Chat system: WhatsApp / Slack (Week 11)
- [ ] Notification system (Week 11)
- [ ] File storage & sync: Dropbox / Google Drive (Week 11)
- [ ] Typeahead / autocomplete (Week 12)
- [ ] Your own capstone at 1M users (Week 12)

### Stretch (if ahead of schedule)

- [ ] Video streaming: YouTube / Netflix
- [ ] Ride sharing: Uber
- [ ] Ticket booking: Ticketmaster
- [ ] Web crawler

### Frontend system design (if the loop includes one)

- [ ] Autocomplete component
- [ ] Infinite-scroll news feed
- [ ] Image carousel / photo gallery
- [ ] Collaborative editor (Google Docs, high level)

**Your edge:** you've built offline-first, performance-sensitive mobile clients for years.
In any design, call out the client side (pagination, caching, optimistic updates, retries,
push vs poll). Many backend-only candidates skip it.
