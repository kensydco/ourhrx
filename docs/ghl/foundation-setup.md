---
title: GHL Foundation Setup
module: GHL
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# GHL Foundation Setup

## Objective

Create the base objects required before building funnels, workflows, Affiliate Manager campaigns, AI agents, and membership resources.

## Required Objects

### Pipeline

Create pipeline:

`OHRx | Pipeline | Affiliate Program`

Stages:

1. Applicant
2. Under Review
3. Pending Information
4. Approved
5. Active Affiliate
6. Top Performer
7. Inactive / Paused
8. Rejected
9. Compliance Hold

### Core Tags

Create:

- Affiliate-Applicant
- Affiliate-Approved
- Active-Affiliate
- Affiliate-Inactive
- OHRx-High-Reach
- OHRx-HBCU-Network
- OHRx-FaithBased
- OHRx-Memphis
- OHRx-Atlanta
- OHRx-Birmingham
- OHRx-Rural-South
- Resource-Vault-Access
- Needs-Owner-Review

### Custom Fields

Create under an Affiliate group when possible:

- Affiliate - Primary Niche
- Affiliate - Audience Size
- Affiliate - Primary Platform
- Affiliate - Instagram Handle
- Affiliate - TikTok Handle
- Affiliate - Facebook Page
- Affiliate - Website
- Affiliate - Promotion Plan
- Affiliate - Motivation
- Affiliate - Approval Date
- Affiliate - Payout Email
- Affiliate - Commission Percent
- Affiliate - Partner Tier
- Affiliate - Referral Count
- Affiliate - Lifetime Revenue
- Affiliate - Notes

### Smart Lists

Create:

- Affiliate Applicants
- Approved Affiliates
- Active Affiliates
- Inactive Affiliates
- High Reach Affiliates
- Needs Review
- Pending Information
- Top Performers

## Ask AI Prompt

```text
Create the foundation objects for an affiliate program in GHL.

Create pipeline: OHRx | Pipeline | Affiliate Program.
Stages: Applicant, Under Review, Pending Information, Approved, Active Affiliate, Top Performer, Inactive / Paused, Rejected, Compliance Hold.

Create tags: Affiliate-Applicant, Affiliate-Approved, Active-Affiliate, Affiliate-Inactive, OHRx-High-Reach, OHRx-HBCU-Network, OHRx-FaithBased, OHRx-Memphis, OHRx-Atlanta, OHRx-Birmingham, OHRx-Rural-South, Resource-Vault-Access, Needs-Owner-Review.

Create custom fields for affiliate niche, audience size, primary platform, social handles, website, promotion plan, motivation, approval date, payout email, commission percent, partner tier, referral count, lifetime revenue, and notes.
```

## Manual QA

- Confirm every pipeline stage exists in the correct order.
- Confirm every tag exists exactly as written.
- Confirm custom fields are grouped logically.
- Confirm smart lists return expected test contacts.
- Confirm no duplicate tags were created.

## Exit Criteria

Foundation is complete when a test applicant can be tagged, placed into the pipeline, filtered in smart lists, and updated with custom field data.
