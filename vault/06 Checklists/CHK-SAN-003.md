---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-SAN-003"
section: "Cleaning and Sanitation"
requirement_ids:
  - "SAN-11"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/san"
---

# CHK-SAN-003

## Audit question

Is cleaning frequency based on product and equipment risk?

## Requirement

[[Requirement SAN-11]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-SAN-003") OR contains(requirement_ids, "SAN-11")
```
