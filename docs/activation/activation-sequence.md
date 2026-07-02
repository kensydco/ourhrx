# Partner Activation Sequence

## Objective

Create the first 14-day activation sequence for approved partners.

## Trigger

Partner is approved and receives resource access.

## Sequence Overview

| Day | Message | Purpose |
|---:|---|---|
| 0 | Welcome and link delivery | Start immediately |
| 1 | First action reminder | Get first share |
| 3 | Starter content | Reduce friction |
| 5 | FAQ prompt | Build confidence |
| 7 | Weekly rhythm | Create consistency |
| 10 | Check-in | Offer help |
| 14 | Momentum review | Encourage next action |

## Day 0 Email

Subject: Your partner resources are ready

Body:

Welcome. Your first step is simple: save your link, open the resource vault, and choose one starter message.

Link: {{partner_link}}

Resource vault: {{vault_link}}

## Day 1 SMS

Your first action: pick one approved starter message and share it with the right audience today.

## Day 3 Email

Subject: Copy, paste, and personalize

Body:

Use one starter caption from the resource vault. Keep it honest, simple, and clear. Add your link and disclosure.

## Day 5 Email

Subject: Try a simple FAQ post

Body:

A good FAQ post answers one common question and gives one next step. Keep it short and point people to your link.

## Day 7 Email

Subject: Your weekly rhythm

Body:

Try this weekly rhythm: one story, one educational post, and three direct conversations.

## Day 10 SMS

Need help choosing what to post next? Reply HELP and we will point you to the right starter content.

## Day 14 Email

Subject: Keep the momentum going

Body:

Review what worked, save any questions you received, and choose your next content idea from the vault.

## Ask AI Prompt

```text
Create a 14-day GHL activation sequence for approved partners. Include day 0, day 1, day 3, day 5, day 7, day 10, and day 14 messages. Focus on getting the first share, using approved starter content, and building a simple weekly rhythm.
```

## QA

- Sequence starts only after approval.
- Rejected contacts are excluded.
- Messages include correct links.
- SMS is sent only when allowed.
