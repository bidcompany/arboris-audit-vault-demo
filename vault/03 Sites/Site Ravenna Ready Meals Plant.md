---
type: "site"
company: "Arboris Foods Group"
site: "Ravenna Ready Meals Plant"
country: "Italy"
products: "chilled pasta meals, sauces and filled pasta"
employees: "412"
synthetic: true
tags:
  - "audit/site"
  - "industry/food-beverage"
---

# Site Ravenna Ready Meals Plant

## Profile

| Attribute | Value |
|---|---|
| Country | Italy |
| Address | Via delle Industrie 18, Ravenna, Italy |
| Products | chilled pasta meals, sauces and filled pasta |
| Annual volume | 84,500 tonnes |
| Lines | 9 cooking and packaging lines |
| Employees | 412 |
| Markets | European Union and United Kingdom |
| Certifications | FSSC 22000, ISO 9001, ISO 14001 |

## Audits

- [[Audit Ravenna Ready Meals Plant]]

## Findings at this site

```dataview
TABLE rating AS "Rating", gravity AS "Gravity", section AS "Section", status AS "Status"
FROM "02 Findings"
WHERE site = this.site
SORT choice(rating = "Unsatisfactory", 1, choice(rating = "Major Gaps", 2, choice(rating = "Minor Gaps", 3, 4))) ASC
```
