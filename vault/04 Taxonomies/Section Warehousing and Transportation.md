---
type: "taxonomy"
taxonomy: "audit-section"
section: "Warehousing and Transportation"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Warehousing and Transportation

## Findings in the current dataset

- [[AFG-VA-2604 Warehousing and Transportation]]
- [[AFG-RT-2603 Warehousing and Transportation]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
