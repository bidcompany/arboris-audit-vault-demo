---
type: "taxonomy"
taxonomy: "audit-section"
section: "Rework Management"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Rework Management

## Findings in the current dataset

- [[AFG-RA-2603 Rework Management]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
