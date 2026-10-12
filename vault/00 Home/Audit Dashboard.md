---
type: dashboard
tags:
  - dashboard/audit
---

# Audit Dashboard

> [!summary] Current synthetic dataset
> **10 reports** · **50 findings** · **5 sites plus 2 external entities**

## Reports

```dataview
TABLE site AS "Entity", audit_period AS "Audit period", audit_type AS "Audit type", finding_count AS "Findings"
FROM "01 Reports"
SORT audit_period ASC
```

## Priority findings

```dataview
TABLE site AS "Entity", section AS "Control domain", rating AS "Area rating", priority AS "Priority", status AS "Status"
FROM "02 Findings"
WHERE rating = "Unsatisfactory" OR rating = "Major Gaps"
SORT choice(rating = "Unsatisfactory", 1, 2) ASC, site ASC
```

## Open actions

```dataview
TASK
FROM "02 Findings"
WHERE !completed
GROUP BY file.link
```

## Patterns by control domain

```dataview
TABLE length(rows) AS "Findings", rows.site AS "Entities", rows.rating AS "Ratings"
FROM "02 Findings"
GROUP BY section
SORT length(rows) DESC
```

## AI workspace

- [[AI Analysis Guide]]
- [[Prompt Library]]
- [[Security and Data Handling]]
