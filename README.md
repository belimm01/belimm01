# Mykyta Belimenko

**Senior Software Engineer — backend, platform and AI.** I build Java/Spring Boot and Python/FastAPI services, Kubernetes platforms on AWS, and LLM applications with the Model Context Protocol. 10+ years in enterprise software, from architecture and API contracts to production releases.

[LinkedIn](https://www.linkedin.com/in/mbelimenko/) · Prague, Czechia · Fully remote · EU citizen

## Featured projects

- **[ChangeGuard AI](https://github.com/belimm01/changeguard-ai)** — advisory pull-request change-impact analyser. Deterministic rules for Python dependencies, OpenAPI, Avro and Kubernetes produce evidence-backed findings; a grounded LLM layer and an MCP server are in progress. Python 3.13, FastAPI, Pydantic, async SQLAlchemy, PostgreSQL, strict mypy.
- **[Platform Blueprint](https://github.com/belimm01/platform-blueprint)** — reference internal developer platform: a team-facing service contract rendered into reviewable GitOps configuration, with Go, Kubernetes, Crossplane, Argo CD and Kyverno policy guardrails. Ships with ADRs, a security model and an operational runbook.
- **[Relay](https://github.com/belimm01/relay)** — self-hosted webhook gateway with durable delivery, idempotency, bounded retries and replay. Java 21, Spring Boot, PostgreSQL, Vue 3.
- **[Changelog Studio](https://github.com/belimm01/changelog-studio)** — release-note workflow with a typed domain core, REST API, React client, conventional-commit ingestion and CI.
- **[Recap](https://github.com/belimm01/recap)** — developer-productivity CLI that turns GitLab and Jira activity into a paste-ready standup digest.

## Professional highlights

- Lead architect of a four-country product catalogue with 100,000+ products (Java/Spring Boot and Python/FastAPI services, Kafka, PostgreSQL, Kubernetes); cut a key aggregated-data API from 35 minutes to 40 seconds.
- Built an internal LLM assistant — Claude models, Agno, a custom Python MCP server with per-user authorization, and a DeepEval regression suite in CI — used weekly by 200+ colleagues.
- Built and operated an internal developer platform used by 93 engineering teams, cutting repository onboarding from days to under an hour.

## Stack

- **Backend:** Java 21, Spring Boot, Python, FastAPI, Node.js/NestJS, REST, Kafka, Avro
- **Platform:** Kubernetes, AWS, Helm, Argo CD, Crossplane, Go, GitLab CI/CD, GitHub Actions
- **Data:** PostgreSQL, MySQL, Elasticsearch
- **AI:** Claude models, Agno, Model Context Protocol, DeepEval
- **Frontend:** TypeScript, React, Vue, micro-frontends
- **Observability:** Prometheus, Grafana, Loki

## Engineering approach

- Use Claude Code and OpenAI Codex for exploration, implementation, testing and review, while keeping architecture decisions and final verification my responsibility.
- Keep domain behaviour independent from transport and UI frameworks.
- Treat retries, idempotency, authorization, observability and rollback as product requirements.
- Ship reviewable changes with executable tests, reproducible local workflows and production-ready deployment artifacts.
