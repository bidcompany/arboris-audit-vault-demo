---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-037"
section: "Operational Controls"
requirement_ids:
  - "SAN-05"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-037

## Audit question

Are suppliers and subcontractors monitored across the service chain?

## Requirement

[[Requirement SAN-05]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-037") OR contains(requirement_ids, "SAN-05")
```
