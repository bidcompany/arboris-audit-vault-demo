---
type: entity
entity_type: "supplier"
entity_name: "NorthSea Ingredients Supplier"
country: "Denmark"
products: "frozen seafood ingredients"
synthetic: true
tags:
  - "entity/supplier"
---

# Entity NorthSea Ingredients Supplier

## Profile

| Attribute | Value |
|---|---|
| Type | Supplier |
| Country | Denmark |
| Address | Harbour Park 22, Esbjerg, Denmark |
| Products or services | frozen seafood ingredients |
| Certifications | BRCGS Food Safety, MSC Chain of Custody |

## Audits

```dataview
LIST FROM "01 Reports" WHERE site = this.entity_name
```

## Findings

```dataview
TABLE rating, section, status, recurrence_of FROM "02 Findings" WHERE site = this.entity_name
```
