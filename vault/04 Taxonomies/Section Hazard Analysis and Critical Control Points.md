---
type: "taxonomy"
taxonomy: "audit-section"
section: "Hazard Analysis and Critical Control Points"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Hazard Analysis and Critical Control Points

## Findings in the current dataset

- [[AFG-RA-2601 Hazard Analysis and Critical Control Points]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
