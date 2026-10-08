# Knowledge Map

Every major topic in the curriculum, mapped to where it is taught, practiced, and
referenced. Use this to jump straight to what you need.

Legend: **C** = course module, **L** = lab, **D** = decision record,
**E** = experiment, **N** = note, **T** = template.

---

## 1. Foundations & problem framing

| Topic | Where |
|-------|-------|
| AI architecture concepts | C01/01-concepts, N/architecture |
| Problem framing & requirements | C01/02-problem, T/requirements-template, T/business-context-template |
| Architecture styles for AI systems | C01/03-architecture, C14, L01 |
| Design decisions & trade-offs | C01/04-design-decisions, C15, decisions/ |
| Implementation approach | C01/05-implementation, C02 |
| Failure modes | C01/06-failure-modes, N/reliability |
| NFRs | T/nfr-template, C12 |

## 2. Production AI engineering

| Topic | Where |
|-------|-------|
| Inference serving patterns | C02, N/models |
| Latency & streaming | C02, C12, N/reliability |
| Batch vs realtime | C02, D/sync-vs-async |
| Model selection | C02, D/small-vs-large-model, E/EXP-005 |
| Structured outputs | C02, C06 |
| Document processing pipelines | L02 |

## 3. RAG

| Topic | Where |
|-------|-------|
| Chunking strategies | C03, E/EXP-001, N/rag |
| Embeddings & indexing | C03, N/rag |
| Similarity search / top-k | C03, E/EXP-002 |
| Hybrid search (BM25 + vector) | C04, E/EXP-003, D/vector-vs-hybrid-search |
| Reranking | C04, E/EXP-004 |
| Query rewriting & expansion | C04, N/rag |
| Context assembly & citations | C03, C04 |
| RAG vs fine-tuning | D/rag-vs-fine-tuning |
| Access-controlled retrieval | C05, L05 |
| RAG evaluation | C06, L06, T/evaluation-plan-template |

## 4. Evaluation

| Topic | Where |
|-------|-------|
| Offline eval design | C06, T/evaluation-plan-template |
| Metrics (retrieval, generation, task) | C06, N/evaluation |
| LLM-as-judge | C06, N/evaluation |
| Golden sets & regression gates | C06, C07 |
| Online evals & feedback | C06, C07 |

## 5. LLMOps & observability

| Topic | Where |
|-------|-------|
| Tracing & spans | C07, L07, N/llmops |
| Prompt management & versioning | C07, N/llmops |
| Deployments: canary, shadow, rollback | C07, C12 |
| Token & cost telemetry | C07, C12, N/cost |
| Incident response for AI | L08, L10 |

## 6. Agents

| Topic | Where |
|-------|-------|
| Tool use & function calling | C08, N/agents |
| Planning loops & ReAct | C08 |
| Memory & state | C08, C09 |
| Workflow vs agent | D/workflow-vs-agent |
| Agent vs multi-agent | D/agent-vs-multi-agent |
| Durable execution & retries | C09, C12 |
| Guardrails & HITL | C09, C11 |
| Step limits & runaway cost | E/EXP-006 |
| Orchestration patterns | C10, L10 |

## 7. Security & governance

| Topic | Where |
|-------|-------|
| Threat modeling | C11, T/threat-model-template, L11 |
| Prompt injection & jailbreaks | C11, N/security |
| Data governance & PII | C05, C11 |
| RBAC / ABAC in retrieval | C05, L05 |
| Audit & compliance | C11, C13 |
| Red teaming | C11, N/security |
| Architecture review | T/architecture-review-template |

## 8. Reliability, scale & cost

| Topic | Where |
|-------|-------|
| SLOs & error budgets | C12, N/reliability |
| Fallbacks & degradation | C12, C01/06-failure-modes |
| Load & capacity planning | C12, L12 |
| Multi-region & DR | C14, D/single-vs-multi-region |
| Cost modeling & unit economics | C12, N/cost |
| Serverless vs Kubernetes | D/serverless-vs-kubernetes |
| Managed vs self-hosted | D/managed-vs-self-hosted |

## 9. Platform & enterprise architecture

| Topic | Where |
|-------|-------|
| AI platform capabilities | C13, L13 |
| Shared gateways & model routing | C13, C14 |
| Reference architectures | C14, L01, L14 |
| ADRs & decision facilitation | C15, T/adr-template |
| Architecture from requirements | C16, T/architecture-template |

## 10. Challenge tracks

| Track | Where |
|-------|-------|
| Architecture challenges | challenges/architecture |
| Security challenges | challenges/security |
| Reliability challenges | challenges/reliability |
| Cost challenges | challenges/cost |
| Interview prep | challenges/interviews, decisions/ |
