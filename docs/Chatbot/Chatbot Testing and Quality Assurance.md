# Chatbot Testing and Quality Assurance

Before deploying the chatbot to production, thoroughly test it to ensure it delivers accurate, helpful responses.

---

## Why Test the Chatbot?

Testing ensures:
- The bot returns correct answers for common queries.
- Fallback and escalation flows work as expected.
- The widget displays correctly across browsers and devices.

---

## Test Modes

### 1. Preview Mode

Use the **Live Preview** panel in **Settings → Chatbot** to interact with the bot before publishing changes.

### 2. Staging Environment

Test on a staging version of your knowledge base or website before rolling out to production.

---

## Test Case Categories

| Category               | Examples                                              |
|------------------------|-------------------------------------------------------|
| **Direct Answers**     | Ask a question with a clear, published answer.        |
| **Paraphrased Queries**| Ask the same question in different ways.              |
| **Out-of-Scope Queries**| Ask something not covered in the knowledge base.     |
| **Edge Cases**         | Very short queries, typos, non-English input.         |
| **Escalation Trigger** | Type "talk to a human" or send repeated bad queries.  |

---

## Sample Test Script

| Query                           | Expected Behavior                             |
|---------------------------------|-----------------------------------------------|
| "How do I reset my password?"   | Returns article link + answer.                |
| "pword reset"                   | Returns answer despite typo.                  |
| "What is the weather today?"    | Returns fallback message.                     |
| "I need to speak to someone"    | Triggers escalation flow.                     |
| "pricing"                       | Returns pricing-related article links.        |

---

## Regression Testing

After updating articles or bot settings, re-run your test script to ensure existing queries still return correct answers.

---

## Summary

A structured testing process gives you confidence that the chatbot will perform reliably in production and provide a positive experience for every user.
