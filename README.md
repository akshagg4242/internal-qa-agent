# Internal QA Agent

Status: Completed and verified.

---

## Overview

Internal QA Agent is an n8n-based automation workflow that answers basic internal questions and supports workflow guidance.

The agent is designed for simple internal support and response automation.

---

## Features

- Internal Q&A
- Automated replies
- Workflow assistance
- Simple query handling

---

## Technologies Used

- n8n
- Automation

---

## Repository Structure

```text
internal-qa-agent/
├── workflow/
├── screenshots/
├── docs/
└── README.md
```

---

## Knowledge Source

The agent uses a structured FAQ dataset stored in:

```text
data/internal-faqs.xlsx
```

This sheet acts as the reference source for answering internal queries.

Example fields:

- Question
- Answer
- Category

Sensitive or real organizational data has been excluded.

## Workflow

User Question

↓

n8n Workflow
↓

Response Processing

↓

Generated Reply

---

## Import Workflow

Open n8n:

Import Workflow
→ Select JSON
→ Configure credentials
→ Execute

---

## Screenshots

See `/screenshots`

---

## Status

Workflow tested successfully.
