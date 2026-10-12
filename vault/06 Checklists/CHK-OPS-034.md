---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-034"
section: "Operational Controls"
requirement_ids:
  - "TRN-04"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-034

## Audit question

Are maintenance deferrals risk assessed?

## Requirement

[[Requirement TRN-04]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-034") OR contains(requirement_ids, "TRN-04")
```
