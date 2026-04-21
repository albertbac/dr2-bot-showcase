# Workflow

## High-level functional workflow
1. Upload or register documents
2. Index and normalize content
3. Run evidence-backed query
4. Review answer with grounding
5. Escalate or refine as needed

```mermaid
    flowchart TD
        W1["Upload or register documents"]
    W2["Index and normalize content"]
    W3["Run evidence-backed query"]
    W4["Review answer with grounding"]
    W5["Escalate or refine as needed"]
    W1 --> W2
    W2 --> W3
    W3 --> W4
    W4 --> W5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
