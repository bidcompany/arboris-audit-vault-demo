---
type: entity
entity_type: "site"
entity_name: "Parma Dairy Ingredients Plant"
country: "Italy"
products: "milk powders, whey ingredients and dairy blends"
synthetic: true
tags:
  - "entity/site"
---

# Entity Parma Dairy Ingredients Plant

## Profile

| Attribute | Value |
|---|---|
| Type | Site |
| Country | Italy |
| Address | Strada Provinciale 42, Parma, Italy |
| Products or services | milk powders, whey ingredients and dairy blends |
| Certifications | FSSC 22000, ISO 9001, Halal |

## Audits

```dataview
LIST FROM "01 Reports" WHERE site = this.entity_name
```

## Findings

```dataview
TABLE rating, section, status, recurrence_of FROM "02 Findings" WHERE site = this.entity_name
```
