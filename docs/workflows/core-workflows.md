---
title: Core Workflow Library
module: Workflows
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# Core Workflow Library

## Purpose

This file defines the first workflows required to operate the affiliate program in GHL.

## Workflow 1: Application Confirmation and Notify

Name:

`OHRx | Automation | Affiliate Application — Confirmation & Notify`

Trigger:

- Form submitted: `OHRx | Form | Affiliate Application`

Actions:

1. Add tag: `Affiliate-Applicant`
2. Create or update opportunity in `OHRx | Pipeline | Affiliate Program`
3. Move to stage: Applicant
4. Send confirmation email
5. Send confirmation SMS if allowed
6. Notify owner
7. Create review task

Ask AI Prompt:

```text
Create a GHL workflow named OHRx | Automation | Affiliate Application — Confirmation & Notify.
Trigger: affiliate application form submitted.
Actions: add Affiliate-Applicant tag, create or update opportunity in Affiliate Program pipeline at Applicant stage, send short confirmation email, send short SMS if allowed, notify owner, and create review task.
Keep messages friendly, clear, and professional.
```

## Workflow 2: Pending Information

Name:

`OHRx | Automation | Affiliate Review — Request Missing Info`

Trigger:

- Opportunity moved to Pending Information

Actions:

1. Send email requesting missing details.
2. Send SMS reminder if allowed.
3. Create follow-up task due in 3 days.

## Workflow 3: Approval and Link Delivery

Name:

`OHRx | Automation | Affiliate Approval — Link Delivery`

Trigger:

- Opportunity moved to Approved OR tag `Affiliate-Approved` added

Actions:

1. Add tag: `Affiliate-Approved`
2. Add contact to Affiliate Manager campaign if supported
3. Send approval email with affiliate link placeholder
4. Grant resource vault access
5. Start onboarding sequence
6. Create internal task to verify link delivery

Ask AI Prompt:

```text
Create a GHL workflow named OHRx | Automation | Affiliate Approval — Link Delivery.
Trigger: opportunity moved to Approved or Affiliate-Approved tag added.
Actions: add Affiliate-Approved tag, add contact to Affiliate Manager campaign if available, send approval email with affiliate link placeholder, grant resource vault access, start onboarding sequence, and create internal task to verify link delivery.
```

## Workflow 4: Rejection or Waitlist

Name:

`OHRx | Automation | Affiliate Review — Rejection or Waitlist`

Trigger:

- Opportunity moved to Rejected

Actions:

1. Send polite message.
2. Add internal note.
3. Remove applicant from active recruitment sequence.

## Workflow 5: Resource Vault Access Granted

Name:

`OHRx | Automation | Resource Vault — Access Granted`

Trigger:

- Tag added: `Resource-Vault-Access`

Actions:

1. Send resource vault link.
2. Explain first three actions.
3. Send disclosure reminder.
4. Start onboarding drip.

## Workflow 6: Inactivity 30-Day Check-In

Name:

`OHRx | Automation | Affiliate Inactivity — 30 Day Check-In`

Trigger:

- No tracked activity for 30 days OR manual tag added

Actions:

1. Send helpful check-in.
2. Offer new content ideas.
3. Add task for outreach if high-value partner.

## Workflow 7: Inactivity 60-Day Pause

Name:

`OHRx | Automation | Affiliate Inactivity — 60 Day Pause Review`

Trigger:

- No tracked activity for 60 days OR manual tag added

Actions:

1. Add tag: `Affiliate-Inactive`
2. Move opportunity to Inactive / Paused
3. Send reactivation message
4. Notify owner if partner was previously active

## Workflow 8: Compliance Hold

Name:

`OHRx | Automation | Affiliate Compliance — Hold`

Trigger:

- Opportunity moved to Compliance Hold

Actions:

1. Pause promotional automation if possible.
2. Add internal task.
3. Send neutral message that account requires review.
4. Notify owner.

## Workflow 9: Top Performer Recognition

Name:

`OHRx | Automation | Affiliate Milestone — Top Performer`

Trigger:

- Manual tag OR referral threshold met

Actions:

1. Move to Top Performer.
2. Send recognition message.
3. Notify owner.
4. Add to top-performer smart list.

## Global Testing Rule

Every workflow must be tested with a dummy contact before activation.

## Exit Criteria

Core workflow library is complete when a test contact can move from Applicant to Approved, receive link instructions, receive resource access, and later be marked inactive or rejected without breaking the contact record.
