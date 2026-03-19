# Webhooks Integration

Configure webhooks in Document360 to send real-time event notifications to any external system or service.

---

## Overview

The Webhooks integration allows teams to send HTTP POST requests to custom URLs whenever specific documentation events occur, enabling flexible, real-time integration with any system that accepts webhooks.

---

## Prerequisites

- A publicly accessible URL to receive webhook payloads
- Document360 project admin access
- Basic understanding of HTTP POST requests and JSON payloads

---

## Setup Steps

1. Navigate to **Settings → Integrations → Webhooks** in Document360.
2. Click **Add Webhook**.
3. Enter the destination **URL** for webhook delivery.
4. Select the documentation events to subscribe to.
5. Configure optional authentication headers or HMAC signing secrets.
6. Click **Save** and test the webhook.

---

## Features

- **Event Subscriptions** – Subscribe to specific events such as article published, updated, or deleted.
- **Custom Headers** – Add authentication headers to secure webhook delivery.
- **HMAC Signing** – Verify webhook authenticity using a shared signing secret.
- **Delivery Logs** – View webhook delivery history and retry failed deliveries.

---

## Supported Events

- Article created
- Article published
- Article updated
- Article deleted
- New comment added
- Team member added

---

## Use Cases

- Trigger a CI/CD pipeline to rebuild a documentation site when articles are published.
- Sync documentation updates to an internal system in real time.
- Notify a custom logging or monitoring service of all documentation changes.

---

## Best Practices

- Always validate the HMAC signature of incoming webhook payloads in your receiving endpoint.
- Return HTTP 200 responses quickly to avoid webhook delivery timeouts.
- Log all incoming webhook payloads for debugging and audit purposes.

---

## Summary

The Webhooks integration provides maximum flexibility for integrating Document360 with any external system, enabling real-time, event-driven documentation workflows without predefined connectors.
