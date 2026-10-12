---
type: checklist-question
checklist_id: "CHK-MASTER-2027"
question_id: "CHK-DOC-026"
section: "Document Control"
requirement_ids:
  - "GMP-04"
version: "1.0"
status: Current
synthetic: true
tags:
  - "checklist/question"
  - "section/doc"
---

# CHK-DOC-026

## Audit question

Are obsolete references detectable in audit records?

## Requirement

[[Requirement GMP-04]]

## Historical findings

```dataview
LIST FROM "02 Findings" WHERE contains(checklist_question_ids, "CHK-DOC-026") OR contains(requirement_ids, "GMP-04")
```
