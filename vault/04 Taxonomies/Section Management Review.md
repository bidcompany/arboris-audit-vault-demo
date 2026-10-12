---
type: "taxonomy"
taxonomy: "audit-section"
section: "Management Review"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Management Review

## Findings in the current dataset

- [[AFG-RT-2605 Management Review]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
