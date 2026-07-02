---
title: Sprint 1 GHL Ask AI Prompt Library
module: Prompts
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# Sprint 1 GHL Ask AI Prompt Library

## How to Use

Run one prompt at a time inside GHL Ask AI. After each output, manually review, rename assets using the naming convention, and test before activating.

## Prompt 1: Foundation Objects

```text
Create the foundation objects for an affiliate program in GHL.

Create pipeline: OHRx | Pipeline | Affiliate Program.
Stages: Applicant, Under Review, Pending Information, Approved, Active Affiliate, Top Performer, Inactive / Paused, Rejected, Compliance Hold.

Create tags: Affiliate-Applicant, Affiliate-Approved, Active-Affiliate, Affiliate-Inactive, OHRx-High-Reach, OHRx-HBCU-Network, OHRx-FaithBased, OHRx-Memphis, OHRx-Atlanta, OHRx-Birmingham, OHRx-Rural-South, Resource-Vault-Access, Needs-Owner-Review.

Create custom fields for affiliate niche, audience size, primary platform, social handles, website, promotion plan, motivation, approval date, payout email, commission percent, partner tier, referral count, lifetime revenue, and notes.
```

## Prompt 2: Affiliate Application Form

```text
Create a form named OHRx | Form | Affiliate Application.

Fields: first name, last name, email, phone, Instagram handle, TikTok handle, Facebook page or profile, website, audience size, primary niche, city/state, why do you want to join, how do you plan to promote, payout email, and disclosure agreement checkbox.

Make required fields: name, email, phone, primary niche, audience size, promotion plan, payout email, and disclosure checkbox.
```

## Prompt 3: Affiliate Registration Funnel

```text
Create a 3-page affiliate recruitment funnel for OurHealth Rx.

Pages: landing page, application page, thank-you page.
Tone: conversational, bold, trustworthy, community-centered.
Goal: recruit partners who can refer customers using a unique tracking link.

Landing sections: hero, why us, how it works, who it is for, partner opportunity, why now, FAQ, final CTA.
CTA: Apply to Become an Affiliate.
Application form: embed OHRx | Form | Affiliate Application.
Thank-you page: confirm application received and explain that review is required before approval.
Avoid hype, guarantees, or exaggerated claims.
```

## Prompt 4: Confirmation Workflow

```text
Create a GHL workflow named OHRx | Automation | Affiliate Application — Confirmation & Notify.
Trigger: affiliate application form submitted.
Actions: add Affiliate-Applicant tag, create or update opportunity in Affiliate Program pipeline at Applicant stage, send short confirmation email, send short SMS if allowed, notify owner, and create review task.
Keep messages friendly, clear, and professional.
```

## Prompt 5: Approval Workflow

```text
Create a GHL workflow named OHRx | Automation | Affiliate Approval — Link Delivery.
Trigger: opportunity moved to Approved or Affiliate-Approved tag added.
Actions: add Affiliate-Approved tag, add contact to Affiliate Manager campaign if available, send approval email with affiliate link placeholder, grant resource vault access, start onboarding sequence, and create internal task to verify link delivery.
```

## Prompt 6: Pending Information Workflow

```text
Create a workflow named OHRx | Automation | Affiliate Review — Request Missing Info.
Trigger: opportunity moved to Pending Information.
Actions: send a short email asking the applicant to complete missing details, send SMS if allowed, and create a 3-day follow-up task.
Tone: helpful, direct, and professional.
```

## Prompt 7: Rejection or Waitlist Workflow

```text
Create a workflow named OHRx | Automation | Affiliate Review — Rejection or Waitlist.
Trigger: opportunity moved to Rejected.
Actions: send a polite message, add an internal note, remove from active recruitment workflows, and keep the contact record for future review.
Tone: respectful and door-open.
```

## Prompt 8: Resource Vault Access

```text
Create a workflow named OHRx | Automation | Resource Vault — Access Granted.
Trigger: Resource-Vault-Access tag added.
Actions: send the resource vault link, explain the first three recommended actions, remind partner to use disclosure language, and start onboarding sequence.
Tone: encouraging, simple, and action-oriented.
```

## Prompt 9: Conversation AI

```text
Create a Conversation AI agent named OHRx | AI | Conversation — Affiliate Concierge.
Purpose: answer basic partner program questions, explain how to apply, explain approval steps, direct people to the application page, and escalate uncertain questions to a human.
Tone: conversational, bold, trustworthy, helpful.
Rules: keep answers short, avoid guarantees, ask one question at a time, and always provide the next step.
```

## Prompt 10: Voice AI

```text
Create a Voice AI script for OurHealth Rx partner program support.
Role: answer basic questions, capture caller contact information, send application link by SMS if allowed, and route uncertain questions to the team.
Tone: warm, professional, brief.
Rules: confirm important details, avoid long explanations, and end with a clear next step.
```

## Prompt 11: Smart Lists

```text
Create smart lists for the affiliate program:
Affiliate Applicants, Approved Affiliates, Active Affiliates, Inactive Affiliates, High Reach Affiliates, Needs Review, Pending Information, and Top Performers.
Use tags, pipeline stages, and custom fields to define each list.
```

## Prompt 12: QA Checklist

```text
Create a QA checklist for the OurHealth Rx affiliate program build in GHL.
Include tests for form submission, pipeline movement, tags, custom fields, confirmation messages, owner notifications, approval flow, rejection flow, resource access, mobile funnel layout, and AI response review.
```
