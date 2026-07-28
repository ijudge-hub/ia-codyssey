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

Subject
Possible Update Needed: Density/Window Section in User Manual

---

Email

Dear [Name],

I hope this message finds you well.

While conducting a routine review of the latest user manual, I noticed that the Density/Window section may not fully reflect the current software interface. This could potentially cause confusion for end users.

Could you confirm whether this section has already been updated or is currently under revision? If not, I would be glad to make the necessary corrections at your direction.

Thank you for your time, and please let me know how you would like to proceed.

Best regards,
[Your Name]
[Title / Department]

---

**Reasoning**
- **Neutral framing:** Phrases like *"I noticed"* and *"may not fully reflect"* present the issue as an observation rather than a criticism, keeping the tone collaborative and non-accusatory.
- **Executive-appropriate brevity:** The email respects the recipient's time by delivering only essential information — the issue, a clear question, and an offer to help — without unnecessary detail.
- **Deference to authority:** Closing with *"at your direction"* and *"how you would like to proceed"* reinforces that the executive holds decision-making authority, which is appropriate given their role.

#### Gemini 3.1 Pro Result

안녕하세요! 비즈니스 이메일 작성을 도와드리는 AI 튜터입니다. 

임원(의사결정자)에게 보내는 이메일인 만큼, 예의를 갖추면서도 핵심만 빠르게 파악할 수 있도록 간결하게 작성하는 것이 중요합니다. 요청하신 조건에 맞춰 작성한 이메일 초안입니다.

---

**Subject**
Inquiry Regarding User Manual: Density/Window Section

**Email**
Dear [Name],

While reviewing the latest user manual, I noticed that the information in the Density/Window section appears to differ slightly from the current software interface. 

Could you please let me know if this section has already been updated in a separate draft? If not, I would be happy to revise the document to ensure it accurately reflects the current interface.

Best regards,

[Your Name]  
[Your Title]

---

**Reasoning**
* **부드러운 문제 제기 (No blaming):** "appears to differ slightly(약간 달라 보입니다)"라는 표현을 사용하여 누군가의 실수를 지적하는 느낌을 없애고, 객관적인 관찰 결과로 부드럽게 전달했습니다.
* **임원 맞춤형 간결함 (Concise & Respectful):** 바쁜 의사결정자의 시간을 절약하기 위해 불필요한 배경 설명 없이 '문제 상황 보고 ➔ 업데이트 여부 확인 ➔ 해결책(수정) 제시'의 3단계 구조로 짧고 명확하게 작성했습니다.
* **적극적인 해결책 제시 (Offer to revise):** 단순히 문제를 보고하는 것에 그치지 않고, 필요시 직접 문서를 수정하겠다는 의지("I would be happy to revise~")를 보여주어 프로페셔널하고 책임감 있는 인상을 줍니다.


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
