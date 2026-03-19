# Chatbot Accessibility

The Document360 Chatbot is designed to meet web accessibility standards, ensuring all users can interact with it regardless of ability.

---

## Accessibility Standards

The chatbot widget is built to conform with:
- **WCAG 2.1 Level AA** (Web Content Accessibility Guidelines)
- **Section 508** compliance for U.S. federal accessibility requirements

---

## Keyboard Navigation

Users can interact with the chatbot entirely via keyboard:

| Action                     | Keyboard Shortcut         |
|----------------------------|---------------------------|
| Open chat widget           | `Tab` to focus, `Enter`   |
| Type a query               | Focus input field, type   |
| Submit query               | `Enter`                   |
| Close chat window          | `Esc`                     |
| Navigate feedback buttons  | `Tab`, `Enter`            |

---

## Screen Reader Support

- All interactive elements have appropriate ARIA labels.
- Bot responses are announced to screen readers as they appear.
- The chat window has a descriptive `role="dialog"` attribute.

---

## Color Contrast

- The default widget theme meets WCAG AA contrast ratio requirements (4.5:1 for normal text).
- Custom color configurations should be tested for contrast compliance before publishing.

---

## Focus Management

- When the chat window opens, focus is automatically moved to the input field.
- When the chat window closes, focus returns to the trigger button.

---

## Testing Accessibility

Use tools such as:
- **axe DevTools** browser extension
- **NVDA** or **JAWS** screen readers
- **Lighthouse** accessibility audit

---

## Summary

Document360 is committed to making the Chatbot accessible to all users. Contact support if you encounter specific accessibility barriers.
