# Chatbot Webhooks

Use webhooks to receive real-time notifications and data from the Document360 Chatbot in your own systems.

---

## What Are Chatbot Webhooks?

Webhooks are HTTP callbacks that Document360 sends to a URL you specify when specific chatbot events occur. Use them to:
- Sync conversation data to your CRM.
- Trigger workflows in tools like Zapier or n8n.
- Log chatbot events in your own database.
- Notify custom dashboards of escalations.

---

## Available Webhook Events

| Event                   | Description                                              |
|-------------------------|----------------------------------------------------------|
| `conversation.started`  | A new chat session has been initiated.                   |
| `conversation.ended`    | A chat session has been closed.                          |
| `query.answered`        | A user query was answered successfully.                  |
| `query.unanswered`      | A query could not be answered.                           |
| `escalation.triggered`  | A conversation was escalated to human support.           |
| `feedback.submitted`    | A user submitted a rating or comment.                    |

---

## Configuring Webhooks

1. Go to **Settings → Chatbot → Webhooks**.
2. Click **+ Add Webhook**.
3. Enter your **Endpoint URL** (must be publicly accessible HTTPS).
4. Select the **events** you want to subscribe to.
5. Optionally add a **Secret** for payload verification.
6. Click **Save**.

---

## Webhook Payload Example

```json
{
  "event": "escalation.triggered",
  "timestamp": "2025-03-15T10:45:00Z",
  "sessionId": "abc123",
  "userQuery": "I can't find my invoice",
  "confidence": 0.42,
  "articleLinks": []
}
```

---

## Verifying Payloads

Document360 signs webhook payloads with your secret using HMAC-SHA256. Verify the `X-D360-Signature` header in your endpoint to confirm the request is authentic.

---

## Summary

Webhooks make it easy to build custom integrations and automation workflows around chatbot events, connecting Document360 to your wider tech stack.
