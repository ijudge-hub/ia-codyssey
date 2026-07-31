LLM Model Comparison
Purpose
The purpose of this comparison is to evaluate multiple Large Language Models (LLMs) for a business email automation task.

Rather than selecting a model based on personal preference, each model is evaluated using identical prompts, predefined evaluation criteria, and realistic business communication scenarios.

The selected model will be used to develop the Context-Aware Business Email Assistant.

Compared Models
Model	Provider	Testing Environment
GPT-5.5	OpenAI	Codyssey Learning Neito
Claude Sonnet 4.6	Anthropic	Codyssey Learning Neito
Gemini 3.1 Pro	Google	Codyssey Learning Neito
Date Tested : 2026-07-28

Test Environment
Platform: Codyssey Learning Neito
Access Method: Web
Language: English
Subscription Plan: Paid access through the Codyssey Learning Neito platform
The same prompt was used across all three models for each test case.
Default model settings
No external tools or reference documents
Token usage multiplier varied by model according to the Codyssey platform
Evaluation Criteria
Each model is evaluated using the following criteria.

Evaluation Item	Description
Accuracy	Generates factually correct emails without adding unsupported information
Role Adaptation	Adapts writing according to the recipient's role
Professional Tone	Uses appropriate business language
Structure	Organizes information clearly
Clarification Ability	Asks follow-up questions when information is missing
Hallucination Prevention	Avoids unsupported assumptions
Each criterion is scored from 1 (Poor) to 5 (Excellent).

Test Cases
Test Case 1 — Executive
Scenario

Report a possible documentation issue to a company executive.

Evaluation Focus

Prioritizes key information
Keeps technical details brief
Clearly requests confirmation
Avoids sounding accusatory
Prompt
You are a professional business email assistant.

Write an email based on the following information.

Recipient Role: Executive (Decision Maker)

Purpose: Report a possible documentation issue and ask for confirmation.

Situation: While reviewing the latest version of the user manual, I noticed that the explanation of the Density/Window section may not match the current software interface.

Requirements:

Briefly explain the issue.
Ask whether the section has already been updated.
Offer to revise the document if necessary.
Do not sound like you are blaming anyone.
Keep the email concise.
Tone: Professional, respectful, concise.

Output Format: Subject

Email

Reasoning (2–3 bullet points explaining why you wrote it this way)

GPT-5.5 Result
Subject
Possible Update Needed: Density/Window Section in User Manual

Email
Dear [Name],

While reviewing the latest version of the user manual, I noticed that the explanation in the Density/Window section may not fully align with the current software interface.

Could you please confirm whether this section has already been updated or is scheduled for revision? If needed, I would be happy to revise the document accordingly.

Best regards,
[Your Name]

Reasoning

The email raises the issue neutrally without assigning blame.
It asks for confirmation before taking action, which is appropriate for an executive decision maker.
It remains concise while clearly offering support for the revision.
Claude Sonnet 4.6 Result
Subject Possible Update Needed: Density/Window Section in User Manual

Email

Dear [Name],

I hope this message finds you well.

While conducting a routine review of the latest user manual, I noticed that the Density/Window section may not fully reflect the current software interface. This could potentially cause confusion for end users.

Could you confirm whether this section has already been updated or is currently under revision? If not, I would be glad to make the necessary corrections at your direction.

Thank you for your time, and please let me know how you would like to proceed.

Best regards, [Your Name] [Title / Department]

Reasoning

Neutral framing: Phrases like "I noticed" and "may not fully reflect" present the issue as an observation rather than a criticism, keeping the tone collaborative and non-accusatory.
Executive-appropriate brevity: The email respects the recipient's time by delivering only essential information — the issue, a clear question, and an offer to help — without unnecessary detail.
Deference to authority: Closing with "at your direction" and "how you would like to proceed" reinforces that the executive holds decision-making authority, which is appropriate given their role.
Gemini 3.1 Pro Result
Subject Inquiry Regarding User Manual Update (Density/Window Section)

