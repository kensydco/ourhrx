# Sprint 3 Activation Workflows

## Objective

Define the GHL workflows that activate approved partners after link delivery.

## Workflow 1: Vault Access Delivery

Trigger: Resource access tag added.

Actions:

- Send vault link.
- Send first actions.
- Start onboarding lessons.
- Create follow-up task after seven days.

## Workflow 2: Onboarding Lessons

Trigger: Partner approved.

Actions:

- Send lesson 1 immediately.
- Send lesson 2 after one day.
- Send lesson 3 after three days.
- Send lesson 4 after five days.
- Send lesson 5 after seven days.

## Workflow 3: First Share Reminder

Trigger: Approval sequence starts.

Actions:

- Wait one day.
- Send reminder to pick one starter message.
- If no response after three days, send support prompt.

## Workflow 4: 14-Day Momentum Review

Trigger: Fourteen days after approval.

Actions:

- Send review message.
- Ask if partner needs content help.
- Create owner task for high-value partner.

## Workflow 5: Support Request Routing

Trigger: Partner support form submitted.

Actions:

- Tag support request.
- Create task.
- Send confirmation message.
- Notify owner or operator.

## Ask AI Prompt

```text
Create GHL activation workflows for approved partners: vault access delivery, onboarding lessons, first share reminder, 14-day momentum review, and support request routing. Include triggers, wait steps, messages, tags, tasks, and QA tests.
```

## QA

- Workflows only apply to approved contacts.
- Resource link is correct.
- Timed messages send in order.
- Support request creates a task.
- Rejected contacts are excluded.
