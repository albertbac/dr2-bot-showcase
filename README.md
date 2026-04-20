# Evidence-first Specialist Analyst Assistant

## 1. App name
dr2-bot

## 2. One-line summary
A public-safe technical case for an evidence-first specialist analyst assistant built around controlled retrieval and document grounding.

## 3. Primary user
Specialist analyst

## 4. Secondary user
Reviewer or operations lead

## 5. Problem solved
Document-heavy work needs answers that stay traceable to source material instead of turning into unverifiable chat output.

## 6. Short workflow
Documents are ingested, indexed, searched through a controlled evidence flow, and returned to the user with grounded responses and review context.

## 7. Public-safe technical scope
Public-safe scope covers ingestion, retrieval, evidence presentation, admin controls, and high-level assistant workflow.

## 8. High-level integrations
High-level only: storage, retrieval services, model providers, and optional graph or search layers.

## 9. What stays private and why
Prompt templates, ranking weights, provider selection, routing rules, and evidence policies remain private because they define product quality and security boundaries.

## 10. Confidence level
HIGH

## 11. Exposure risk
MEDIUM

## 12. Repository map
```text
dr2-bot-showcase/
├── README.md
├── LICENSE
├── .gitignore
├── PUBLIC_DISCLOSURE_POLICY.md
├── SECURITY_BOUNDARY.md
├── APP_CARD_PTBR.md
├── TECHNICAL_STORY.md
├── ARCHITECTURE.md
├── WORKFLOW.md
├── PRIVACY_BOUNDARY.md
├── IMPACT_NOTES.md
├── MANUAL_TODO.md
├── site/
│   └── SITE_COPY_PTBR.md
├── screenshots/
│   └── SHOTLIST.md
├── synthetic-data/
│   ├── README.md
│   └── SYNTHETIC_DATA_TODO.md
├── reports/
│   ├── PRIVACY_AUDIT.md
│   └── PUBLISH_CHECKLIST.md
└── docs/
    ├── og-social-card.svg
    └── repo-map.svg
```

## 13. Manual public-safe evidence still needed
- Confirm the public persona label for the assistant
- Capture manual screenshots with synthetic documents
- Validate which evidence view is safest for public positioning
