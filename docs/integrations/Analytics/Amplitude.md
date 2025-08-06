# Amplitude Integration – Document360

Document360 supports integration with **Amplitude**, a product analytics platform that helps track user behavior and interactions on your knowledge base.

By integrating Amplitude with Document360, you can:

- Monitor user engagement on your documentation site
- Understand how users interact with articles
- Track events like article views, searches, feedback, and more

---

## Prerequisites

Before setting up the integration:

- You need an active **Amplitude account**
- Retrieve the **API key** (also referred to as the Project API Key) from your Amplitude project settings

---

## Steps to Configure Amplitude Integration

1. **Log in to your Document360 project**
2. Navigate to **Settings → Integrations**
3. Select **Amplitude** from the list of integrations
4. Toggle the switch to **Enable** the integration
5. Enter your **Amplitude API Key**
6. Click **Save**

Once saved, the Amplitude tracking script will be injected into your documentation portal.

---

## What Data is Tracked?

Once integrated, Document360 automatically sends analytics events to Amplitude such as:

- Page/Article views
- Search activity
- Article feedback (like/dislike)
- Language/Version switches
- Navigation between articles

Each event includes metadata like:

- Article ID and title
- Category and subcategory
- Language and version
- Timestamp
- Referrer URL

---

## Viewing Events in Amplitude

After integration, you can view tracked events in your Amplitude dashboard:

1. Go to your **Amplitude project**
2. Navigate to **Events → Event Stream**
3. Filter by project, time, or event name
4. Analyze trends, funnels, and user cohorts based on usage

---

## Disabling the Integration

To disable the Amplitude integration:

1. Go to **Settings → Integrations → Amplitude**
2. Toggle off the **Enable** switch
3. Click **Save**

This removes the tracking script from your knowledge base site.

---

## Best Practices

- Use **asynchronous script loading** (enabled by default) to avoid impacting performance
- Combine Amplitude data with other analytics platforms for a complete view
- Use event properties to create meaningful segments and behavior flows

---

## Summary

The Amplitude integration with Document360 enables you to track and analyze user behavior effectively. With rich event data and seamless setup, this integration helps improve content quality, structure, and engagement through informed decision-making.
