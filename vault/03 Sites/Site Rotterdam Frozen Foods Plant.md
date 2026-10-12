---
type: "site"
company: "Arboris Foods Group"
site: "Rotterdam Frozen Foods Plant"
country: "Netherlands"
products: "frozen vegetables, coated seafood and prepared side dishes"
employees: "441"
synthetic: true
tags:
  - "audit/site"
  - "industry/food-beverage"
---

# Site Rotterdam Frozen Foods Plant

## Profile

| Attribute | Value |
|---|---|
| Country | Netherlands |
| Address | Maashaven 212, Rotterdam, Netherlands |
| Products | frozen vegetables, coated seafood and prepared side dishes |
| Annual volume | 97,300 tonnes |
| Lines | 8 preparation, freezing and packing lines |
| Employees | 441 |
| Markets | European Union, United Kingdom and Scandinavia |
| Certifications | FSSC 22000, ISO 9001, MSC Chain of Custody |

## Audits

- [[Audit Rotterdam Frozen Foods Plant]]

## Findings at this site

```dataview
TABLE rating AS "Rating", gravity AS "Gravity", section AS "Section", status AS "Status"
FROM "02 Findings"
WHERE site = this.site
SORT choice(rating = "Unsatisfactory", 1, choice(rating = "Major Gaps", 2, choice(rating = "Minor Gaps", 3, 4))) ASC
```
