---
type: "taxonomy"
taxonomy: "audit-section"
section: "Utilities and Maintenance"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Utilities and Maintenance

## Findings in the current dataset

- [[AFG-PR-2601 Utilities and Maintenance]]
- [[AFG-PR-2603 Utilities and Maintenance]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
