---
type: "taxonomy"
taxonomy: "audit-section"
section: "Calibration and Measuring Equipment"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Calibration and Measuring Equipment

## Findings in the current dataset

- [[AFG-RT-2604 Calibration and Measuring Equipment]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
