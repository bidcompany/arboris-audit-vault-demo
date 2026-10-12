---
type: "taxonomy"
taxonomy: "audit-section"
section: "Good Manufacturing Practices"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Good Manufacturing Practices

## Findings in the current dataset

- [[AFG-RA-2605 Good Manufacturing Practices]]
- [[AFG-LI-2603 Good Manufacturing Practices]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
