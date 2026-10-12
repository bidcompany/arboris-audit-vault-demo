---
type: "taxonomy"
taxonomy: "audit-section"
section: "People Competence Training and Awareness"
synthetic: true
tags:
  - "taxonomy/audit-section"
---

# People Competence Training and Awareness

## Findings in the current dataset

- [[AFG-RA-2604 People Competence Training and Awareness]]
- [[AFG-LI-2604 People Competence Training and Awareness]]

## Dynamic view

```dataview
TABLE site AS "Site", rating AS "Rating", gravity AS "Gravity", status AS "Status"
FROM "02 Findings"
WHERE section = this.section
SORT site ASC
```
