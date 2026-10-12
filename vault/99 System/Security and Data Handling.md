---
type: policy-guide
tags:
  - system/security
---

# Security and Data Handling

## Recommended architecture

Use local storage and local embeddings as the default. Use a cloud model only through an approved enterprise endpoint and only for document classes authorized for external processing.

## Required controls before real audit data

- Store the vault in an approved encrypted location.
- Apply least-privilege access at folder and synchronization levels.
- Do not synchronize the vault through personal cloud accounts.
- Exclude credentials, authentication tokens and personal secrets from notes.
- Verify model-provider retention, training usage, processing region and audit logging.
- Define whether attachments may be indexed or only Markdown extracts.
- Record source provenance and preserve the authoritative audit report outside Obsidian.
- Treat AI output as analysis, not audit evidence, until a qualified reviewer validates it.

## AI processing tiers

| Tier | Data | Suggested processing |
|---|---|---|
| Green | Synthetic or public | Local or approved cloud model |
| Amber | Internal and non-sensitive | Local embeddings; approved enterprise model with controls |
| Red | Confidential, personal or legally restricted | Local-only unless a formal exception authorizes cloud processing |

## Evidence discipline

Every generated conclusion should identify the source finding IDs. Store hypotheses under `AI analysis workspace`; never rewrite the original observed condition or evidence with generated text.
