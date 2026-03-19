# Chatbot Notifications

Configure notifications to keep your team informed about chatbot activity, escalations, and performance thresholds.

---

## Types of Notifications

| Notification Type         | Description                                                    |
|---------------------------|----------------------------------------------------------------|
| **Escalation Alert**      | Triggered when a conversation is escalated to human support.   |
| **Unanswered Query Alert**| Triggered when the bot fails to answer a user's question.      |
| **Low Resolution Rate**   | Alert when the resolved rate drops below a configured value.   |
| **High Volume Alert**     | Triggered when conversation volume exceeds a threshold.        |

---

## Setting Up Notifications

1. Go to **Settings → Chatbot → Notifications**.
2. Select the notification types you want to enable.
3. Choose the delivery channel:
   - **Email**
   - **Slack**
   - **Microsoft Teams**
   - **Webhook**
4. Set thresholds (e.g., alert when resolved rate < 70%).
5. Save your settings.

---

## Escalation Notifications

When escalation is enabled, the assigned support team receives:
- User's query and conversation transcript.
- Time and date of the escalation.
- Suggested article links from the chatbot's search results.

---

## Slack and Microsoft Teams Integration

1. Generate a webhook URL in your Slack or Teams workspace.
2. Paste the URL in **Settings → Chatbot → Notifications → Webhook URL**.
3. Select notification types to send to that channel.

---

## Summary

Proactive notifications help your team respond quickly to chatbot issues and escalations, maintaining a high-quality user experience.
