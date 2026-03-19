# Chatbot Versioning

Manage multiple versions of your chatbot configuration to support staged rollouts, A/B testing, and rollback capabilities.

---

## What Is Chatbot Versioning?

Chatbot versioning allows you to save snapshots of your chatbot configuration (settings, templates, widget options) so you can:
- Revert to a previous configuration if a change causes problems.
- Test new configurations on a staging environment before going live.
- Maintain an audit history of chatbot changes.

---

## Creating a Configuration Snapshot

1. Go to **Settings → Chatbot → Versioning**.
2. Click **Save Snapshot**.
3. Enter a name and optional description for the snapshot.
4. Click **Confirm**.

---

## Restoring a Previous Version

1. Navigate to **Settings → Chatbot → Versioning**.
2. Find the snapshot you want to restore.
3. Click **Restore**.
4. Confirm the restoration dialog.

> **Note:** Restoring a snapshot will overwrite your current chatbot configuration.

---

## Version History Table

| Field         | Description                                      |
|---------------|--------------------------------------------------|
| **Version Name** | The name you assigned to the snapshot.        |
| **Created By**   | Team member who saved the snapshot.           |
| **Date**         | Date and time the snapshot was created.       |
| **Status**       | Active or Archived.                           |

---

## Best Practices

- Save a snapshot before making significant configuration changes.
- Use descriptive names (e.g., "Pre-escalation-setup-2025-06").
- Archive old snapshots that are no longer relevant.

---

## Summary

Chatbot versioning provides a safety net for configuration changes, ensuring you can always return to a known-good state quickly and confidently.
