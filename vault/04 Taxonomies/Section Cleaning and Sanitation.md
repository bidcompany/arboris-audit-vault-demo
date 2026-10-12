---
type: "taxonomy"
taxonomy: "audit-section"
section: "Cleaning and Sanitation"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Cleaning and Sanitation

## Findings in the current dataset

- [[AFG-RA-2602 Cleaning and Sanitation]]
- [[AFG-LI-2601 Cleaning and Sanitation]]
- [[AFG-LI-2606 Cleaning and Sanitation]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
