# Chatbot Deployment Guide

Deploy the Document360 Chatbot across different platforms and environments to maximize its reach.

---

## Deployment Options

| Option                   | Use Case                                                  |
|--------------------------|-----------------------------------------------------------|
| **Document360 Portal**   | Native, automatic; no extra steps required.               |
| **External Website**     | Embed the JavaScript snippet on any web page.             |
| **Web Application**      | Use the REST API for in-app chat integration.             |
| **Mobile App**           | Integrate via the REST API or a WebView component.        |
| **Help Desk Widget**     | Connect via Zendesk, Freshdesk, or Intercom integrations. |

---

## Document360 Portal Deployment

The chatbot is automatically available on your Document360 knowledge base portal once enabled in settings. No additional steps are needed.

---

## External Website Deployment

1. Copy the embed snippet from **Settings → Chatbot → Embed Code**.
2. Add it to every page where you want the chat widget to appear.
3. The widget loads asynchronously and will not impact page performance.

---

## Single-Page Application (SPA) Deployment

For React, Angular, or Vue apps:

```javascript
import { initD360Chat } from '@document360/chatbot-sdk';

initD360Chat({
  projectToken: 'YOUR_PROJECT_TOKEN',
  containerId: 'chat-container'
});
```

---

## Production Checklist

- [ ] Chatbot enabled in settings.
- [ ] Embed code added to all target pages.
- [ ] Fallback message configured.
- [ ] Escalation channel set up.
- [ ] Analytics access granted to relevant team members.
- [ ] Bot tested with sample questions.

---

## Summary

Document360's flexible deployment options make it easy to bring the chatbot experience to wherever your users need it most.
