# Sprint 2 Workflow Specs

## Objective

Define the GHL workflows required to operate the initial partner program build.

## Required Workflows

### 1. Application Submitted

Trigger: Partner application form submitted.

Actions:

- Apply Applicant tag
- Create opportunity in Applicant stage
- Send confirmation email
- Send confirmation SMS if allowed
- Notify owner
- Create review task

### 2. Pending Information

Trigger: Opportunity moved to Pending Information.

Actions:

- Send missing information email
- Create follow-up task
- Wait three days
- Notify owner if no response

### 3. Approved

Trigger: Opportunity moved to Approved.

Actions:

- Apply Approved tag
- Add to partner campaign if available
- Send approval email
- Grant resource access
- Start onboarding sequence

### 4. Rejected

Trigger: Opportunity moved to Rejected.

Actions:

- Send respectful closeout email
- Remove applicant from active review reminders
- Keep contact record

### 5. Resource Access

Trigger: Resource access tag added.

Actions:

- Send vault link
- Send first-action checklist
- Start training sequence

### 6. Inactive 30 Days

Trigger: No activity for 30 days or manual tag.

Actions:

- Send check-in
- Offer new content ideas
- Create task for high-value partner

### 7. Inactive 60 Days

Trigger: No activity for 60 days or manual tag.

Actions:

- Add inactive tag
- Move opportunity to inactive stage
- Send reactivation message

## Ask AI Prompt

```text
Create GHL workflows for a partner program: application submitted, pending information, approved, rejected, resource access, inactive 30 days, and inactive 60 days. For each workflow include trigger, tags, pipeline action, message action, owner task, and QA test.
```

## QA

- Each workflow is inactive until tested.
- Dummy contact can complete each path.
- No workflow creates duplicate opportunities.
- No rejected contact receives onboarding messages.
