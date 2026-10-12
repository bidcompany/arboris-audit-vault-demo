---
type: "finding"
finding_id: "AFG-VA-2602"
aliases:
  - "AFG-VA-2602"
company: "Arboris Foods Group"
site: "Valencia Beverage Plant"
country: "Spain"
report: "Audit Valencia Beverage Plant"
audit_period: "2026-06-08 to 2026-06-12"
section: "Product Specifications"
rating: "Major Gaps"
priority: "P1"
gravity: "Priority Finding"
driver: "Packaging specification version control"
status: "Open"
requirement_ids:
  - "DOC-02"
checklist_question_ids:
  - "CHK-DOC-025"
synthetic: true
tags:
  - "audit/finding"
  - "gravity/key-driver"
  - "status/open"
topics:
  - "Product Specifications"
  - "Packaging specification version control"
---

# AFG-VA-2602 Product Specifications

> [!summary] Classification
> **Rating:** Major Gaps  
> **Gravity:** Priority Finding  
> **Status:** Open

## Observed condition

The production-planning interface allowed selection of an obsolete carton artwork for a plant-based drink. The obsolete version did not include the current recycling statement but contained correct ingredient and allergen information.

## Audit evidence

- No obsolete cartons were present in the warehouse.
- The version remained active in the planning dropdown after its effective end date.
- A planner demonstrated that manual verification against the document system was necessary.

## Requirement

AFG Specification Standard 3.7 sections 6.1 and 6.5

## Root cause

The specification repository and planning system were synchronized through a weekly file rather than effective-date controls.

## Corrections

- [ ] Disable obsolete artwork codes and review planned orders  \n  Owner: Lucia Ramos, Packaging Manager  \n  Due: 2026-06-12

## Corrective and preventive actions

- [ ] Implement automated effective-date blocking between systems  \n  Owner: Carlos Esteve, IT Manager  \n  Due: 2026-08-15
- [ ] Review all active packaging codes for version alignment  \n  Owner: Lucia Ramos, Packaging Manager  \n  Due: 2026-07-10

## Connections

[[Audit Valencia Beverage Plant]] · [[Site Valencia Beverage Plant]] · [[Section Product Specifications]]

## AI analysis workspace

Use this section for validated conclusions only. Keep generated hypotheses separate from audit evidence.

- Similar findings:
- Potential systemic pattern:
- Questions for the process owner:
- Validation evidence required:
