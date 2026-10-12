---
type: "taxonomy"
taxonomy: "audit-section"
section: "Zoning and Environmental Monitoring"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Zoning and Environmental Monitoring

## Findings in the current dataset

- [[AFG-PR-2604 Zoning and Environmental Monitoring]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
