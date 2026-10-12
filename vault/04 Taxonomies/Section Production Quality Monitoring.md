---
type: "taxonomy"
taxonomy: "audit-section"
section: "Production Quality Monitoring"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Production Quality Monitoring

## Findings in the current dataset

No findings in the current dataset.

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
