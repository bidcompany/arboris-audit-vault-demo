---
type: ai-guide
tags:
  - ai/audit
---

# AI Analysis Guide

## Recommended workflow

1. Retrieve relevant findings using metadata and semantic search.
2. Ask the model to cite finding IDs for every statement.
3. Separate direct evidence, inference and missing information.
4. Validate the result with the report owner.
5. Record only approved conclusions in the related finding note.

## Useful analysis lenses

- recurring root causes across different sites;
- common control failures hidden under different audit sections;
- corrective actions that address symptoms rather than causes;
- overdue or duplicated remediation;
- possible systemic issues requiring a group-level response;
- weak signals that precede more severe findings.

## Minimum answer format

Ask the model to return:

1. conclusion;
2. supporting finding IDs;
3. evidence quoted or paraphrased from each finding;
4. inference and confidence level;
5. contradictory evidence;
6. missing information;
7. recommended validation step.

See [[Prompt Library]] for ready-to-use prompts.
