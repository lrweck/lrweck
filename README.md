### Olá! I'm Luis 👋

**✍️ Blog:** [lrweck.github.io/posts](https://lrweck.github.io/posts/) — engineering notes on Go, PostgreSQL and the occasional benchmark deep-dive.

Go developer in Santa Catarina, Brasil. I build **multitenant PostgreSQL tooling** and small, fast Go libraries — connection pools, iterators, structured logging, and benchmarks.

#### What I'm working on

- **[tpool](https://github.com/lrweck/tpool)** — multitenant PostgreSQL connection pool: global budget, per-tenant floors, burst spillover.
- **[tenantpool](https://github.com/lrweck/tenantpool)** — lazy per-tenant pool lifecycle manager for Go; one factory call per cold tenant, idle reaping, stats.
- **[wideslog](https://github.com/lrweck/wideslog)** — wide events on top of `log/slog`: one operation → one structured record.
- **[iter](https://github.com/lrweck/iter)** — lazy, composable, type-safe pipelines for Go iterators.

#### Also poking at

- [pgrust-benchmark](https://github.com/lrweck/pgrust-benchmark) — pgrust v0.2 (Rust) vs PostgreSQL 18.6 native binaries.
- [pgbench](https://github.com/lrweck/pgbench) — Postgres benchmarking setup.

#### How I work

- Minimal libraries: a small API, no speculative abstraction, benchmarks that tell the truth.
- Postgres-first: `pgx`, `pgxpool`, `database/sql`, native binaries.
- Lazy first / ponytail mindset: the shortest path that still works.

---

*Check [my blog](https://lrweck.github.io/posts/) or the repos — feedback and PRs welcome.*
