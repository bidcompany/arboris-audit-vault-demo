# Demo guide: navigating the Audit Vault in Obsidian

**Arboris Foods Group** · Version 1.0 · October 2026

This guide walks you through presenting the dashboards, findings, local graph, relationships and AI-assisted analysis, step by step.

---

## Purpose of this guide

This guide lets you run a repeatable demonstration of the Audit Vault. The path starts from the dashboard, opens a finding, navigates its relationships and ends with a controlled example of AI analysis.

The main message: transactional systems can stay authoritative, while the Vault makes audit knowledge easier to find, connect and reuse.

### Recommended duration

| Format | Duration | Use |
|---|---|---|
| **Essential path** | 12–15 minutes | First presentation to the client |
| **Extended path** | 25–30 minutes | Deep dive with auditors and methodology owners |

---

## 1. Preparation before the demo

1. Start Obsidian and open the `vault/` folder of this repository as a vault. It is the folder that directly contains `00 Home`, `01 Reports` and `02 Findings`.
2. Open **Settings** and check that these community plugins are enabled: **Dataview**, **Copilot**, **Smart Connections**, **Omnisearch** and **Templater**.
3. Check that the core plugin **Graph view** is enabled.
4. Wait for Smart Connections and Copilot to finish indexing before you share your screen.
5. Open `00 Home` and select **Use Case Validation Dashboard**.
6. Close personal files and turn off notifications. Use the synthetic dataset for the whole demo.

### Quick checks

| Check | Expected result | If it doesn't work |
|---|---|---|
| **Dashboard** | Queries show tables, not code | Enable Dataview and reopen the note |
| **Dataset** | 10 audits and 50 findings | Make sure you opened the correct inner folder |
| **Local graph** | The command is available on the note | Enable Graph view in the core plugins |
| **Copilot** | AI panel available on the right | Check the provider, model and credentials |

### Useful shortcuts

On macOS, use `Cmd` instead of `Ctrl` and `Cmd [` instead of `Alt ←`.

| Shortcut | Function |
|---|---|
| `Ctrl P` | Opens the command palette |
| `Ctrl Shift F` | Global search in the vault |
| `Ctrl` + click | Opens a link from edit mode |
| `Alt ←` | Goes back to the previous note |

---

## 2. Finding your way around the Vault

The left sidebar represents the knowledge model. You don't need to open every folder. During the demo, it is enough to show that each type of information has a consistent place.

| Folder | Contents | Use in the demo |
|---|---|---|
| **00 Home** | Dashboards and entry point | Start of the demo |
| **01 Reports** | Ten audits and their metadata | From report to findings |
| **02 Findings** | Fifty structured findings | Central object of navigation |
| **03 Sites** and **13 Entities** | Production sites and external entities | Historical view by entity |
| **04 Taxonomies** | Control domains and areas | Cross-cutting analysis |
| **06 Checklists** and **07 Requirements** | Questions and requirements | Methodological traceability |
| **08 Controlled Documents** | Documents and versions | Impact analysis |
| **09 CAPAs** and **10 Closure Evidence** | Actions and evidence of effectiveness | Closure and follow-up |
| **11 Lessons Learned** | Reusable knowledge | Transfer of learning |

> 💬 **Talking point:** The Vault is not a new document folder. It is a knowledge layer that connects audits, findings, requirements, actions and evidence.

### View modes

- Use **Reading view** to present notes to the client.
- Use **Source mode** or **Live Preview** only when you need to update the *AI analysis workspace*.
- If a link doesn't open with a click, use `Ctrl` + click or switch to Reading view.

---

## 3. Main demo path

### Step 1: Open the dashboard

1. Expand `00 Home`.
2. Open **Use Case Validation Dashboard**.
3. Show the scope: 10 audits, 50 findings, checklists, requirements, controlled documents, CAPAs and evidence.
4. Scroll through the queries *Recurring findings*, *Closed CAPAs and effectiveness* and *Lessons learned*.

