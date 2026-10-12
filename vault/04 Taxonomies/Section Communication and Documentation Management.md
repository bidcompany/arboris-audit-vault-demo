---
type: "taxonomy"
taxonomy: "audit-section"
section: "Communication and Documentation Management"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Communication and Documentation Management

## Findings in the current dataset

- [[AFG-VA-2605 Communication and Documentation Management]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
