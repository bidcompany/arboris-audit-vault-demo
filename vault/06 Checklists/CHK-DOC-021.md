---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-DOC-021"
section: "Document Control"
requirement_ids:
  - "SAN-11"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/doc"
---

# CHK-DOC-021

## Audit question

Does every controlled document show owner, version and effective date?

## Requirement

[[Requirement SAN-11]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-DOC-021") OR contains(requirement_ids, "SAN-11")
```
