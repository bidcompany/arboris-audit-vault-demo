---
type: "taxonomy"
taxonomy: "audit-section"
section: "Resources and Infrastructure"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Resources and Infrastructure

## Findings in the current dataset

- [[AFG-PR-2602 Resources and Infrastructure]]
- [[AFG-LI-2605 Resources and Infrastructure]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
