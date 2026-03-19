# Chatbot Escalation to Human Support

Configure the Document360 Chatbot to hand off conversations to a human support agent when the bot cannot resolve a user's query.

---

## What Is Escalation?

Escalation is the process of transferring a chatbot conversation to a live support agent. This ensures users who need deeper help are not left without assistance.

---

## Enabling Escalation

1. Go to **Settings → Chatbot → Escalation**.
2. Toggle **Enable Human Escalation** to ON.
3. Configure the escalation trigger (e.g., after N failed attempts or when confidence drops below threshold).

---

## Escalation Channels

You can route escalated conversations to:

- **Email** – Send a notification to your support team email.
- **Zendesk** – Create a ticket automatically.
- **Freshdesk** – Open a new support ticket.
- **Custom Webhook** – Post escalation data to any endpoint.

---

## Escalation Message

Customize the message the bot shows when escalating:

> "I'm sorry I couldn't help. Let me connect you with our support team."

---

## Escalation Triggers

| Trigger                        | Description                                          |
|--------------------------------|------------------------------------------------------|
| **Low Confidence**             | Bot answer confidence falls below the set threshold. |
| **Repeated Unresolved Queries**| User asks the same or similar question multiple times.|
| **User Request**               | User types "talk to a human" or similar phrases.     |

---

## Summary

A well-configured escalation path ensures every user reaches a resolution, whether through automated answers or human support.
