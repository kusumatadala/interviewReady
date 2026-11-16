# Sequential Interview Preparation Roadmap

**One session = 40 minutes. Sessions are numbered, not dated.** Follow this curriculum in order, at your own pace. Do **one session or several** whenever you have time; never auto-advance due to the calendar.

- Start with **[Session 001](sessions/001.md)**.
- Mark a session complete only after doing its exercise and writing short evidence in [progress/STATUS.md](progress/STATUS.md).
- If unfinished, resume the **same number**. A future daily check should link to the first unchecked session, not generate a day-based batch.
- Every session: **5 min recall → 25 min hands-on → 10 min tests/explanation/reflection**.
- 64 sequential sessions = **42 h 40 min** of focused practice, excluding breaks or repeat attempts.
- Earlier `daily/YYYY-MM-DD.md` files remain as historical archives, not the active course.

## Coverage map

| Phase | Sessions | Focus |
|---|---|---|
| 1. Core foundations | 001–008 | Java 17 collections and HashMap internals, DSA, Spring Boot REST and validation, SQL... |
| 2. Production correctness | 009–016 | Java concurrency, DSA, Spring @Transactional and proxy behavior, Hibernate/JPA... |
| 3. Payments and distributed reliability | 017–024 | Java concurrency, DSA, PostgreSQL, Payments... |
| 4. Algorithms and deployment | 025–032 | JVM memory, garbage collection and profiling, DSA, DSA, Kafka rebalances and offset commits... |
| 5. Full-stack and application security | 033–040 | TypeScript, React, React, Authentication... |
| 6. Applied AI engineering | 041–048 | Python service basics for Java engineers, LLM APIs, RAG, RAG evaluation... |
| 7. Advanced backend architecture | 049–056 | Microservice boundaries and API ownership, CQRS, event sourcing and trade-offs, Rate limiting, backpressure and queues, Observability... |
| 8. Interview conversion and consolidation | 057–064 | Java 8→17 / Spring modernization, Spring production hardening, PostgreSQL performance troubleshooting, Kafka tracing and replay... |

## Full numbered sequence

### Phase 1 — Core foundations

- **[Session 001](sessions/001.md)** — Java 17 collections and HashMap internals (40 min). **Done when:** Explain collisions, equals/hashCode and implement a frequency counter.
- **[Session 002](sessions/002.md)** — DSA — arrays and hash maps (40 min). **Done when:** Solve Two Sum and Group Anagrams in Java with edge tests.
- **[Session 003](sessions/003.md)** — Spring Boot REST and validation (40 min). **Done when:** Build a small validated API with consistent error responses.
- **[Session 004](sessions/004.md)** — SQL — indexes and EXPLAIN (40 min). **Done when:** Compare indexed versus full-scan query plans on sample data.
- **[Session 005](sessions/005.md)** — Kafka — topics, keys and consumer groups (40 min). **Done when:** Design ordered partitions and reason about consumer scale.
- **[Session 006](sessions/006.md)** — Docker — image to HTTP endpoint (40 min). **Done when:** Build and run a Spring Boot JAR container with health check.
- **[Session 007](sessions/007.md)** — React + TypeScript — API states (40 min). **Done when:** Build loading, success, empty and failure states.
- **[Session 008](sessions/008.md)** — Behavioral — first STAR + mini-mock (40 min). **Done when:** Deliver an authentic ownership story and 5-minute technical explanation.

### Phase 2 — Production correctness

- **Session 009 (planned; detailed page published when reached)** — Java concurrency — data races and atomics (40 min). **Done when:** Reproduce and fix a race using AtomicInteger or locks.
- **Session 010 (planned; detailed page published when reached)** — DSA — two pointers and sliding window (40 min). **Done when:** Solve two patterns and explain invariants.
- **Session 011 (planned; detailed page published when reached)** — Spring @Transactional and proxy behavior (40 min). **Done when:** Write tests for rollback and internal invocation pitfalls.
- **Session 012 (planned; detailed page published when reached)** — Hibernate/JPA — N+1 and pagination (40 min). **Done when:** Count SQL queries before and after fetch strategy change.
- **Session 013 (planned; detailed page published when reached)** — Kafka — at-least-once and idempotency (40 min). **Done when:** Design transactional deduplication with a unique event key.
- **Session 014 (planned; detailed page published when reached)** — Spring testing — JUnit and Mockito (40 min). **Done when:** Write unit vs integration tests with useful failure assertions.
- **Session 015 (planned; detailed page published when reached)** — REST API evolution and error contracts (40 min). **Done when:** Version an API and design stable retryable error responses.
- **Session 016 (planned; detailed page published when reached)** — Fintech mock — transfers and ledger (40 min). **Done when:** Whiteboard a consistent money movement flow.

### Phase 3 — Payments and distributed reliability

