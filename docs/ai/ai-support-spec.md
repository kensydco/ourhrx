# AI Support Spec

## Objective

Document the first AI support assets for Sprint 2.

## Conversation Agent

Name: `OHRx | AI | Conversation — Partner Concierge`

Purpose:

- Answer basic program questions.
- Direct users to the application page.
- Help approved partners find resources.
- Escalate unclear requests.

## Phone Agent

Name: `OHRx | AI | Phone — Partner Support`

Purpose:

- Capture name and contact information.
- Send application link when allowed.
- Create support task when needed.
- Route detailed questions to the team.

## Ask AI Prompt

```text
Create two GHL AI support assets for the OurHealth Rx partner program. Asset one is a Conversation AI agent for chat and SMS. Asset two is a phone support agent. Both should answer basic questions, guide users to the next step, create follow-up tasks when needed, avoid inventing terms, and escalate unclear questions.
```

## QA

- Test application question.
- Test status question.
- Test resource question.
- Test unclear question.
- Confirm task creation works.
