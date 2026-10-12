---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-038"
section: "Operational Controls"
requirement_ids:
  - "SAN-09"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-038

## Audit question

Are temperature deviations assessed using exposure time?

## Requirement

[[Requirement SAN-09]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-038") OR contains(requirement_ids, "SAN-09")
```
