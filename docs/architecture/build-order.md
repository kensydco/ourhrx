---
title: Build Order
module: Architecture
priority: High
status: Draft
platform: GoHighLevel
last_updated: 2026-07-01
---

# Build Order

## Rule

Build dependencies before visible assets. Do not publish recruitment content until the application funnel, confirmation workflow, and pipeline are tested.

## Sprint 1 Build Sequence

### 1. Audit Existing GHL Sub-Account

Check:
- Domains
- Email settings
- SMS settings
- Existing funnels
- Forms
- Workflows
- Pipelines
- Tags
- Custom fields
- Affiliate Manager status
- Social channels

Output:
- One-page audit summary
- Open questions
- Risks
- Assets that can be reused

### 2. Create Foundation Objects

Build:
- Custom values
- Custom fields
- Tags
- Pipeline
- Smart lists
- Folders

### 3. Build Affiliate Application Form

Create form before funnel so the funnel can embed it.

### 4. Build Affiliate Registration Funnel

Pages:
- Landing page
- Application page
- Thank-you page

### 5. Build Confirmation Workflow

Trigger:
- Affiliate application form submitted

Actions:
- Apply tag
- Create or update opportunity
- Send confirmation email
- Send confirmation SMS if appropriate
- Notify owner

### 6. Configure Affiliate Manager Campaign

Build after the pipeline exists and before approving live affiliates.

### 7. Build Approval and Rejection Workflows

Trigger from pipeline stage movement or manual tag.

### 8. Build Resource Vault

Build after approval workflow is defined.

### 9. Build Conversation AI and Voice AI

AI must reference approved knowledge base content only.

### 10. QA Full Flow

Test:
- Form submission
- Pipeline update
- Internal notification
- Confirmation messages
- Approval path
- Rejection path
- Link delivery
- Resource access

## Publication Gate

Recruitment posts may go live only after:

- Funnel is tested
- Form is tested
- Confirmation workflow is tested
- Owner review complete
- Affiliate Manager campaign ready

## AI-First / Manual-Second Map

| Asset | Ask AI Use | Manual Review Need |
|---|---:|---:|
| Landing page copy | High | Medium |
| Forms | Medium | High |
| Workflows | Medium | High |
| Email templates | High | Medium |
| SMS templates | High | Medium |
| Pipeline stages | Low | High |
| Tags | Low | High |
| Affiliate Manager campaign | Medium | High |
| Conversation AI | High | High |
| Voice AI | High | High |
| Reports | Medium | Medium |
