# CRM Model

## Objective

Define how GHL contact records, opportunities, tags, custom fields, and smart lists represent the partner program.

## Contact Record

Each partner is a GHL contact. The contact record stores identity, communication history, social handles, review notes, tier, and activity fields.

## Pipeline

`OHRx | Pipeline | Partner Program`

Stages:

1. Applicant
2. Under Review
3. Pending Information
4. Approved
5. Active Partner
6. Top Performer
7. Inactive / Paused
8. Rejected
9. Review Hold

## Required Custom Fields

- Partner - Primary Niche
- Partner - Audience Size
- Partner - Primary Platform
- Partner - Instagram Handle
- Partner - TikTok Handle
- Partner - Facebook Page
- Partner - Website
- Partner - Promotion Plan
- Partner - Motivation
- Partner - Approval Date
- Partner - Payout Email
- Partner - Partner Tier
- Partner - Activity Count
- Partner - Lifetime Value
- Partner - Notes

## Required Smart Lists

- Partner Applicants
- Approved Partners
- Active Partners
- Inactive Partners
- Pending Information
- Top Performers
- Needs Review

## Ask AI Prompt

```text
Create a GHL CRM structure for a partner program. Include one pipeline with stages for applicant review, approval, active status, inactivity, rejection, and hold. Include custom fields for niche, audience, platform, social handles, promotion plan, approval date, payout email, tier, count fields, and notes. Create smart lists for each major stage.
```

## QA

- Dummy applicant appears in Applicant smart list.
- Approved contact appears in Approved smart list.
- Active partner appears in Active smart list.
- Required custom fields are visible on contact record.
