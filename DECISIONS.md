---
title: Decisions Log
module: Operations
status: Active
platform: GoHighLevel
last_updated: 2026-07-01
---

# Decisions Log

Use this file to preserve major architecture and operating decisions.

## Decision 001: Use Native GHL First

Decision:

GHL will be the primary operating system for the affiliate program.

Rationale:

- Reduces complexity.
- Keeps operators in one tool.
- Speeds implementation.
- Avoids premature custom development.

Implication:

A custom web app should only be built after a documented GHL limitation is proven.

## Decision 002: Use GitHub as Canonical Project Memory

Decision:

This repository is the source of truth for implementation playbooks, prompts, workflows, and operating standards.

Rationale:

- Version control.
- Easy handoff to humans and LLMs.
- Clear review history.
- Durable documentation.

## Decision 003: Build Modular Workstreams

Decision:

The platform playbook will be built by sprint and module, not as one giant document.

Rationale:

- Easier to maintain.
- Easier to review.
- Easier for AI tools to crawl.
- Avoids unnecessary documentation before features are needed.

## Decision 004: Owner Review Before Launch

Decision:

Public-facing content, AI responses, program terms, and commission language require owner review before activation.

Rationale:

- Protects brand trust.
- Reduces errors.
- Keeps program terms consistent.
