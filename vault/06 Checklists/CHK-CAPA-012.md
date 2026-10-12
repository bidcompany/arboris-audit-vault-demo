---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-CAPA-012"
section: "Corrective and Preventive Action Management"
requirement_ids:
  - "DOC-08"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/capa"
---

# CHK-CAPA-012

## Audit question

Does each corrective action address the documented root cause?

## Requirement

[[Requirement DOC-08]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-CAPA-012") OR contains(requirement_ids, "DOC-08")
```
