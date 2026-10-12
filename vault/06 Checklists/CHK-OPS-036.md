---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-036"
section: "Operational Controls"
requirement_ids:
  - "TRN-10"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-036

## Audit question

Are critical alarms challenged using live tests?

## Requirement

[[Requirement TRN-10]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-036") OR contains(requirement_ids, "TRN-10")
```
