# Looker Integration

Connect Document360 with Looker to embed BI dashboards and data explorations within your documentation.

---

## Overview

The Looker integration enables teams to embed Looker Looks, dashboards, and explores into Document360 articles, providing readers with live data insights alongside written documentation.

---

## Prerequisites

- A Looker instance with API access
- Document360 project admin access
- Looker API credentials (client ID and secret) or embed secret

---

## Setup Steps

1. Navigate to **Settings → Integrations → Looker** in Document360.
2. Enter your Looker **instance URL**, **client ID**, and **client secret**.
3. Enable Looker Embedded Analytics in your Looker admin settings.
4. Generate signed embed URLs for the dashboards or Looks to embed.
5. Paste the embed URLs into Document360 articles using the embed widget.
6. Click **Save**.

---

## Features

- **Signed Embeds** – Securely embed Looker dashboards using signed embed URLs.
- **Row-Level Security** – Enforce Looker user attribute-based access control in embeds.
- **Live Data** – Embedded dashboards reflect real-time data from Looker.
- **Custom Theming** – Match Looker embed themes to your documentation site's branding.

---

## Use Cases

- Embed operational metrics dashboards in product documentation.
- Include customer usage analytics in customer success knowledge bases.
- Display live data tables alongside technical specifications in developer docs.

---

## Best Practices

- Use Looker's row-level security to ensure readers only see data they're authorized to view.
- Test embed links in a staging environment before publishing.
- Optimize Looker dashboards for fast load times when embedded.

---

## Summary

The Looker integration brings the power of business intelligence directly into documentation, enabling teams to deliver data-enriched content that provides immediate, actionable insights.
