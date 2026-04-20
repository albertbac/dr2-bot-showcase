# Architecture

## High-level architecture
- Classification: CORE HEALTHCARE / CLINICAL AI
- Category: clinical-ai
- Confidence: HIGH
- Exposure risk: MEDIUM

```mermaid
    flowchart LR
        A[Web client]
    B[API layer]
    C[Ingestion pipeline]
    D[Retrieval service]
    E[Evidence review surface]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Web client
- API layer
- Ingestion pipeline
- Retrieval service
- Evidence review surface

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.
