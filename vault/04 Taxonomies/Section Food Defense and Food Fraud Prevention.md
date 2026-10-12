---
type: "taxonomy"
taxonomy: "audit-section"
section: "Food Defense and Food Fraud Prevention"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# Food Defense and Food Fraud Prevention

## Findings in the current dataset

- [[AFG-VA-2603 Food Defense and Food Fraud Prevention]]
- [[AFG-RT-2602 Food Defense and Food Fraud Prevention]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
