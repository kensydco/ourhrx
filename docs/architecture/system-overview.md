---
title: System Overview
module: Architecture
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# System Overview

## Purpose

This document defines the operating architecture for the OurHealth Rx Affiliate Growth Platform.

The platform should use native GoHighLevel functionality first. A companion web app should only be introduced when a specific GHL limitation is proven.

## Core Principle

GHL is the operating system. The companion app is an extension layer, not the source of truth.

## Primary Business Flow

1. Prospect sees affiliate recruitment content.
2. Prospect visits affiliate landing page.
3. Prospect submits affiliate application.
4. Contact enters Affiliate Program pipeline.
5. Owner reviews application.
6. Approved partner is added to Affiliate Manager.
7. Approved partner receives unique link and onboarding resources.
8. Partner shares link.
9. GHL tracks referrals and commission data where possible.
10. Team monitors performance, engagement, and inactivity.

## Native GHL Responsibilities

- Funnels
- Forms
- CRM contacts
- Pipelines
- Tags
- Custom fields
- Email
- SMS
- Conversation AI
- Voice AI
- Affiliate Manager
- Memberships or gated resource pages
- Social Planner
- Reporting and smart lists

## Future Companion App Responsibilities

Only add a companion app for functions that GHL cannot support well.

Candidate use cases:

- Advanced affiliate dashboard
- Commission forecasting
- Custom leaderboard
- Payout reconciliation
- Advanced attribution by content source
- Affiliate coaching recommendations

## System of Record

| Data Type | System of Record |
|---|---|
| Affiliate contact profile | GHL Contact |
| Affiliate lifecycle stage | GHL Opportunity Pipeline |
| Affiliate link | GHL Affiliate Manager |
| Commission settings | GHL Affiliate Manager |
| Resource access | GHL Membership or gated page |
| Email and SMS engagement | GHL |
| Future advanced analytics | Companion app, if needed |

## Data Model Summary

The core affiliate record is a GHL Contact. The affiliate's current lifecycle state is represented by both pipeline stage and tags.

Use custom fields for structured data such as niche, audience size, payout email, approved date, commission percentage, and affiliate tier.

## Success Criteria

The system is successful when a new operator can:

1. Review new applicants.
2. Approve or reject applicants.
3. Issue links and onboarding resources.
4. Track affiliate status.
5. Identify inactive affiliates.
6. Support affiliates through AI and automated communication.
7. Produce a simple report of applications, approvals, active partners, and referral activity.