- **Session 017 (planned; detailed page published when reached)** — Java concurrency — executors and CompletableFuture (40 min). **Done when:** Build bounded asynchronous work with timeout and cancellation.
- **Session 018 (planned; detailed page published when reached)** — DSA — binary search variants (40 min). **Done when:** Solve rotated-array search and binary-search-on-answer.
- **Session 019 (planned; detailed page published when reached)** — PostgreSQL — isolation and locking (40 min). **Done when:** Demonstrate a concurrent debit race and compare locks.
- **Session 020 (planned; detailed page published when reached)** — Payments — double-entry ledger invariants (40 min). **Done when:** Model balance-preserving journal entries and reconciliation.
- **Session 021 (planned; detailed page published when reached)** — Outbox/inbox pattern (40 min). **Done when:** Draw crash windows and implement or pseudocode reliable publication.
- **Session 022 (planned; detailed page published when reached)** — Resilience — retries, circuit breakers, timeouts (40 min). **Done when:** Choose retry bounds and test downstream outages.
- **Session 023 (planned; detailed page published when reached)** — Docker Compose — app and database (40 min). **Done when:** Run an original API plus database locally.
- **Session 024 (planned; detailed page published when reached)** — Behavioral — decisions and mistakes (40 min). **Done when:** Tell a truthful error-and-recovery STAR story.

### Phase 4 — Algorithms and deployment

- **Session 025 (planned; detailed page published when reached)** — JVM memory, garbage collection and profiling (40 min). **Done when:** Explain heap, threads, GC logs and one memory symptom.
- **Session 026 (planned; detailed page published when reached)** — DSA — linked lists and stacks (40 min). **Done when:** Solve cycle detection and monotonic-stack practice.
- **Session 027 (planned; detailed page published when reached)** — DSA — graphs BFS/DFS (40 min). **Done when:** Solve Number of Islands with complexity and boundary tests.
- **Session 028 (planned; detailed page published when reached)** — Kafka rebalances and offset commits (40 min). **Done when:** Trace ownership and duplicates through rebalances.
- **Session 029 (planned; detailed page published when reached)** — Caching, eviction and consistency (40 min). **Done when:** Design a read cache with TTL and invalidation trade-offs.
- **Session 030 (planned; detailed page published when reached)** — Kubernetes/OpenShift — probes, resources and secrets (40 min). **Done when:** Configure readiness/liveness and explain rollout health.
- **Session 031 (planned; detailed page published when reached)** — Cloud fundamentals — IAM, networking, managed services (40 min). **Done when:** Map a container service to basic secure cloud components.
- **Session 032 (planned; detailed page published when reached)** — Fintech design mock — high availability (40 min). **Done when:** Give a structured 10-minute design and critique.

### Phase 5 — Full-stack and application security

- **Session 033 (planned; detailed page published when reached)** — TypeScript — interfaces, unions and generics (40 min). **Done when:** Model API results with exhaustive error handling.
- **Session 034 (planned; detailed page published when reached)** — React — state, effects and request cancellation (40 min). **Done when:** Prevent stale responses and memory leaks.
- **Session 035 (planned; detailed page published when reached)** — React — render performance and test strategy (40 min). **Done when:** Profile re-renders and write component behavior tests.
- **Session 036 (planned; detailed page published when reached)** — Authentication — OAuth2/OIDC and sessions (40 min). **Done when:** Map auth code flow, tokens, renewal and common mistakes.
- **Session 037 (planned; detailed page published when reached)** — Spring Security — authorization by resource (40 min). **Done when:** Enforce per-user access in a testable endpoint.
- **Session 038 (planned; detailed page published when reached)** — DSA — binary trees and traversal (40 min). **Done when:** Implement BFS/DFS and lowest common ancestor.
- **Session 039 (planned; detailed page published when reached)** — DSA — heaps and top K (40 min). **Done when:** Solve a priority queue problem and analyze trade-offs.
- **Session 040 (planned; detailed page published when reached)** — Full-stack integration mock (40 min). **Done when:** Build or review one Java API + typed React form.

### Phase 6 — Applied AI engineering

- **Session 041 (planned; detailed page published when reached)** — Python service basics for Java engineers (40 min). **Done when:** Implement a small typed FastAPI endpoint as a learning exercise.
- **Session 042 (planned; detailed page published when reached)** — LLM APIs — structured outputs, errors and cost (40 min). **Done when:** Wrap a model call with schema validation and retries.
- **Session 043 (planned; detailed page published when reached)** — RAG — ingest, chunk and retrieve (40 min). **Done when:** Prototype retrieval and describe chunking/recall trade-offs.
- **Session 044 (planned; detailed page published when reached)** — RAG evaluation — relevance and grounded answers (40 min). **Done when:** Design a tiny labeled evaluation set and score quality.
- **Session 045 (planned; detailed page published when reached)** — Agents, tools and MCP contracts (40 min). **Done when:** Define safe tool schemas and failure recovery.
- **Session 046 (planned; detailed page published when reached)** — AI safety/observability — prompt injection, traces (40 min). **Done when:** List trust boundaries, privacy and evaluation signals.
- **Session 047 (planned; detailed page published when reached)** — Production AI service design (40 min). **Done when:** Plan latency budgets, caching, rate limits and fallbacks.
- **Session 048 (planned; detailed page published when reached)** — Applied AI mock — technical trade-offs (40 min). **Done when:** Walk through a grounded RAG/tool-calling system.

