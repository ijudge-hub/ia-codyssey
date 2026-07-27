# Adaptive Business Email Assistant using Prompt Engineering

## Project Overview

This project aims to develop an LLM-based business email assistant that automatically adjusts the tone, structure, and content of emails according to the recipient's role and communication context.

Unlike general AI email generators, this assistant analyzes who the recipient is before generating an email. The same business situation should produce different emails depending on whether the recipient is an executive, engineer, client, or external organizer.

The goal is to improve communication efficiency while reducing unnecessary revisions and preventing hallucinated information.

---

## Problem Statement

Business professionals spend significant time revising emails because communication style changes depending on:

- recipient role
- technical knowledge
- organizational relationship
- communication purpose

Existing AI assistants mainly focus on grammar and fluency, but they often fail to adapt the email strategy to different business contexts.

This project addresses that limitation by designing a context-aware prompt engineering workflow.

---

## Project Goals

The assistant should:

- identify recipient type
- adjust email tone automatically
- organize information based on business priority
- avoid unsupported assumptions
- request clarification when information is missing
- generate reusable business-quality emails

---
## Target Users

This assistant is designed for professionals who regularly communicate through business emails, including:

- Project managers
- Designers
- Engineers
- Sales representatives
- Professionals communicating with international partners
- Employees who need to write English business emails

---

## Input Template

The assistant receives structured information before generating an email.

```text
Recipient Type:
Relationship:
Purpose:
Situation:
Required Information:
Desired Action:
Tone:
Urgency:
Constraints:
```

---

## Expected Output

The assistant generates:

1. Email Subject
2. Email Body
3. Recommended Writing Strategy
4. Missing Information (if clarification is needed)

---

## Example Business Scenarios

Scenario 1
Reporting a document issue to an executive.

Scenario 2
Requesting technical confirmation from an engineer.

Scenario 3
Asking an exhibition organizer about submission requirements.

Scenario 4
Following up with an external vendor.

---

## Success Criteria

The assistant should:

- adapt email strategy according to recipient role
- maintain professional business tone
- avoid hallucinated facts
- ask clarification questions when required
- generate reusable business-quality emails
