# Chatbot SSO Integration

Configure Single Sign-On (SSO) with the Document360 Chatbot to provide personalized experiences for authenticated users.

---

## What Is Chatbot SSO?

When SSO is enabled, the chatbot can identify logged-in users and:
- Address them by name in responses.
- Restrict chatbot access to authenticated users only.
- Log conversations against specific user identities.

---

## Prerequisites

- **Enterprise plan** (SSO is not available on lower-tier plans).
- An identity provider (IdP) configured in Document360 (e.g., Okta, Azure AD, Auth0).

---

## How It Works

1. The user logs in to your portal via SSO.
2. Your IdP issues a JWT token containing the user's profile information.
3. The chatbot widget reads the token and extracts user attributes.
4. Personalized greeting and conversation logging are activated.

---

## Configuration Steps

1. Go to **Settings → Chatbot → SSO**.
2. Enable **SSO Integration**.
3. Enter the **JWT Secret** shared with your identity provider.
4. Map token claims to chatbot user attributes:

| Token Claim | Chatbot Attribute |
|-------------|------------------|
| `sub`       | User ID          |
| `name`      | Display Name     |
| `email`     | Email Address    |

5. Save your settings.

---

## Restricting Chatbot to Authenticated Users

Toggle **Require Authentication** to prevent unauthenticated users from accessing the chatbot widget.

---

## Security Considerations

- Always use signed JWTs (RS256 or HS256 with a strong secret).
- Rotate JWT secrets periodically.
- Never expose the JWT secret in client-side code.

---

## Summary

SSO integration elevates the chatbot experience by enabling personalization and secure, identity-aware conversations for logged-in users.