### Phase 7 — Advanced backend architecture

- **Session 049 (planned; detailed page published when reached)** — Microservice boundaries and API ownership (40 min). **Done when:** Decompose a domain with contracts and data ownership.
- **Session 050 (planned; detailed page published when reached)** — CQRS, event sourcing and trade-offs (40 min). **Done when:** Compare state reconstruction with simpler CRUD.
- **Session 051 (planned; detailed page published when reached)** — Rate limiting, backpressure and queues (40 min). **Done when:** Choose limits and reason through overload.
- **Session 052 (planned; detailed page published when reached)** — Observability — logs, metrics and traces (40 min). **Done when:** Create useful SLO/SLI and tracing correlation examples.
- **Session 053 (planned; detailed page published when reached)** — Multi-region and availability trade-offs (40 min). **Done when:** Explain failover, latency and consistency.
- **Session 054 (planned; detailed page published when reached)** — DSA — dynamic programming fundamentals (40 min). **Done when:** Solve memoized vs bottom-up 1D DP.
- **Session 055 (planned; detailed page published when reached)** — DSA — intervals, sorting and greedy (40 min). **Done when:** Solve a merge/scheduling scenario with proof sketch.
- **Session 056 (planned; detailed page published when reached)** — Incident diagnosis and communication (40 min). **Done when:** Practice outage timeline, mitigation, follow-up actions.

### Phase 8 — Interview conversion and consolidation

- **Session 057 (planned; detailed page published when reached)** — Java 8→17 / Spring modernization (40 min). **Done when:** Explain migration risks, API compatibility and test plan.
- **Session 058 (planned; detailed page published when reached)** — Spring production hardening (40 min). **Done when:** Configure health, graceful shutdown, metrics and secure defaults.
- **Session 059 (planned; detailed page published when reached)** — PostgreSQL performance troubleshooting (40 min). **Done when:** Use index/query evidence to propose an optimization.
- **Session 060 (planned; detailed page published when reached)** — Kafka tracing and replay (40 min). **Done when:** Design correlation IDs, safe replay and DLQ recovery.
- **Session 061 (planned; detailed page published when reached)** — Testing strategy — unit, contract and end-to-end (40 min). **Done when:** Design a testing pyramid for event-driven service.
- **Session 062 (planned; detailed page published when reached)** — Final system design — investigation platform (40 min). **Done when:** Mock architecture with resilience, scale and audit requirements.
- **Session 063 (planned; detailed page published when reached)** — Timed Java coding mock (40 min). **Done when:** Complete one medium problem under interview constraints.
- **Session 064 (planned; detailed page published when reached)** — Final behavioral and role-fit mock (40 min). **Done when:** Prepare clear motivation, ownership, relocation/remote considerations.

## Completion rules

1. A planned session is **not** completed automatically, even if its page exists.
2. One 40-minute block ends with working code/tests, a concise diagram, or a spoken explanation with self-grading. Record a blocker honestly if the task needs another block.
3. The canonical pointer is the **first unchecked number** in `progress/STATUS.md` (not the day or number of automation runs).
4. GitHub can hold private notes elsewhere; **this repository is public**, so avoid employer-confidential examples, personal/application information and secrets.
5. Sessions **001–008** have detailed, working pages. Future lessons **009–064** have fixed titles in this roadmap and will be published in sequence when reached, without tying them to dates. No dead links to unpublished pages.

## Main references

- [Java 17](https://docs.oracle.com/en/java/javase/17/docs/) · [Spring Framework](https://docs.spring.io/spring-framework/reference/) · [Spring Data JPA](https://docs.spring.io/spring-data/jpa/reference/)
- [Kafka documentation](https://kafka.apache.org/documentation/) · [PostgreSQL](https://www.postgresql.org/docs/current/)
- [Docker](https://docs.docker.com/get-started/) · [Kubernetes](https://kubernetes.io/docs/concepts/)
- [React Learn](https://react.dev/learn) · [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [LeetCode](https://leetcode.com/problemset/) · [NeetCode](https://neetcode.io/roadmap)
- [Spring AI](https://docs.spring.io/spring-ai/reference/) · [Model Context Protocol](https://modelcontextprotocol.io/introduction)
