# Auth0 Integration

Integrate Document360 with Auth0 to implement flexible, standards-based authentication for your knowledge base.

---

## Overview

The Auth0 integration enables teams to use Auth0 as an identity provider for Document360, supporting SSO, social logins, and custom authentication flows for both team members and readers.

---

## Prerequisites

- An Auth0 account with tenant admin access
- Document360 project admin access
- Auth0 application credentials (domain, client ID, client secret)

---

## Setup Steps

1. Navigate to **Settings → Integrations → Auth0 (SSO)** in Document360.
2. Create a new Auth0 application of type **Regular Web Application**.
3. Copy the **callback URL** from Document360 into the Auth0 app's Allowed Callback URLs.
4. Enter your Auth0 **domain**, **client ID**, and **client secret** in Document360.
5. Configure the login page and user attribute mappings.
6. Test the connection and click **Save**.

---

## Features

- **Universal Login** – Use Auth0's Universal Login page for consistent authentication.
- **Social Logins** – Allow users to log in with Google, GitHub, Microsoft, and more.
- **Custom Rules** – Apply Auth0 rules and actions to enrich user profiles.
- **Role Mapping** – Map Auth0 roles to Document360 access levels.

---

## Use Cases

- Enable customers to access a gated knowledge base using their existing accounts.
- Implement social logins for a developer portal with minimal configuration.
- Apply custom authentication logic to control documentation access.

---

## Best Practices

- Use Auth0 rules to add custom claims to tokens for fine-grained access control.
- Enable multi-factor authentication in Auth0 for sensitive documentation.
- Regularly rotate Auth0 client secrets and update them in Document360.

---

## Summary

The Auth0 integration provides a flexible, developer-friendly authentication layer for Document360, supporting a wide range of identity scenarios from social logins to enterprise SSO.
