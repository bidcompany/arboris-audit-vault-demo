---
type: entity
entity_type: "site"
entity_name: "Lille Bakery Plant"
country: "France"
products: "baked snacks, cereal bars and filled biscuits"
synthetic: true
tags:
  - "entity/site"
---

# Entity Lille Bakery Plant

## Profile

| Attribute | Value |
|---|---|
| Type | Site |
| Country | France |
| Address | 14 Rue de l'Industrie, Lille, France |
| Products or services | baked snacks, cereal bars and filled biscuits |
| Certifications | BRCGS Food Safety, ISO 9001 |

## Audits

```dataview
LIST FROM "01 Reports" WHERE site = this.entity_name
```

## Findings

```dataview
TABLE rating, section, status, recurrence_of FROM "02 Findings" WHERE site = this.entity_name
```
