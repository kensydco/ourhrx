---
title: Start Here
module: Dashboard
priority: Critical
status: Active
platform: GoHighLevel
last_updated: 2026-07-02
version: 0.3.0
---

# OurHealth Rx Platform Playbook

This is the first file a new operator should open.

## Purpose

This repository is the operating playbook for the OurHealth Rx partner platform. It documents how to build, manage, test, and improve the GoHighLevel system.

## Current Build Status

| Sprint | Status | Purpose |
|---|---|---|
| Sprint 1 | Complete | Architecture and foundation |
| Sprint 2 | Complete | GHL implementation specs |
| Sprint 3 | Complete | Resource vault and activation |
| Sprint 4 | Pending | AI support flows |
| Sprint 5 | Pending | Reporting and optimization |

## Read These First

1. [Project Status](PROJECT_STATUS.md)
2. [Implementation Roadmap](IMPLEMENTATION_ROADMAP.md)
3. [Decisions Log](DECISIONS.md)
4. [System Overview](docs/architecture/system-overview.md)
5. [Build Order](docs/architecture/build-order.md)
6. [Naming Conventions](docs/architecture/naming-conventions.md)
7. [Brand Voice](docs/branding/brand-voice.md)
8. [Messaging Guardrails](docs/compliance/guardrails.md)

## Build GHL Foundation

- [GHL Foundation Setup](docs/ghl/foundation-setup.md)
- [Affiliate CRM Model](docs/crm/affiliate-crm-model.md)
- [Affiliate Manager Campaign Setup](docs/affiliate-manager/campaign-setup.md)
- [Commission Model](docs/affiliate-manager/commission-model.md)
- [Approval and Link Management](docs/affiliate-manager/approval-and-link-management.md)

## Build Funnels and Forms

- [Affiliate Registration Hub](docs/funnels/affiliate-registration-hub.md)
- [Affiliate Funnel Build Spec](docs/funnels/affiliate-funnel-build-spec.md)
- [Forms Library](docs/forms/forms-library.md)

## Build Automations

- [Core Workflow Library](docs/workflows/core-workflows.md)
- [Sprint 2 Workflow Specs](docs/workflows/sprint-2-workflow-specs.md)
- [Sprint 3 Activation Workflows](docs/workflows/sprint-3-activation-workflows.md)
- [Workflow Registry](registries/workflow-registry.md)

## Build Messaging

- [Email Library](docs/messaging/email-library.md)
- [SMS Library](docs/messaging/sms-library.md)
- [Onboarding Email Sequence](docs/messaging/onboarding-email-sequence.md)
- [Onboarding SMS Sequence](docs/messaging/onboarding-sms-sequence.md)

## Build Partner Activation

- [Resource Vault](docs/membership/resource-vault.md)
- [Onboarding Lessons](docs/membership/onboarding-lessons.md)
- [Partner Starter Kit](docs/activation/partner-starter-kit.md)
- [Activation Sequence](docs/activation/activation-sequence.md)
- [First 30 Days Plan](docs/activation/first-30-days.md)
- [Social Content Bank](docs/activation/social-content-bank.md)
- [Contact Templates](docs/activation/contact-templates.md)
- [Partner FAQ Content](docs/activation/affiliate-faq-content.md)
- [Support Request Process](docs/activation/support-request-process.md)

## Build AI Support

- [AI Knowledge Base](docs/ai/knowledge-base.md)
- [Conversation AI Spec](docs/ai/conversation-ai-spec.md)
- [AI Support Spec](docs/ai/ai-support-spec.md)

## Use Prompts

- [Sprint 1 Prompt Library](prompts/ask-ai/sprint-1-prompt-library.md)
- [Sprint 2 Prompt Library](prompts/ask-ai/sprint-2-prompt-library.md)
- [Sprint 3 Prompt Library](prompts/ask-ai/sprint-3-prompt-library.md)
- [Prompt Registry](registries/prompt-registry.md)

## QA

- [QA Launch Checklist](docs/qa/launch-checklist.md)
- [Sprint 3 Activation QA](docs/qa/sprint-3-activation-qa.md)
- [Asset Registry](registries/asset-registry.md)
- [AI Registry](registries/ai-registry.md)

## Role Guides

- [Executive Guide](roles/executive.md)
- [GHL Builder Guide](roles/ghl-builder.md)
- [AI Operator Guide](roles/ai-operator.md)
- [Marketing Operator Guide](roles/marketing-operator.md)

## Required Build Order

1. Audit current GHL sub-account.
2. Create tags, custom fields, pipeline, smart lists.
3. Build application form.
4. Build funnel.
5. Configure manager campaign.
6. Build application workflow.
7. Build approval workflow.
8. Build review workflows.
9. Build email and SMS templates.
10. Build resource vault.
11. Build activation sequence.
12. Build support request process.
13. Configure AI agents.
14. Run QA checklist.
15. Review before launch.
