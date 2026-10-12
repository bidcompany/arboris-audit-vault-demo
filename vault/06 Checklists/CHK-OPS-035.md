---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-OPS-035"
section: "Operational Controls"
requirement_ids:
  - "TRN-07"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/ops"
---

# CHK-OPS-035

## Audit question

Are temporary utility bypasses time limited and approved?

## Requirement

[[Requirement TRN-07]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-OPS-035") OR contains(requirement_ids, "TRN-07")
```
