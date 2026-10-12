---
type: "taxonomy"
taxonomy: "audit-section"
section: "Pest Control"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Pest Control

## Findings in the current dataset

- [[AFG-LI-2602 Pest Control]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
