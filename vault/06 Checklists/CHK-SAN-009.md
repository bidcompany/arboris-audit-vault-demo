---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-SAN-009"
section: "Cleaning and Sanitation"
requirement_ids:
  - "GMP-09"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/san"
---

# CHK-SAN-009

## Audit question

Are cleaning failures escalated and investigated?

## Requirement

[[Requirement GMP-09]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-SAN-009") OR contains(requirement_ids, "GMP-09")
```