> 💬 **Talking point:** We start from a synthetic but realistic body of knowledge. The dashboard contains no hand-copied data. It aggregates the structured notes in the Vault.

### Step 2: Open an audit

1. Open `01 Reports`.
2. Select **Audit Parma Dairy Ingredients Plant**.
3. Read the summary, the period, the audit type and the number of findings.
4. In the **Findings** section, open **AFG-PR-2601**.

> 💬 **Talking point:** We go down from the report to a single finding and keep the context of the entity and the source audit.

### Step 3: Read the finding

- **Observed condition:** what was observed.
- **Audit evidence:** the objective evidence collected.
- **Requirement:** the applicable requirement.
- **Root cause:** the identified cause.
- **Corrections** and **Corrective and preventive actions:** what will be done, by whom and by when.
- **Connections:** links to the report, the site and the control domain.

> 💬 **Talking point:** The finding is no longer just a paragraph in a Word file. It becomes a knowledge object you can navigate and compare.

---

## 4. Navigating links and the local graph

### Follow the links

1. Stay on note **AFG-PR-2601**.
2. Scroll down to the **Connections** section.
3. In Reading view, click **Audit Parma Dairy Ingredients Plant** or **Site Parma Dairy Ingredients Plant**.
4. Press `Alt ←` to go back to the finding.

### Open the local graph

1. With the finding open, click the three dots in the top-right corner.
2. Hover over **Open linked view**.
3. Select **Open local graph**.
4. Alternatively, press `Ctrl P`, search for *local graph* and select **Graph view: Open local graph**.
5. Open the graph settings. Set depth to 2, turn incoming and outgoing links on, and turn tags and attachments off.
6. If you want to keep the finding in the centre, drag the graph tab into the right sidebar.

> ⚠️ The local graph always starts from the note that is currently open. If you launch it from the dashboard, it shows the dashboard's links, not the finding's.

> 💬 **Talking point:** Starting from a single finding, I can explore its context without knowing the folders or document names in advance.

### How to read the graph

- **Central node:** the finding that is currently open.
- **First level:** the report, site, domain and other direct links.
- **Second level:** indirectly linked objects, such as other findings or methodology content.
- **Double-click on a node:** opens the corresponding note.

---

## 5. Search and dynamic tables

### Text search

1. Press `Ctrl Shift F`.
2. Search for `backflow prevention` or `utility control`.
3. Open the relevant results and compare their evidence and actions.
4. Explain that Omnisearch improves retrieval even when you don't know the exact title.

### Dataview

Dataview builds tables by querying note metadata. The query is visible in edit mode and the result appears in Reading view. During the demo, show the result, not the code, unless someone asks a technical question.

| View | What it demonstrates |
|---|---|
| **Recurring findings** | Identifies recurrences linked to earlier findings |
| **Closed CAPAs and effectiveness** | Distinguishes a completed action from verified effectiveness |
| **Checklist coverage** | Links questions to requirements |
| **Current controlled documents** | Separates current versions from superseded ones |

> 💬 **Talking point:** The dashboards are a view on the knowledge base. If I add a well-structured audit, the aggregations update without rebuilding the report by hand.

### Smart Connections

Use it as an exploration aid that suggests semantically similar notes. Do not present similarity as evidence. Always open the suggested notes and compare the original evidence.

---

## 6. AI analysis workspace demonstration

Every finding has an *AI analysis workspace* section. It does not start the AI automatically and it does not change the record by itself. It holds only the conclusions the auditor has verified.

### Step 1: Prepare the context

1. Open **AFG-PR-2601 Utilities and Maintenance**.
2. Open **Copilot** in the right sidebar.
3. If available, select the mode that uses the current note or the vault as context.
4. Check that indexing has finished.

### Step 2: Run the prompt

```text
Analyze the current finding using the connected notes in the vault.

Provide:
1. Similar findings, including finding IDs
2. Potential systemic pattern
3. Questions for the process owner
4. Evidence required to validate or close the finding

Separate facts found in the vault from hypotheses.
Do not invent evidence.
```