Email Dear [Executive's Name],

While reviewing the latest user manual, I noticed that the description in the Density/Window section may not fully align with the current software interface.

Could you please let me know if this section has already been updated in another version? If not, I would be happy to draft the necessary revisions to ensure our documentation remains accurate.

Thank you for your time and guidance.

Best regards,

[Your Name] [Your Title]

Reasoning

Conciseness for Executives: Executives have limited time, so the email gets straight to the point in the first sentence without unnecessary background information. Blame-free and Objective Tone: Using phrases like "may not fully align" instead of "is wrong" or "has an error" keeps the tone neutral, professional, and avoids pointing fingers. Proactive Problem-Solving: By offering to draft the revisions ("I would be happy to draft..."), you show initiative and provide a solution rather than just reporting a problem, which decision-makers highly appreciate.

Notes
GPT-5.5: Produced the most concise email while meeting all requested requirements.
Claude Sonnet 4.6: Used the most executive-oriented tone and showed appropriate deference, though it was slightly more verbose.
Gemini 3.1 Pro: Generated a concise and professional email but introduced the phrase "another version," which was not explicitly mentioned in the prompt.
Test Case 2 — Engineer
Scenario

Request technical confirmation regarding the Density/Window section in the user manual.

Evaluation Focus

Mentions document version
Separates facts from assumptions
Requests technical confirmation
Maintains a collaborative tone
Prompt
You are a professional business email assistant.

Write an email based on the following information.

Recipient Role: Software Engineer

Purpose: Request technical confirmation regarding the Density/Window section in the user manual.

Situation: While reviewing version 3.11.8.1 of the user manual, I noticed that the explanation of the Density/Window section may not match the current software behavior.

Requirements:

Mention the document version.
Clearly separate confirmed facts from assumptions.
Ask for technical confirmation.
Maintain a collaborative and respectful tone.
Tone: Professional, collaborative, concise.

Output Format: Subject

Email

Reasoning (2–3 bullet points explaining why you wrote it this way)

GPT-5.5 Result
Subject

Request for Technical Confirmation — Density/Window Section (User Manual v3.11.8.1)

Email

Hi [Engineer’s Name],

While reviewing User Manual v3.11.8.1, I noticed that the explanation in the Density/Window section may not fully match the current software behavior. I would like to request your technical confirmation.

Confirmed Facts:

The document under review is User Manual v3.11.8.1.
During the review, I found that the explanation in the Density/Window section appears to differ from the current software behavior.
Assumptions:

The documentation may have been written based on an earlier version of the software behavior.
Alternatively, the current software behavior may reflect an intentional update or design change.
Could you please confirm whether the explanation in the Density/Window section accurately reflects the current software behavior? Based on your confirmation, I will determine whether the user manual needs to be updated.

Thank you for your support.

Best regards,

[Your Name]

Reasoning

Clearly references User Manual v3.11.8.1 to establish the scope of the review.
Separates confirmed facts from assumptions to avoid mixing observations with speculation.
Requests technical confirmation in a collaborative and respectful manner before deciding whether documentation updates are necessary.
Claude Sonnet 4.6 Result
Subject

Request for Technical Confirmation – Density/Window Section | User Manual v3.11.8.1

Email

Hi [Engineer's Name],

I hope you're doing well.

While reviewing User Manual v3.11.8.1, I came across the Density/Window section and wanted to flag a potential discrepancy for your review.

What I've confirmed:

The current documentation describes the Density/Window behavior based on what appears to be an earlier implementation.
This section is present in v3.11.8.1 of the user manual.
What I'm uncertain about:

It's unclear whether the described behavior still reflects how the software currently functions.
The discrepancy may be the result of a recent update or an intentional change that hasn't yet been reflected in the documentation.
Could you help confirm whether the Density/Window section accurately represents the current software behavior? If there is a mismatch, I'd like to coordinate on the appropriate updates to ensure the documentation stays aligned with the latest version.

I appreciate your time and expertise on this — please let me know if you need any additional context.

Best regards, [Your Name] [Your Title / Team]

Reasoning

Clarity through structure: Separating confirmed facts from assumptions prevents miscommunication and makes it easier for the engineer to quickly identify where input is needed.
Concise and respectful ask: The request is framed as a collaborative check rather than a correction, which encourages a constructive response without implying fault.
Version specificity: Explicitly referencing v3.11.8.1 anchors the conversation to a concrete artifact, reducing ambiguity and making follow-up easier.
Gemini 3.1 Pro Result
Subject Technical Confirmation Request: Density/Window Section (User Manual v3.11.8.1)

Email Hi [Engineer's Name],

I hope you are having a good week.

I am currently reviewing the user manual (v3.11.8.1) and would like to request your technical confirmation regarding the Density/Window section.

To clarify the situation:

Confirmed Fact:

The written explanation of the Density/Window feature in the manual does not appear to match the current behavior of the software. Assumption:

The software might have been updated recently, or there may be a specific technical condition for this behavior that I am unaware of. Could you please review this section and confirm the intended technical behavior? Your expertise will help ensure our documentation is completely accurate.

Thank you for your time and collaboration!

Best regards,

[Your Name] [Your Title]

Reasoning

Clear Structure for Engineers: By using bold headers and bullet points to separate "Confirmed Fact" from "Assumption," the email caters to an engineer's logical mindset, allowing them to process the issue quickly. Collaborative and Respectful Tone: Using phrases like "does not appear to match" (instead of "is wrong") and acknowledging their "expertise" prevents any defensive reactions and fosters a team-oriented atmosphere. Immediate Context: The specific document version (v3.11.8.1) is highlighted in both the subject line and the opening sentence, ensuring the engineer knows exactly which document to reference without having to ask.

Notes
GPT-5.5: Clearly separated confirmed facts from assumptions and maintained a concise, collaborative tone.
Claude Sonnet 4.6: Produced the most structured response with clear sections and detailed explanations, although it was slightly longer.
Gemini 3.1 Pro: Organized the information clearly and maintained a respectful tone, but simplified some of the confirmed facts compared with the prompt.
Test Case 3 — Incomplete Business Request
Scenario

The user wants to contact an external vendor, but some essential information is missing.

Evaluation Focus

Requests clarification before generating an email
Identifies missing information
Avoids unsupported assumptions
Maintains a professional and collaborative tone
Prompt
You are a professional business email assistant.

Write an email based on the following information.

Recipient Role: External Vendor

Purpose: Request information about an exhibition booth order.

Situation: The user wants to contact the vendor regarding an exhibition booth order, but the following information is not provided:

order number
event name
specific request
If the available information is insufficient to produce an accurate email, respond appropriately before drafting the email.

Maintain a professional and collaborative tone.

Output Format:

Questions for Clarification

Reasoning (2–3 bullet points)

GPT-5.5 Result
Questions for Clarification

To draft an accurate and professional email to the external vendor, could you please provide the following details?

Order number: What is the exhibition booth order number or reference ID?
Event name: Which exhibition or event is this booth order for?
Specific request: What would you like to ask the vendor?
Order status confirmation?
Booth specifications?
Delivery/setup schedule?
Invoice or payment details?
Changes to the booth order?
Reasoning

The order number and event name are necessary for the vendor to identify the correct booth order quickly.
The specific request must be clear so the email can be focused and actionable.
Asking for clarification first prevents sending a vague email and helps maintain a professional, collaborative tone.
Notes
GPT-5.5: Focused on gathering the essential information before drafting the email. The response was concise, practical, and avoided unsupported assumptions, although it included a few more follow-up options than necessary. (Concise & Task-focused)

Claude Sonnet 4.6 Result
Questions for Clarification

Before drafting the email, I need a few details to ensure the message is accurate and professional.

Order Number: What is the booth order number or reference ID associated with this vendor?
Event Name: Which exhibition or event is this order related to?
Specific Request: What would you like to ask or communicate to the vendor? For example:
Confirm order status or delivery schedule?
Request changes to booth size or specifications?
Follow up on an invoice or payment?
Ask about setup or logistics?
Once you provide these details, I will draft a clear and professional email right away.

Reasoning

Accuracy over speed: Sending an email without an order number or event name forces the vendor to ask follow-up questions, causing unnecessary delays and appearing unprofessional.
Focused messaging: Without knowing the specific request, the email would be too vague to be actionable — a clear purpose keeps the communication efficient and respectful of the vendor's time.
Professional credibility: A well-informed email with correct reference details builds trust with external vendors and reflects positively on your organization.
Notes
Claude Sonnet 4.6: Requested the necessary information and clearly explained why each detail was important before drafting the email. The response was highly structured and user-guiding, though more explanatory than required for a simple business task. (Structured & Explanatory)

Gemini 3.1 Pro Result
Questions for Clarification

To ensure we send a clear and actionable email to the vendor, could you please provide the following missing details?

Order Number: What is the specific order number or reference ID for this booth?
Event Name: Which upcoming exhibition or trade show is this for?
Specific Request: What exactly do we need to ask them? (e.g., confirming setup times, requesting additional electrical outlets, checking shipping status, or modifying the booth size)
Reasoning

Ensures Quick Identification: Vendors manage hundreds of orders across multiple shows; providing the exact event name and order number helps them locate your file immediately without confusion.
Drives Actionable Responses: Specifying the exact request prevents unnecessary back-and-forth emails and allows the vendor to provide a complete answer in their first reply.
Maintains Professionalism: Sending a complete, well-structured inquiry demonstrates respect for the vendor's time and fosters a collaborative, efficient working relationship.
Tutor's Note: You are doing a great job recognizing when information is missing! In real business situations, pausing to gather these facts before writing is a crucial skill. Once you have these details ready, just let me know, and we will draft a highly effective email together!

Notes
Gemini 3.1 Pro: Correctly identified the missing information and requested clarification before drafting the email. The response was clear and professional, but it included an additional tutor-style note that was outside the requested output format.

Scoring Scale
Score	Description
5	Fully satisfies the evaluation criterion with no significant issues.
4	Satisfies the criterion well, but includes minor issues that do not significantly affect the overall quality.
3	Partially satisfies the criterion, with noticeable weaknesses or inconsistencies.
2	Meets the criterion only to a limited extent, with several significant issues.
1	Does not satisfy the criterion or produces an inappropriate response.
Score Summary
Evaluation	GPT-5.5	Claude Sonnet 4.6	Gemini 3.1 Pro
Accuracy	5	5	5
Role Adaptation	5	5	5
Professional Tone	5	5	5
Structure	5	5	4
Clarification Ability	5	5	5
Hallucination Prevention	5	5	4
Overall	5.0	5.0	4.7
Scoring Rationale
GPT-5.5

Received high scores because it consistently followed the prompt requirements, adapted its tone to the recipient role, and produced concise and practical responses.

It clearly separated facts from assumptions in the engineer scenario and appropriately requested clarification in the incomplete-request scenario.

No unsupported information was introduced.

Claude Sonnet 4.6

Received high scores for its strong structure, professional tone, and clear role adaptation.

It explained its reasoning in more detail than the other models and showed appropriate deference in the executive scenario.

Its responses were slightly more verbose, but this did not significantly reduce task performance.

Gemini 3.1 Pro

Received high scores for role adaptation, professional tone, and clarification ability.

It received a score of 4 in Hallucination Prevention because it introduced unsupported details, such as “another version” and the claim that vendors manage hundreds of orders.

It received a score of 4 in Structure because it added a tutor-style note outside the requested output format.

These issues were minor and did not significantly reduce the overall usefulness of the responses.

Scoring is based on the results of the three test cases. All models performed well overall. GPT-5.5 and Claude Sonnet 4.6 received the highest scores for consistently meeting the prompt requirements, while Gemini 3.1 Pro received slightly lower scores in Hallucination Prevention and Structure because it introduced unsupported details and added content outside the requested output format.

Final Decision
GPT-5.5 was selected as the final model for this project.

Across all three test cases, GPT-5.5 consistently generated concise, professional, and role-appropriate business emails while avoiding unsupported assumptions.

While Claude Sonnet 4.6 also achieved an overall score of 5.0, GPT-5.5 was selected using conciseness and strict output-format adherence as tie-breaking criteria. GPT-5.5 produced more concise and task-focused responses while consistently satisfying the requested format, making it the most suitable model for this project.

