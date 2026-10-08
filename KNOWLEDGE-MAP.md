                         AI ARCHITECTURE
                              │
          ┌───────────────────┼────────────────────┐
          │                   │                    │
      AI SYSTEMS        SOFTWARE ARCH         ENTERPRISE
          │                   │                    │
     ┌────┼────┐         ┌────┼────┐         ┌────┼────┐
     │    │    │         │    │    │         │    │    │
    RAG Agents Models    C4  ADR  NFR     Security SRE Cost
     │    │
     │    ├── Tools
     │    ├── Memory
     │    ├── State
     │    ├── Planning
     │    ├── HITL
     │    └── Multi-Agent
     │
     ├── Ingestion
     ├── Chunking
     ├── Embeddings
     ├── Retrieval
     ├── Hybrid Search
     ├── Reranking
     └── Evaluation
                CROSS-CUTTING CONCERNS
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
     Security       Observability     Reliability
        │                │                │
        ▼                ▼                ▼
    Governance        Evaluation          Cost