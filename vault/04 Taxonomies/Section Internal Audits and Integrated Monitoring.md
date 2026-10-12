---
type: "taxonomy"
taxonomy: "audit-section"
section: "Internal Audits and Integrated Monitoring"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Internal Audits and Integrated Monitoring

## Findings in the current dataset

- [[AFG-PR-2606 Internal Audits and Integrated Monitoring]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
