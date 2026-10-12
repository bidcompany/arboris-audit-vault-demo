---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-CAPA-011"
section: "Corrective and Preventive Action Management"
requirement_ids:
  - "DOC-06"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/capa"
---

# CHK-CAPA-011

## Audit question

Is the root cause distinct from the observed condition?

## Requirement

[[Requirement DOC-06]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-CAPA-011") OR contains(requirement_ids, "DOC-06")
```
