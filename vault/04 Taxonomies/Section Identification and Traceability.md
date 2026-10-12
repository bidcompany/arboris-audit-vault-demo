---
type: "taxonomy"
taxonomy: "audit-section"
section: "Identification and Traceability"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Identification and Traceability

## Findings in the current dataset

- [[AFG-VA-2601 Identification and Traceability]]
- [[AFG-VA-2606 Identification and Traceability]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
