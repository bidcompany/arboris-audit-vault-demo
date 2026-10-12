---
type: "taxonomy"
taxonomy: "audit-section"
section: "Supplier and Incoming Material Management"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Supplier and Incoming Material Management

## Findings in the current dataset

- [[AFG-PR-2605 Supplier and Incoming Material Management]]
- [[AFG-RT-2601 Supplier and Incoming Material Management]]
- [[AFG-RT-2606 Supplier and Incoming Material Management]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
