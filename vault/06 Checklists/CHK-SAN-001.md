---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-SAN-001"
section: "Cleaning and Sanitation"
requirement_ids:
  - "SAN-05"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/san"
---

# CHK-SAN-001

## Audit question

Does the cleaning plan identify all product-contact and concealed inspection points?

## Requirement

[[Requirement SAN-05]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-SAN-001") OR contains(requirement_ids, "SAN-05")
```
