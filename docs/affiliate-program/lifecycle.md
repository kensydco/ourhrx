---
title: Affiliate Lifecycle
module: Affiliate Program
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# Affiliate Lifecycle

## Lifecycle Stages

### 1. Prospect

A person who has seen recruitment content but has not yet applied.

Primary goal:

- Drive to affiliate landing page or guide download.

### 2. Applicant

A person who submitted the application form.

GHL actions:

- Add tag: `Affiliate-Applicant`
- Add opportunity to Applicant stage
- Send confirmation message
- Notify owner

### 3. Under Review

Application is being evaluated.

Review factors:

- Audience fit
- Promotion plan
- Brand alignment
- Trustworthiness
- Relevant network

### 4. Pending Information

Applicant needs to provide missing information.

Typical reasons:

- Missing payout email
- Missing social handle
- Unclear promotion plan
- Need owner clarification

### 5. Approved

Applicant has been accepted but has not yet produced activity.

GHL actions:

- Add tag: `Affiliate-Approved`
- Add to Affiliate Manager
- Send link delivery message
- Grant resource access
- Start onboarding sequence

### 6. Active Affiliate

Partner is actively sharing or generating referrals.

GHL actions:

- Add tag: `Active-Affiliate`
- Start engagement sequence
- Track referral milestones

### 7. Top Performer

Partner exceeds defined threshold.

Possible thresholds:

- 10 referrals
- 25 referrals
- Revenue milestone
- Consistent monthly activity

### 8. Inactive / Paused

Partner has no activity for a defined period.

Default:

- 30-day check-in
- 60-day inactive tag
- 90-day reactivation or pause review

### 9. Rejected

Application is not accepted.

GHL actions:

- Send polite message
- Keep door open when appropriate
- Tag as rejected

### 10. Compliance Hold

Partner requires review before continuing.

Common reasons:

- Missing disclosure
- Unapproved claim
- Questionable content
- Brand misalignment

## Ask AI Prompt

```text
Create an affiliate lifecycle framework in GHL using pipeline stages and tags.

Stages: Prospect, Applicant, Under Review, Pending Information, Approved, Active Affiliate, Top Performer, Inactive / Paused, Rejected, Compliance Hold.

For each stage, define the goal, recommended tags, next action, and owner notification rule. Keep language clear and operational.
```

## Manual QA

- Confirm all lifecycle stages map to pipeline stages or smart lists.
- Confirm no stage requires manual memory outside GHL.
- Confirm owner approval is required before Approved.
- Confirm Compliance Hold pauses automated promotional messages.
