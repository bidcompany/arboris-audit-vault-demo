---
type: dashboard
tags:
  - dashboard/use-cases
---

# Use Case Validation Dashboard

## Dataset scope

**10 audit reports** · **50 findings** · **40 checklist questions** · **6 controlled document families** · **10 CAPA closure records** · **10 closure evidence records** · **5 lessons learned**

## Recurring findings

```dataview
TABLE site, section, rating, recurrence_of FROM "02 Findings" WHERE recurrence_of != ""
```

## Closed CAPAs and effectiveness

```dataview
TABLE finding_id, closure_date, effectiveness_result, evidence_id FROM "09 CAPAs" SORT closure_date DESC
```

## Checklist coverage

```dataview
TABLE section, requirement_ids FROM "06 Checklists" WHERE type = "checklist-question" GROUP BY section
```

## Current controlled documents

```dataview
TABLE document_id, version, effective_date, applicability FROM "08 Controlled Documents" WHERE status = "Current"
```

## Lessons learned

```dataview
TABLE area, related_findings FROM "11 Lessons Learned"
```

## Entity overview

```dataview
TABLE entity_type, country, products FROM "13 Entities"
```
