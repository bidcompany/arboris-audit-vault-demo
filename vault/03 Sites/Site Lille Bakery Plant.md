---
type: "site"
company: "Arboris Foods Group"
site: "Lille Bakery Plant"
country: "France"
products: "biscuits, filled wafers and cereal bars"
employees: "498"
synthetic: true
tags:
  - "audit/site"
  - "industry/food-beverage"
---

# Site Lille Bakery Plant

## Profile

| Attribute | Value |
|---|---|
| Country | France |
| Address | Parc Industriel Nord 14, Lille, France |
| Products | biscuits, filled wafers and cereal bars |
| Annual volume | 63,800 tonnes |
| Lines | 11 baking and packing lines |
| Employees | 498 |
| Markets | European Union and Switzerland |
| Certifications | BRCGS Food Safety, ISO 9001 |

## Audits

- [[Audit Lille Bakery Plant]]

## Findings at this site

```dataview
TABLE rating AS "Rating", gravity AS "Gravity", section AS "Section", status AS "Status"
FROM "02 Findings"
WHERE site = this.site
SORT choice(rating = "Unsatisfactory", 1, choice(rating = "Major Gaps", 2, choice(rating = "Minor Gaps", 3, 4))) ASC
```
