---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-SAN-002"
section: "Cleaning and Sanitation"
requirement_ids:
  - "SAN-09"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/san"
---

# CHK-SAN-002

## Audit question

Are dismantling steps defined for difficult-to-access components?

## Requirement

[[Requirement SAN-09]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-SAN-002") OR contains(requirement_ids, "SAN-09")
```
