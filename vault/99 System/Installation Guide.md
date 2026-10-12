---
type: guide
tags:
  - system/setup
---

# Installation Guide

## Open the vault

1. Extract the ZIP to a local folder.
2. In Obsidian choose **Open folder as vault**.
3. Select the `vault` folder of the repository (or the extracted vault folder).
4. Open [[Start Here]].

## Install community plugins

Go to **Settings > Community plugins**, turn off Restricted Mode and install these plugins individually:

| Plugin | Purpose | Priority |
|---|---|---|
| Dataview | Dynamic tables, task lists and dashboards | Required |
| Omnisearch | Full-text search, including supported attachments | Recommended |
| Smart Connections | Local embeddings and semantic related-note discovery | Recommended |
| Copilot | Chat and retrieval over vault content using configurable model providers | Advanced |
| Templater | Structured creation of new reports and findings | Recommended |
| QuickAdd | Guided capture and repeatable audit workflows | Optional |

Enable Dataview first. The dashboard works as soon as its index has finished.

## Configure folders

- New notes: `00 Inbox`
- Attachments: `90 Attachments`
- Templates: `80 Templates`

## Configure semantic search

1. Enable Smart Connections.
2. Select a local embedding model if supported by your workstation.
3. Index Markdown notes first; exclude `90 Attachments` until data handling has been approved.
4. Test with: `find findings involving weak change control`.

## Configure AI chat

1. Open the Copilot settings.
2. Choose an approved provider. For enterprise use, prefer the corporate Azure OpenAI endpoint or a locally hosted model.
3. Store API keys only in the plugin settings or the approved credential store. Never paste keys into a note.
4. Restrict retrieval to this vault and start with the prompts in [[Prompt Library]].
5. For confidential audits, confirm provider retention, region, access controls and logging before enabling cloud calls.

## Verification

- [[Audit Dashboard]] shows 10 reports and 50 findings.
- The priority table lists all Unsatisfactory and Major Gaps records.
- A site note shows only findings from that site.
- Smart Connections proposes semantically related findings.
- AI responses cite the finding IDs used and distinguish evidence from inference.
