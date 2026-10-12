---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-SAN-004"
section: "Cleaning and Sanitation"
requirement_ids:
  - "SAN-14"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/san"
---

# CHK-SAN-004

## Audit question

Are pre-operational releases completed only after all required checks?

## Requirement

[[Requirement SAN-14]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-SAN-004") OR contains(requirement_ids, "SAN-14")
```
