---
type: finding
finding_id: "AFG-IB-2701"
aliases:
  - "AFG-IB-2701"
company: "Arboris Foods Group"
site: "Iberia Chilled Distribution Centre"
entity_type: "distributor"
report: "Audit Iberia Chilled Distribution Centre"
audit_period: "2027-11-08 to 2027-11-10"
section: "Warehousing and Transportation"
rating: "Major Gaps"
priority: "P1"
gravity: "Priority Finding"
driver: "Alarm escalation during night shift"
status: Open
requirement_ids:
  - "LOG-04"
checklist_question_ids:
  - "CHK-CAPA-017"
recurrence_of: ""
auditor_ids:
  - "AUD-003"
  - "AUD-004"
synthetic: true
tags:
  - "audit/finding"
  - "status/open"
---

# AFG-IB-2701 Warehousing and Transportation

## Observed condition

A cold-room alarm remained acknowledged but unresolved for 47 minutes because the night-shift escalation list contained an obsolete telephone number.

## Audit evidence

- Product temperature remained within specification.
- The backup contact responded after manual escalation.
- The list had not been tested during the previous quarter.

## Requirement

[[Requirement LOG-04]]

## Root cause

The quarterly call-tree test was recorded as a document review rather than a live challenge.

## Corrections

- [ ] Correct and test all contacts  
  Owner: Luis Ortega, Distribution Manager  
  Due: 2027-11-08

## Corrective and preventive actions

- [ ] Introduce quarterly live alarm challenges  
  Owner: Ines Vidal, Quality Manager  
  Due: 2027-12-15

## Connections

[[Audit Iberia Chilled Distribution Centre]] · [[Entity Iberia Chilled Distribution Centre]] · [[Section Warehousing and Transportation]] · [[CHK-CAPA-017]]
