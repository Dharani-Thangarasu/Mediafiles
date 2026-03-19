# Stripe Integration

Connect Document360 with Stripe to manage billing-related documentation and automate content updates based on payment events.

---

## Overview

The Stripe integration allows teams to link billing documentation to payment workflows, enabling customers to access relevant guides based on their subscription tier or payment events.

---

## Prerequisites

- A Stripe account with API access
- Document360 project admin access
- Stripe API keys (publishable and secret)

---

## Setup Steps

1. Navigate to **Settings → Integrations → Stripe** in Document360.
2. Enter your Stripe **API key**.
3. Configure webhook endpoints to receive Stripe events.
4. Map Stripe subscription plans to Document360 content visibility groups.
5. Click **Save**.

---

## Features

- **Subscription-Based Access** – Show or hide documentation based on the customer's Stripe subscription plan.
- **Payment Event Triggers** – Automatically update or notify when a payment event occurs.
- **Billing FAQ Suggestions** – Surface relevant billing articles when customers access account pages.
- **Webhook Support** – Receive and act on Stripe webhook events within your documentation workflow.

---

## Use Cases

- Restrict premium documentation to paying subscribers.
- Automatically notify the docs team when a new pricing plan is launched.
- Surface billing troubleshooting articles for customers with failed payments.

---

## Best Practices

- Use Stripe's test mode to validate the integration before going live.
- Keep billing-related documentation up-to-date whenever pricing plans change.
- Monitor webhook delivery in the Stripe dashboard to ensure reliability.

---

## Summary

The Stripe integration bridges your payment infrastructure with your knowledge base, enabling subscription-aware content delivery and seamless billing support documentation.
