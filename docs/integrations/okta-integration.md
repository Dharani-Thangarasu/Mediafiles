# Okta Integration

Integrate Document360 with Okta to enable Single Sign-On (SSO) and centralized identity management for your knowledge base.

---

## Overview

The Okta integration allows organizations to authenticate users with their existing Okta identity provider, providing secure and seamless access to Document360 without requiring separate credentials.

---

## Prerequisites

- An Okta account with admin privileges
- Document360 project admin access
- SAML 2.0 or OIDC application configured in Okta

---

## Setup Steps

1. Navigate to **Settings → Integrations → Okta (SSO)** in Document360.
2. Create a new SAML or OIDC application in your Okta admin console.
3. Copy the **SSO URL** and **Entity ID** from Document360 into the Okta app configuration.
4. Download the Okta **metadata XML** or copy the certificate.
5. Paste the Okta credentials into the Document360 SSO settings.
6. Test the connection and click **Save**.

---

## Features

- **Single Sign-On** – Log in to Document360 using Okta credentials.
- **Provisioning** – Automatically create and deactivate user accounts via SCIM.
- **Group Mapping** – Map Okta groups to Document360 reader groups and team roles.
- **MFA Enforcement** – Enforce multi-factor authentication policies from Okta.

---

## Use Cases

- Enable employees to access internal documentation with their corporate SSO credentials.
- Automate user provisioning and deprovisioning when employees join or leave.
- Restrict knowledge base access to specific Okta user groups.

---

## Best Practices

- Test SSO with a single user account before rolling out to the entire organization.
- Configure just-in-time (JIT) provisioning for automatic user creation on first login.
- Review Okta group assignments regularly to ensure correct documentation access.

---

## Summary

The Okta integration simplifies access management for Document360 by leveraging your organization's existing identity infrastructure for secure, centralized authentication.
