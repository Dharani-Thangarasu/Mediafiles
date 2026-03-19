# Chatbot Response Templates

Create and manage reusable response templates to ensure consistent, on-brand chatbot answers for common scenarios.

---

## What Are Response Templates?

Response templates are pre-written answers that the chatbot can use for specific types of queries. They are useful for:

- **Greeting messages**
- **Fallback messages** (when no answer is found)
- **Escalation messages**
- **Common procedural answers**

---

## Accessing Templates

1. Go to **Settings → Chatbot → Response Templates**.
2. View existing templates or click **+ New Template** to create one.

---

## Creating a Template

| Field           | Description                                                  |
|-----------------|--------------------------------------------------------------|
| **Template Name** | Internal name for identifying the template.               |
| **Trigger Type**  | When this template is used (greeting, fallback, etc.).    |
| **Message Text**  | The actual response text shown to users.                  |
| **Variables**     | Insert dynamic values like `{{user_name}}` if available.  |

---

## Supported Variables

| Variable         | Description                          |
|------------------|--------------------------------------|
| `{{user_name}}`  | Name of the logged-in user.          |
| `{{date}}`       | Current date.                        |
| `{{portal_name}}`| Name of your knowledge base portal. |

---

## Template Types

- **Welcome Template** – Shown when a user first opens the chat.
- **Fallback Template** – Shown when no answer is found.
- **Escalation Template** – Shown when handing off to human support.
- **Goodbye Template** – Shown when the user ends the conversation.

---

## Summary

Response templates give you control over the tone and messaging of your chatbot, ensuring every interaction feels consistent and professional.