### Step 3: Verify the answer

- Open every cited finding and check that the ID exists.
- Check that the statements are supported by the notes.
- Keep evidence, interpretations and hypotheses separate.
- Remove references that can't be verified.
- Do not let the AI assign the final rating or approve a closure.

---

## 7. Example to add to the finding

After verification, switch to Live Preview or Source mode. Replace the empty bullet points under *AI analysis workspace* with the following text.

```markdown
## AI analysis workspace

### Similar findings
- [[AFG-PR-2701]] — temporary utility bypass control
- [[AFG-RT-2604]] — calibration and measuring equipment

### Potential systemic pattern
Engineering changes and temporary configurations are not always routed
through a complete Quality approval and verification process.

### Questions for the process owner
- Which utility changes require prior Quality approval?
- How are expired temporary permits escalated?
- Are equivalent connections present at other sites?

### Validation evidence required
- Updated utility asset register
- Backflow prevention test certificates
- Approved change-control records
- Evidence from equivalent connection inspections
```

The example is written as working analysis. Before you save it as a validated conclusion, check in the Vault that the two cited findings are relevant to the question. Remove any links the evidence does not support.

> 💬 **Talking point:** The AI produces a first cross-cutting reading. The auditor opens the sources, validates the links and saves only what they consider supported. AI output does not automatically become audit evidence.

### A more cautious option for the demo

Leave the section empty at first, run the prompt live and move a single verified item into the workspace. This shows human control concretely, without depending on the quality of a long answer.

---

## 8. 15-minute demo script

| Time | Action | Message |
|---|---|---|
| **0:00–1:30** | Open the dashboard | From isolated documents to connected audit knowledge |
| **1:30–3:00** | Show scope and queries | Ten audits and fifty findings, aggregated dynamically |
| **3:00–5:30** | Open the Parma audit and AFG-PR-2601 | The finding keeps its context, evidence, requirement and actions |
| **5:30–7:30** | Navigate Connections | Relationships remove manual searching across files |
| **7:30–9:30** | Open the local graph | The graph guides the discovery of context |
| **9:30–12:30** | Run the AI prompt | AI retrieves and compares, but does not decide |
| **12:30–14:00** | Verify and update the workspace | Human in the loop and traceability |
| **14:00–15:00** | Close on the target architecture | ServiceNow stays the system of record; the Vault adds value to the knowledge |

### Suggested opening

> 💬 **Talking point:** Today we will show how to move from separate reports, findings and attachments to audit knowledge you can navigate and query. The Vault does not replace the system of record or the auditor's professional judgement.

### Suggested close

> 💬 **Talking point:** The value is not in moving documents to a new repository. It is in turning audit history into operational memory, so that every new audit starts from what the organisation has already observed, corrected and verified.

---

## 9. Rules to state to the client

- The Vault is a knowledge layer, not the authoritative transactional system.
- ServiceNow or the corporate platform can keep managing workflows, responsibilities, deadlines and approvals.
- AI answers must be traceable to the notes and verified by a qualified person.
- AI must not approve CAPAs, close findings or assign the final rating on its own.
- Authorisations, retention and data segregation must be defined in the enterprise architecture.
- All Arboris data is synthetic and intended for demonstration only.

### Closing questions for the client

- Which use case would most reduce preparation or review time?
- Which system should remain authoritative for findings and actions?
- Which documents and metadata would a pilot need?
- What evidence would be needed to validate the approach against the Audit methodology?

### Contingency plan

| Problem | Response during the demo |
|---|---|
| **Copilot doesn't respond** | Show the prompt and use the pre-validated example in this guide |
| **A query doesn't render** | Switch to Reading view, check Dataview and open the relevant folder directly |
| **The graph is too crowded** | Use the local graph with depth 1 or 2 |
| **Smart Connections suggests weak results** | Open only pre-verified cases and make clear that similarity is exploratory |
