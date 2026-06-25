# Internal QA Agent Setup Guide

## Prerequisites

- n8n installed
- Access to Google Sheets
- Required workflow credentials

---

## Step 1 — Import Workflow

Open n8n.

Select:

Import Workflow

Choose:

workflow/internal-qa-agent-workflow.json

---

## Step 2 — Configure FAQ Dataset

Open:

data/internal-faqs.xlsx

Review:

- Question
- Answer
- Category

Update sample records if required.

---

## Step 3 — Connect Data Source

Configure the workflow to read the FAQ sheet.

Update:

- Spreadsheet source
- Sheet selection
- Access permissions

Save workflow.

---

## Step 4 — Configure Workflow Nodes

Verify:

- Trigger node
- Processing node
- Response node

Save changes.

---

## Step 5 — Activate Workflow

Enable workflow.

Confirm successful activation.

---

## Step 6 — Test Query

Example:

Input:

How do I request inventory access?

Expected:

Agent returns matching FAQ response.

---

## Step 7 — Verify Execution

Open:

Executions

Confirm successful workflow execution.

---

## Troubleshooting

No reply:
- Verify workflow activation

FAQ not loading:
- Verify sheet connection

Execution failed:
- Review execution logs

---

## Status

Workflow imported and verified successfully.
