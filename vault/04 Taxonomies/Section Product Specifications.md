---
type: "taxonomy"
taxonomy: "audit-section"
section: "Product Specifications"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Product Specifications

## Findings in the current dataset

- [[AFG-VA-2602 Product Specifications]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
