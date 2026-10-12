---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-CAPA-018"
section: "Corrective and Preventive Action Management"
requirement_ids:
  - "TRN-10"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/capa"
---

# CHK-CAPA-018

## Audit question

Are overdue actions escalated?

## Requirement

[[Requirement TRN-10]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-CAPA-018") OR contains(requirement_ids, "TRN-10")
```
