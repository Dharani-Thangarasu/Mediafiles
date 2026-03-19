# Segment Integration

Connect Document360 with Segment to unify documentation analytics data with your broader customer data platform.

---

## Overview

Segment acts as a central data hub, collecting events from Document360 and routing them to your preferred analytics, marketing, and data warehouse destinations.

---

## Prerequisites

- A Segment account
- Your Segment **Write Key**
- Document360 project admin access

---

## Setup Steps

1. Log in to Document360 and navigate to **Settings → Integrations → Segment**.
2. Toggle the **Enable** switch.
3. Enter your Segment **Write Key**.
4. Click **Save**.

Document360 will begin sending events to your Segment source.

---

## Events Sent to Segment

| Event | Properties |
|---|---|
| `Page Viewed` | Article title, URL, category |
| `Search Performed` | Query string, result count |
| `Article Feedback` | Feedback type (positive/negative), article ID |
| `Link Clicked` | Link URL, article context |

---

## Routing Data to Destinations

Once events are in Segment, you can forward them to:

- **Google Analytics** – for web traffic analysis
- **Amplitude** – for product analytics
- **Mixpanel** – for event-based analytics
- **BigQuery / Redshift** – for data warehousing
- **Braze / Customer.io** – for marketing automation

---

## Use Cases

- Combine documentation engagement data with product usage data.
- Build a 360-degree view of customer journeys that include documentation touchpoints.
- Trigger onboarding emails when users view specific getting-started articles.

---

## Best Practices

- Use Segment's Schema to enforce consistent event naming and properties.
- Enable Segment Protocols to validate incoming documentation events.
- Use Personas to build audiences based on documentation behavior.

---

## Summary

The Segment integration makes Document360 a first-class source in your customer data stack, enabling powerful cross-platform analysis and personalization based on documentation engagement.
