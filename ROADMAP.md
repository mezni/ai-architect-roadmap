# Roadmap

Recommended study order, with dependencies and paired labs. Each stage builds on the
previous one; you can go deep or skim depending on your background.

## Stage map

```
Stage 1  Foundations ──────────────┐
Stage 2  Production Engineering ───┤
Stage 3  RAG Track (03→04→05) ─────┼──► Stage 5  Ops & Quality (06→07)
Stage 4  Agent Track (08→09→10) ───┘         │
                                              ▼
                    Stage 6  Governance & Scale (11→12)
                                              │
                                              ▼
                    Stage 7  Enterprise Architecture (13→14→15→16)
```

## Stage 1 — Foundations

| Course | Why first | Lab |
|--------|-----------|-----|
| 01 AI Architect Foundations | Shared vocabulary: concepts → problem → architecture → decisions → implementation → failure modes | `labs/01-insurance-claims-architecture` |

**Milestone:** pass `courses/01-ai-architect-foundations/checkpoint.md`.

## Stage 2 — Production Engineering

| Course | Why | Lab |
|--------|-----|-----|
| 02 Production AI Engineering | Serving, latency, cost, reliability of LLM apps | `labs/02-document-processing-api` |

## Stage 3 — RAG Track

| Course | Why | Lab |
|--------|-----|-----|
| 03 RAG Foundations | Chunking, embeddings, retrieval, generation | `labs/03-technical-support-rag` |
| 04 Advanced Enterprise RAG | Hybrid search, reranking, query rewriting, scale | `labs/04-financial-research-rag` |
| 05 Secure Enterprise RAG | Row-level access, PII, tenancy, audit | `labs/05-secure-legal-rag` |

**Checkpoint lab:** `labs/06-rag-evaluation` (pairs with Stage 5 course 06).

## Stage 4 — Agent Track

| Course | Why | Lab |
|--------|-----|-----|
| 08 Agent Foundations | Tool calling, planning loops, memory | `labs/08-incident-investigation-agent` |
| 09 Production Agentic AI | Durability, guardrails, HITL, idempotency | `labs/09-procurement-agent` |
| 10 Multi-Agent Systems | Orchestrator/worker, delegation, handoffs | `labs/10-multi-agent-incident-response` |

> Stage 4 can run in parallel with Stage 3 once Stage 2 is done.

## Stage 5 — Quality & Ops

| Course | Why | Lab |
|--------|-----|-----|
| 06 AI Evaluation | Offline/online evals, judges, regression gates | `labs/06-rag-evaluation` |
| 07 LLMOps & Observability | Tracing, metrics, prompt registry, canaries | `labs/07-ai-observability` |

## Stage 6 — Governance & Scale

| Course | Why | Lab |
|--------|-----|-----|
| 11 AI Security & Governance | Threat modeling, red teaming, policy | `labs/11-banking-ai-security-review` |
| 12 Reliability, Scale & Cost | SLOs, chaos, load, cost engineering | `labs/12-scale-reliability-challenge` |

## Stage 7 — Enterprise Architecture

| Course | Why | Lab |
|--------|-----|-----|
| 13 Enterprise AI Platform | Building the platform other teams use | `labs/13-shared-ai-platform` |
| 14 Enterprise AI Architecture | Reference architectures, multi-region | `labs/14-global-insurance-ai-platform` |
| 15 Architecture Decisions | ADR craft, trade-off facilitation | — |
| 16 AI Architecture Generator | Capstone: requirements → architecture | — |

## Suggested pacing

| Pace | Weekly load | Duration (all 16) |
|------|-------------|-------------------|
| Intensive | ~12 h/week (1 course + lab work) | ~16 weeks |
| Standard | ~6 h/week | ~7–8 months |
| Fast (experienced) | skim 01–02, deep-dive 03–10 | ~10 weeks |

## Parallel tracks (shortcuts)

- **RAG specialist:** Stage 1 → 03 → 04 → 05 → 06 → labs 03–06
- **Agent specialist:** Stage 1 → 02 → 08 → 09 → 10 → labs 08–10
- **Platform/enterprise:** Stage 1 → 02 → 06 → 07 → 11 → 12 → 13 → 14
- **Interview prep:** Stage 1 → 15 + `challenges/interviews` + `decisions/`

## Supporting material at every stage

- `decisions/` — consult whenever a course presents a trade-off
- `experiments/` — run or read when you need evidence for a tuning choice
- `notes/` — quick refreshers per topic
- `templates/` — use in labs and challenges as deliverables
