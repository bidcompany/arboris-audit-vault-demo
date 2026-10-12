---
type: "site"
company: "Arboris Foods Group"
site: "Valencia Beverage Plant"
country: "Spain"
products: "fruit beverages, plant-based drinks and concentrates"
employees: "365"
synthetic: true
tags:
  - "audit/site"
  - "industry/food-beverage"
---

# Site Valencia Beverage Plant

## Profile

| Attribute | Value |
|---|---|
| Country | Spain |
| Address | Avenida de la Industria 77, Valencia, Spain |
| Products | fruit beverages, plant-based drinks and concentrates |
| Annual volume | 216 million litres |
| Lines | 7 aseptic and hot-fill lines |
| Employees | 365 |
| Markets | European Union and Latin America |
| Certifications | FSSC 22000, ISO 9001, ISO 14001 |

## Audits

- [[Audit Valencia Beverage Plant]]

## Findings at this site

```dataview
TABLE rating AS "Rating", gravity AS "Gravity", section AS "Section", status AS "Status"
FROM "02 Findings"
WHERE site = this.site
SORT choice(rating = "Unsatisfactory", 1, choice(rating = "Major Gaps", 2, choice(rating = "Minor Gaps", 3, 4))) ASC
```
