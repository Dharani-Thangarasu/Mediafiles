# Chatbot API Reference

Use the Document360 Chatbot API to programmatically query the chatbot, retrieve conversation history, and manage settings.

---

## Authentication

All API requests require a Bearer token:

```
Authorization: Bearer <YOUR_API_KEY>
```

Generate your API key in **Settings → API Tokens**.

---

## Base URL

```
https://api.document360.io/v1
```

---

## Endpoints

### Query the Chatbot

**POST** `/chatbot/query`

Submit a user query and receive an AI-generated answer.

**Request Body:**
```json
{
  "query": "How do I reset my password?",
  "language": "en",
  "projectVersionId": "optional-version-id"
}
```

**Response:**
```json
{
  "answer": "To reset your password, go to the login page and click 'Forgot Password'.",
  "confidence": 0.92,
  "articleLinks": [
    {
      "title": "Resetting Your Password",
      "url": "https://docs.example.com/reset-password"
    }
  ]
}
```

---

### Get Conversation History

**GET** `/chatbot/conversations`

**Query Parameters:**

| Parameter    | Type   | Description                        |
|--------------|--------|------------------------------------|
| `startDate`  | string | ISO 8601 start date filter.        |
| `endDate`    | string | ISO 8601 end date filter.          |
| `page`       | int    | Page number (default: 1).          |
| `pageSize`   | int    | Results per page (default: 20).    |

---

### Trigger Re-Training

**POST** `/chatbot/train`

Initiates a re-index of all published articles.

**Response:**
```json
{
  "status": "training_started",
  "estimatedDuration": "2-5 minutes"
}
```

---

## Rate Limits

| Plan       | Requests per Minute |
|------------|---------------------|
| Business   | 60                  |
| Enterprise | 300                 |

---

## Summary

The Chatbot API gives you full programmatic control over chatbot interactions and management, enabling seamless integration into custom applications.
