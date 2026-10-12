---
type: auditor
auditor_id: "AUD-001"
name: "Laura Conti"
role: "Lead Auditor"
scope:
  - "Manufacturing"
  - "Supplier"
synthetic: true
tags:
  - "audit/person"
---

# Auditor Laura Conti

## Profile

Role: **Lead Auditor**  
Qualified scope: Manufacturing, Supplier

## Audits

```dataview
LIST FROM "01 Reports" WHERE contains(auditor_ids, "AUD-001")
```
