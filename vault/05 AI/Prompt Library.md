---
type: prompt-library
tags:
  - ai/prompts
---

# Prompt Library

## Cross site pattern discovery

Analyze the findings retrieved from this vault and identify recurring control failures across sites. For every pattern, cite the exact finding IDs, distinguish direct evidence from inference, state confidence as high, medium or low, and list evidence that would disprove the pattern. Do not infer facts not present in the notes.

## Root cause quality review

Evaluate whether each recorded root cause explains the observed condition and evidence. Flag circular wording, restated symptoms and unsupported assumptions. Cite the finding ID, explain the weakness and propose questions that an auditor should ask before revising the root cause. Do not replace the approved root cause automatically.

## CAPA adequacy review

Compare each corrective action with its root cause. Classify the action as correction, corrective action or preventive action. Identify actions that do not address the cause, lack measurable effectiveness criteria or depend only on retraining. Cite finding IDs and preserve uncertainty.

## Emerging risk discovery

Search for weak signals shared by at least two findings, even when they belong to different audit sections. Return the signal, supporting evidence, affected sites, plausible risk pathway, alternative explanations and the next evidence to collect.

## Management summary

Create a concise management summary of the selected findings. Separate confirmed facts, interpretation and proposed decisions. Cite every finding ID and do not claim that a risk materialized unless the source explicitly says so.

## Similar finding retrieval

For the current finding, retrieve the five most similar findings. Explain similarity based on observed condition, control mechanism and root cause rather than shared keywords alone. Cite each finding ID.
