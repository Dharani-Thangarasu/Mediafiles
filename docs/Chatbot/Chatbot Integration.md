# Chatbot Integration

Learn how to integrate the Document360 Chatbot with third-party tools and embed it on external websites.

---

## Embedding on an External Website

You can embed the chatbot widget on any website by adding the provided script snippet.

### Steps

1. Go to **Settings → Chatbot → Embed Code**.
2. Copy the JavaScript snippet.
3. Paste it just before the closing `</body>` tag on your website.

```html
<script>
  window.D360ChatConfig = {
    projectToken: "YOUR_PROJECT_TOKEN"
  };
</script>
<script src="https://cdn.document360.io/chatbot.js" async></script>
```

---

## Integrating with Help Desk Tools

### Zendesk
1. Install the Document360 Chatbot app from the Zendesk Marketplace.
2. Connect using your Document360 API key.
3. The chatbot will appear within Zendesk's help widget.

### Freshdesk
Follow the same pattern via the Freshdesk app directory.

---

## API Integration

For custom integrations, use the **Document360 Chatbot API**:

- **Endpoint**: `POST https://api.document360.io/v1/chatbot/query`
- **Headers**: `Authorization: Bearer <API_KEY>`
- **Body**:
```json
{
  "query": "How do I reset my password?",
  "language": "en"
}
```

---

## Summary

Whether you embed the widget, integrate with a help desk, or call the API directly, Document360 makes it easy to bring chatbot functionality wherever your users are.
