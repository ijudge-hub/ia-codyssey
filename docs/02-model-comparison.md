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
**Prompt**

Request technical confirmation regarding the Density/Window section in the user manual.

**Evaluation Focus**

- Mentions document version
- Separates facts from assumptions
- Requests technical confirmation
- Maintains a collaborative tone

*** Prompt
 You are a professional business email assistant.

Write an email based on the following information.

Recipient Role:
Software Engineer

Purpose:
Request technical confirmation regarding the Density/Window section in the user manual.

Situation:
While reviewing version 3.11.8.1 of the user manual, I noticed that the explanation of the Density/Window section may not match the current software behavior.

Requirements:
- Mention the document version.
- Clearly separate confirmed facts from assumptions.
- Ask for technical confirmation.
- Maintain a collaborative and respectful tone.

Tone:
Professional, collaborative, concise.

Output Format:
Subject

Email

Reasoning (2–3 bullet points explaining why you wrote it this way) 

#### GPT-5.5 Result
Subject

Density/Window 섹션 관련 기술 확인 요청 — User Manual v3.11.8.1

Email

안녕하세요,

User Manual v3.11.8.1을 검토하던 중, Density/Window 섹션의 설명이 현재 소프트웨어 동작과 일부 일치하지 않을 가능성이 있어 기술 확인을 요청드립니다.

확인된 사항:
- 검토 대상 문서는 User Manual v3.11.8.1입니다.
- Density/Window 섹션의 설명을 검토하는 과정에서 현재 소프트웨어 동작과 차이가 있어 보이는 부분을 발견했습니다.

가정 사항:
- 해당 섹션의 설명이 이전 버전의 동작을 기준으로 작성되었을 가능성이 있습니다.
- 또는 현재 소프트웨어 동작이 의도된 변경 사항이나 업데이트 결과일 수 있습니다.

가능하시다면 Density/Window 섹션의 설명이 현재 소프트웨어 동작과 일치하는지 기술적으로 확인해 주실 수 있을까요?  
확인 결과에 따라 매뉴얼 수정이 필요한지 판단하고자 합니다.

협조해 주셔서 감사합니다.

감사합니다,  
[Your Name]

Reasoning

- 문서 버전(v3.11.8.1)을 명확히 언급해 검토 기준을 분명히 했습니다.
- “확인된 사항”과 “가정 사항”을 구분해 사실과 추측이 혼동되지 않도록 했습니다.
- 엔지니어에게 기술 확인을 요청하면서도 협업적이고 정중한 톤을 유지했습니다.

#### Claude Sonnet 4.6 Result
Subject

Request for Technical Confirmation – Density/Window Section | User Manual v3.11.8.1

---

Email

Hi [Engineer's Name],

I hope you're doing well.

While reviewing **User Manual v3.11.8.1**, I came across the **Density/Window section** and wanted to flag a potential discrepancy for your review.

**What I've confirmed:**
- The current documentation describes the Density/Window behavior based on what appears to be an earlier implementation.
- This section is present in v3.11.8.1 of the user manual.

**What I'm uncertain about:**
- It's unclear whether the described behavior still reflects how the software currently functions.
- The discrepancy may be the result of a recent update or an intentional change that hasn't yet been reflected in the documentation.

Could you help confirm whether the Density/Window section accurately represents the current software behavior? If there is a mismatch, I'd like to coordinate on the appropriate updates to ensure the documentation stays aligned with the latest version.

I appreciate your time and expertise on this — please let me know if you need any additional context.

Best regards,
[Your Name]
[Your Title / Team]

---

**Reasoning**

- **Clarity through structure:** Separating confirmed facts from assumptions prevents miscommunication and makes it easier for the engineer to quickly identify where input is needed.
- **Concise and respectful ask:** The request is framed as a collaborative check rather than a correction, which encourages a constructive response without implying fault.
- **Version specificity:** Explicitly referencing v3.11.8.1 anchors the conversation to a concrete artifact, reducing ambiguity and making follow-up easier.

#### Gemini 3.1 Pro
안녕하세요! 비즈니스 이메일 작성 연습을 하고 계시군요. 주어진 조건에 맞춰 엔지니어와 명확하고 부드럽게 소통할 수 있는 이메일 초안을 작성해 보았습니다. 

정말 훌륭한 연습입니다! 아래의 예시를 참고해 보세요. 👏

---

**Subject**
Request for Technical Confirmation: Density/Window Section (User Manual v3.11.8.1)

**Email**
Hi [Engineer's Name],

I hope this email finds you well.

I am currently reviewing the **User Manual v3.11.8.1** and would like to request your technical expertise regarding the Density/Window section.

**Confirmed Facts:**
- The current user manual (v3.11.8.1) contains a specific explanation of the Density/Window feature.
- During my review, I noticed that this written explanation does not seem to match the actual, current behavior of the software.

**Assumptions:**
- I assume the software's behavior may have been updated recently, and the manual still reflects an older version.
- Alternatively, there might be a specific technical condition or use case for this behavior that I am currently unaware of.

Could you please review this section and confirm the intended technical behavior of the Density/Window feature? Your input will help us ensure the documentation is completely accurate and up-to-date.

Thank you for your time and collaboration!

Best regards,

[Your Name]
[Your Title]

---

**Reasoning**
- **명확한 버전 명시 (Mention the document version):** 제목과 본문 첫 문장에 'v3.11.8.1'을 굵은 글씨(Bold)로 명시하여, 엔지니어가 어떤 문서를 기준으로 확인해야 하는지 즉각적으로 알 수 있게 했습니다.
- **사실과 가정의 명확한 분리 (Separate facts from assumptions):** 'Confirmed Facts'와 'Assumptions'라는 소제목과 불릿 포인트를 사용했습니다. 개발자들은 논리적이고 구조화된 글을 선호하므로, 이렇게 작성하면 오해 없이 상황을 빠르게 파악할 수 있습니다.
- **협업적이고 정중한 어조 (Collaborative and respectful tone):** "틀렸다(wrong)"라는 단어 대신 "일치하지 않는 것 같다(does not seem to match)"라는 부드러운 표현을 썼습니다. 또한 상대방의 전문성을 존중하는 표현("request your technical expertise")을 사용하여 긍정적인 협업을 유도했습니다.

---

이메일에 사용된 영어 표현이나 구조 중에서 혹시 이해가 안 되는 부분이 있다면 언제든 편하게 질문해 주세요. 다른 상황에 맞는 이메일로 다시 설명해 드릴 수도 있습니다. 계속해서 멋지게 학습해 나가시길 응원합니다! 🚀


### Test Case 3 — Ambiguous Request

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
