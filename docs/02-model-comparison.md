# LLM Model Comparison

## Purpose

The purpose of this comparison is to evaluate multiple Large Language Models (LLMs) for a business email automation task.

Rather than selecting a model based on personal preference, each model is evaluated using identical prompts, predefined evaluation criteria, and realistic business communication scenarios.

The selected model will be used to develop the Context-Aware Business Email Assistant.

---

## Compared Models

| Model | Provider | Testing Environment |
|-------|----------|---------------------|
| GPT-5.5 | OpenAI | Codyssey Learning Nato |
| Claude Sonnet 4.6 | Anthropic | Codyssey Learning Nato |
| Gemini 3.1 pro | Google | Codyssey Learning Nato |



**Date Tested** : 2026-07-28

---
## Test Environment

- Platform: Codyssey Learning Nato
- Access Method: Web
- Language: English
- Same prompt used for every model
- Default model settings
- No external tools or reference documents
- Token usage multiplier varied by model according to the Codyssey platform

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

#### Prompt

You are a professional business email assistant.

Write an email based on the following information.

Recipient Role:
Executive (Decision Maker)

Purpose:
Report a possible documentation issue and ask for confirmation.

Situation:
While reviewing the latest version of the user manual, I noticed that the explanation of the Density/Window section may not match the current software interface.

Requirements:
- Briefly explain the issue.
- Ask whether the section has already been updated.
- Offer to revise the document if necessary.
- Do not sound like you are blaming anyone.
- Keep the email concise.

Tone:
Professional, respectful, concise.

Output Format:
Subject

Email

Reasoning (2–3 bullet points explaining why you wrote it this way)

#### GPT-5.5 Result

Subject  
Possible Update Needed: Density/Window Section in User Manual

Email  
Dear [Name],

While reviewing the latest version of the user manual, I noticed that the explanation in the Density/Window section may not fully align with the current software interface.

Could you please confirm whether this section has already been updated or is scheduled for revision? If needed, I would be happy to revise the document accordingly.

Best regards,  
[Your Name]

Reasoning  
- The email raises the issue neutrally without assigning blame.  
- It asks for confirmation before taking action, which is appropriate for an executive decision maker.  
- It remains concise while clearly offering support for the revision.


#### Claude Sonnet 4.6 Result

(여기에 Claude 결과)

#### Gemini 3.1 Pro Result

(여기에 Gemini 결과)

#### Notes

- GPT-5.5: ...
- Claude: ...
- Gemini: ...
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
