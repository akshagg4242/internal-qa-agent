# Internal QA Agent Setup Guide

## Prerequisites

- n8n installed
- Required credentials configured

---

## Step 1 — Import Workflow

Open n8n.

Select:

Import Workflow

Choose:

workflow/internal-qa-agent-workflow.json

---

## Step 2 — Configure Nodes

Update workflow configuration.

Configure:

- Trigger node
- Response node
- Any credentials required

Save workflow.

---

## Step 3 — Activate Workflow

Enable workflow.

Confirm successful activation.

---

## Step 4 — Test Queries

Example:

Input:

How do I request inventory access?

Expected:

Agent returns configured response.

---

## Step 5 — Verify Execution

Open:

Executions

Confirm successful workflow execution.

---

## Troubleshooting

No response:
- Verify trigger configuration

Workflow failing:
- Check execution logs

Credential issue:
- Reconfigure node credentials

---

## Status

Workflow imported and verified successfully.
