# Arboris Audit Vault: Obsidian demo

An Obsidian vault that shows how a set of audit reports can be turned into a **navigable, AI-ready knowledge base**. You can browse findings by site and control domain, follow recurring issues and CAPAs, and run evidence-based AI analysis over the whole corpus.

> **All data is synthetic.** *Arboris Foods Group*, its sites, people, findings and dates are fictional. They were created only for demonstration and testing.

---

## What's inside

| Item | Count |
|---|---|
| Audit reports (2026 periodic audits, 2027 follow-ups, supplier and distributor audits) | 10 |
| Atomic finding notes | 50 |
| Sites and external entities | 5 + 2 |
| Audit-section taxonomy | 24 control domains |
| Checklist questions / requirements | 40 / 25 |
| Controlled documents (6 families, 2 versions each) | 12 |
| CAPAs / closure evidence / lessons learned | 10 / 10 / 5 |

### Source reports

| # | Entity | Audit type | Period | Findings |
|---|---|---|---|---|
| 01 | Ravenna Ready Meals Plant | Periodic on-site | Apr 2026 | 6 |
| 02 | Parma Dairy Ingredients Plant | Periodic on-site | May 2026 | 6 |
| 03 | Valencia Beverage Plant | Periodic on-site | Jun 2026 | 6 |
| 04 | Lille Bakery Plant | Periodic on-site | Jul 2026 | 6 |
| 05 | Rotterdam Frozen Foods Plant | Periodic on-site | Aug 2026 | 6 |
| 06 | Ravenna Ready Meals Plant | Targeted follow-up | Jun 2027 | 4 |
| 07 | Lille Bakery Plant | Targeted follow-up | Aug 2027 | 4 |
| 08 | Parma Dairy Ingredients Plant | Targeted follow-up | Sep 2027 | 4 |
| 09 | NorthSea Ingredients Supplier | Supplier approval | Oct 2027 | 4 |
| 10 | Iberia Chilled Distribution Centre | Distributor surveillance | Nov 2027 | 4 |

The reports use the **Audit Review V2** rating model, with four ratings: `Satisfactory`, `Minor Gaps`, `Major Gaps` and `Unsatisfactory`.

## Repository structure

```
.
├── source-reports/          # The 10 original Word reports (V2): the starting point of the demo
├── vault/                   # The Obsidian vault: open THIS folder in Obsidian
│   ├── 00 Home/             # Start Here, Audit Dashboard, Use Case Validation Dashboard
│   ├── 00 Inbox/            # Default location for new notes
│   ├── 01 Reports/          # One note per audit report
│   ├── 02 Findings/         # One atomic note per finding (frontmatter + actions)
│   ├── 03 Sites/            # Site profiles
│   ├── 04 Taxonomies/       # Audit sections / control domains
│   ├── 05 AI/               # AI Analysis Guide and Prompt Library
│   ├── 06 Checklists/       # Master checklist and checklist questions
│   ├── 07 Requirements/     # Requirements referenced by findings
│   ├── 08 Controlled Documents/
│   ├── 09 CAPAs/
│   ├── 10 Closure Evidence/
│   ├── 11 Lessons Learned/
│   ├── 12 Auditors/
│   ├── 13 Entities/         # Plants, supplier, distributor
│   ├── 80 Templates/        # Templates for new reports and findings
│   ├── 90 Attachments/      # Copy of the source reports, linked from the vault
│   └── 99 System/           # Installation guide, security policy, finding catalogue (JSON)
└── docs/
    └── DEMO_GUIDE.md        # Suggested demo walkthrough
```

## Quick start

1. **Clone or download** this repository (*Code → Download ZIP*).
2. In Obsidian, choose **Open folder as vault** and select the `vault/` folder.
3. Go to **Settings → Community plugins**, turn off Restricted Mode and install **Dataview** (required).
4. Open `00 Home/Start Here.md`, then the **Audit Dashboard**.

Optional plugins: Omnisearch, Smart Connections, Copilot, Templater and QuickAdd. The full setup, including semantic search and AI chat, is in [`vault/99 System/Installation Guide.md`](vault/99%20System/Installation%20Guide.md).

### Check that it works

- The Audit Dashboard shows 10 reports and 50 findings.
- The *Priority findings* table lists every `Unsatisfactory` and `Major Gaps` record.
- Opening a site note shows only that site's findings, through backlinks.

## What the demo shows

- **From documents to knowledge.** Unstructured Word reports become linked, queryable notes with consistent metadata.
- **Cross-site analysis.** Findings can be grouped by control domain, recurrences tracked between the 2026 audits and the 2027 follow-ups, and patterns seen in the graph.
- **CAPA lifecycle.** The vault links findings, corrective actions, closure evidence, effectiveness checks and lessons learned.
- **Grounded AI analysis.** The prompts in the Prompt Library ask the model to cite finding IDs and keep evidence separate from inference.
- **Governance by design.** Green/Amber/Red data tiers and controls are defined before any real data is used. See [`Security and Data Handling`](vault/99%20System/Security%20and%20Data%20Handling.md).

For a step-by-step walkthrough, see [`docs/DEMO_GUIDE.md`](docs/DEMO_GUIDE.md).

## Notes

- `vault/99 System/finding-catalogue.json` is a machine-readable index of all 50 findings. Use it for scripts, imports or evaluation.
- Personal Obsidian state (`workspace.json`, caches, installed plugin binaries) is excluded via `.gitignore`. Each user installs plugins locally.
- The architecture also works for real audit reports. Before importing confidential material, define and approve the controls in the security note.

---

*Built by BID Company (DGS Group), Data & AI division.*
