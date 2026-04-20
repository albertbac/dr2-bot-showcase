# Workflow

## High-level functional workflow
1. Upload or register documents
2. Index and normalize content
3. Run evidence-backed query
4. Review answer with grounding
5. Escalate or refine as needed

```mermaid
    flowchart TD
        S1["Upload or register documents"]
    S2["Index and normalize content"]
    S3["Run evidence-backed query"]
    S4["Review answer with grounding"]
    S5["Escalate or refine as needed"]
    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
