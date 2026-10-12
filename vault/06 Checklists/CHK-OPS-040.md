---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-040"
section: "Operational Controls"
requirement_ids:
  - "SAN-14"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-040

## Audit question

Are internal auditor independence and competence documented?

## Requirement

[[Requirement SAN-14]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-040") OR contains(requirement_ids, "SAN-14")
```
