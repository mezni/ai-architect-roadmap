# AI Architect Roadmap

A structured, self-paced curriculum for becoming an **AI Architect**: the person who
translates business problems into production-grade AI systems and defends those
decisions with evidence.

This repository is organized as a roadmap of 16 courses, 14 hands-on labs, a set of
decision records, experiments, challenges, and reusable templates.

## Who this is for

- Engineers moving from ML/Backend into AI architecture roles
- Architects formalizing LLM/RAG/agent design skills
- Tech leads preparing for architecture reviews or interviews

## Repository layout

| Path | Purpose |
|------|---------|
| `courses/` | 16 courses from foundations to enterprise architecture |
| `labs/` | 14 scenario labs applying course material end-to-end |
| `challenges/` | Practice problems: architecture, security, reliability, cost, interviews |
| `decisions/` | Opinionated decision records for common AI design trade-offs |
| `experiments/` | Reproducible measurement experiments (chunking, top-k, reranking, ...) |
| `notes/` | Condensed reference notes by topic |
| `templates/` | Reusable templates (requirements, ADR, threat model, eval plan, ...) |
| `assets/` | Diagrams and images |

## How to use this roadmap

1. **Read** [`ROADMAP.md`](ROADMAP.md) for the recommended order and dependencies.
2. **Track** your progress in [`PROGRESS.md`](PROGRESS.md).
3. **Study** a course in `courses/NN-name/` — each has a README, numbered modules,
   exercises, examples, and a checkpoint.
4. **Apply** the material with the paired lab in `labs/`.
5. **Reference** [`KNOWLEDGE-MAP.md`](KNOWLEDGE-MAP.md) to jump to any topic.
6. **Decide** using `decisions/` when you hit a real design trade-off.

## Course overview

| # | Course | Focus |
|---|--------|-------|
| 01 | AI Architect Foundations | Concepts, problem framing, architecture, decisions |
| 02 | Production AI Engineering | Serving, latency, cost, reliability basics |
| 03 | RAG Foundations | Retrieval-augmented generation fundamentals |
| 04 | Advanced Enterprise RAG | Query pipelines, hybrid search, reranking, scale |
| 05 | Secure Enterprise RAG | Access control, PII, tenancy, data governance |
| 06 | AI Evaluation | Eval harnesses, metrics, LLM-as-judge, regression |
| 07 | LLMOps & Observability | Tracing, telemetry, prompt management, deployments |
| 08 | Agent Foundations | Tool use, planning, single-agent loops |
| 09 | Production Agentic AI | Durable execution, guardrails, human-in-the-loop |
| 10 | Multi-Agent Systems | Orchestration, delegation, coordination patterns |
| 11 | AI Security & Governance | Threat models, red teaming, compliance |
| 12 | Reliability, Scale & Cost | SLOs, load, fallbacks, unit economics |
| 13 | Enterprise AI Platform | Platform capabilities, internal developer experience |
| 14 | Enterprise AI Architecture | End-to-end reference architectures |
| 15 | Architecture Decisions | Structured trade-off analysis and ADRs |
| 16 | AI Architecture Generator | Capstone: generate architectures from requirements |

## Prerequisites

- Comfortable with Python or TypeScript
- Basic software architecture knowledge (layers, queues, APIs)
- Familiarity with LLM APIs (chat completion, embeddings) — course 01 covers the rest

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

See [`LICENSE`](LICENSE).
