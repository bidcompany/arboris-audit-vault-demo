---
type: entity
entity_type: "distributor"
entity_name: "Iberia Chilled Distribution Centre"
country: "Spain"
products: "chilled and ambient finished goods distribution"
synthetic: true
tags:
  - "entity/distributor"
---

# Entity Iberia Chilled Distribution Centre

## Profile

| Attribute | Value |
|---|---|
| Type | Distributor |
| Country | Spain |
| Address | Calle Logistica 18, Zaragoza, Spain |
| Products or services | chilled and ambient finished goods distribution |
| Certifications | ISO 9001, IFS Logistics |

## Audits

```dataview
LIST FROM "01 Reports" WHERE site = this.entity_name
```

## Findings

```dataview
TABLE rating, section, status, recurrence_of FROM "02 Findings" WHERE site = this.entity_name
```
