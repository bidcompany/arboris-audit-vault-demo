---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-CAPA-019"
section: "Corrective and Preventive Action Management"
requirement_ids:
  - "SAN-05"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/capa"
---

# CHK-CAPA-019

## Audit question

Are recurring findings linked to prior CAPAs?

## Requirement

[[Requirement SAN-05]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-CAPA-019") OR contains(requirement_ids, "SAN-05")
```
