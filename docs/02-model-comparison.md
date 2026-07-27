# LLM Model Comparison

## Purpose

The purpose of this comparison is to evaluate multiple Large Language Models (LLMs) for a business email automation task.

Rather than selecting a model based on personal preference, each model is evaluated using identical prompts, predefined evaluation criteria, and realistic business communication scenarios.

The selected model will be used to develop the Context-Aware Business Email Assistant.

---

## Compared Models

| Model | Environment | Plan |
|--------|-------------|------|
| ChatGPT (GPT-5.5) | Web | Plus |
| Claude Sonnet | Web | Pro |
| Gemini 2.5 Pro | Web | Google AI Pro |

**Date Tested**

2026-07-28

---

## Test Environment

- Platform: Web
- Language: English
- Same prompt used for every model
- Default model settings
- No external tools or reference documents

---

## Evaluation Criteria

Each model is evaluated using the following criteria.

| Evaluation Item | Description |
|-----------------|-------------|
| Accuracy | Generates factually correct emails without adding unsupported information |
| Role Adaptation | Adapts writing according to the recipient's role |
| Professional Tone | Uses appropriate business language |
| Structure | Organizes information clearly |
| Clarification Ability | Asks follow-up questions when information is missing |
| Hallucination Prevention | Avoids unsupported assumptions |

Each criterion is scored from **1 (Poor)** to **5 (Excellent)**.

---

## Test Cases

### Test Case 1 — Executive

**Scenario**

Report a possible documentation issue to a company executive.

**Evaluation Focus**

- Prioritizes key information
- Keeps technical details brief
- Clearly requests confirmation
- Avoids sounding accusatory

---

### Test Case 2 — Engineer

**Scenario**

Request technical confirmation regarding the Density/Window section in the user manual.

**Evaluation Focus**

- Mentions document version
- Separates facts from assumptions
- Requests technical confirmation
- Maintains a collaborative tone

---

### Test Case 3 — Exhibition Organizer

**Scenario**

Request information about booth contacts, floor plans, and submission requirements.

**Evaluation Focus**

- Professional communication
- Clear requests
- Appropriate amount of information
- No unnecessary internal details

---

### Test Case 4 — Vendor Follow-up

**Scenario**

Send a polite follow-up email after three business days without a response.

**Evaluation Focus**

- Professional reminder
- Respectful tone
- Concise writing
- Appropriate closing

---

### Test Case 5 — Ambiguous Request

**Scenario**

The user only says:

> "Please write an email."

**Evaluation Focus**

- Requests clarification
- Avoids assumptions
- Collects sufficient information before writing

---

## Score Summary

| Evaluation | ChatGPT | Claude | Gemini |
|------------|---------|---------|---------|
| Accuracy | | | |
| Role Adaptation | | | |
| Professional Tone | | | |
| Structure | | | |
| Clarification Ability | | | |
| Hallucination Prevention | | | |
| Overall | | | |

---

## Final Decision

The final model will be selected based on the overall evaluation results rather than personal preference.

Particular emphasis will be placed on:

- adapting writing strategy according to the recipient's role,
- preventing unsupported assumptions,
- maintaining a professional tone,
- and producing reusable business-quality emails.
