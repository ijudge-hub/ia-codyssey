# Adaptive Business Email Assistant using Prompt Engineering

## Project Overview

This project aims to develop an LLM-based business email assistant that automatically adjusts the tone, structure, and content of emails according to the recipient's role and communication context.
Unlike general AI email generators, this assistant analyzes the available communication context, identifies the recipient's role, and generates business emails tailored to the specific situation.
The goal is to improve communication efficiency, reduce unnecessary revisions, and minimize hallucinations.

---

## Problem Statement

Business professionals spend significant time revising emails because communication strategies vary depending on:

- recipient role
- technical knowledge
- organizational relationship
- communication purpose

Existing AI email assistants mainly focus on grammar and fluency, but they often fail to adapt writing strategies to different business contexts. They may also make unsupported assumptions when essential information is missing instead of requesting clarification.

This project addresses these limitations by designing a context-aware prompt engineering workflow that adapts email generation to the recipient's role, avoids unsupported assumptions, and requests clarification whenever essential information is missing.

---

## Project Goals

The assistant should:

- identify the recipient's role
- adjust email tone automatically
- organize information based on business priority
- avoid unsupported assumptions
- request clarification when essential information is missing
- generate consistent, business-quality emails

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
Recipient:
Relationship (optional):
Purpose:
Situation:
Supporting Information:
Desired Outcome:
Special Instructions (optional):
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

### Example 1
Report a documentation issue and request confirmation.

### Example 2
Request technical confirmation before updating documentation.

### Example 3
Handle an incomplete request by asking clarification questions before drafting the email.

---

## Success Criteria

The assistant should:

- adapt email strategy according to recipient role
- maintain professional business tone
- minimize hallucinations by avoiding unsupported information
- ask clarification questions when required
- generate reusable business-quality emails

