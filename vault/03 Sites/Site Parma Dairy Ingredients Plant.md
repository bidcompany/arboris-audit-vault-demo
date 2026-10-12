---
type: "site"
company: "Arboris Foods Group"
site: "Parma Dairy Ingredients Plant"
country: "Italy"
products: "milk powders, whey ingredients and dairy blends"
employees: "286"
synthetic: true
tags:
  - "audit/site"
  - "industry/food-beverage"
---

# Site Parma Dairy Ingredients Plant

## Profile

| Attribute | Value |
|---|---|
| Country | Italy |
| Address | Strada Provinciale 42, Parma, Italy |
| Products | milk powders, whey ingredients and dairy blends |
| Annual volume | 121,000 tonnes |
| Lines | 5 drying and blending lines |
| Employees | 286 |
| Markets | European Union, Middle East and North Africa |
| Certifications | FSSC 22000, ISO 9001, Halal |

## Audits

- [[Audit Parma Dairy Ingredients Plant]]

## Findings at this site

```dataview
TABLE rating AS "Rating", gravity AS "Gravity", section AS "Section", status AS "Status"
FROM "02 Findings"
WHERE site = this.site
SORT choice(rating = "Unsatisfactory", 1, choice(rating = "Major Gaps", 2, choice(rating = "Minor Gaps", 3, 4))) ASC
```
