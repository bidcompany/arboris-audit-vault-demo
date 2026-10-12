---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-033"
section: "Operational Controls"
requirement_ids:
  - "SUP-11"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-033

## Audit question

Are food-safety-critical assets identified?

## Requirement

[[Requirement SUP-11]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-033") OR contains(requirement_ids, "SUP-11")
```
