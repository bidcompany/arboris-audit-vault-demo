---
type: entity
entity_type: "site"
entity_name: "Ravenna Ready Meals Plant"
country: "Italy"
products: "chilled pasta meals, sauces and filled pasta"
synthetic: true
tags:
  - "entity/site"
---

# Entity Ravenna Ready Meals Plant

## Profile

| Attribute | Value |
|---|---|
| Type | Site |
| Country | Italy |
| Address | Via delle Industrie 18, Ravenna, Italy |
| Products or services | chilled pasta meals, sauces and filled pasta |
| Certifications | FSSC 22000, ISO 9001, ISO 14001 |

## Audits

```dataview
LIST FROM "01 Reports" WHERE site = this.entity_name
```

## Findings

```dataview
TABLE rating, section, status, recurrence_of FROM "02 Findings" WHERE site = this.entity_name
```
