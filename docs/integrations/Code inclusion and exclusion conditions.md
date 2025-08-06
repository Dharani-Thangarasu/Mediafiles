# Advanced Insertion Rules in Integration – Document360

Document360 supports **Advanced Insertion Rules** for integrations that allow you to control where, when, and how the integration scripts are inserted into your knowledge base site.

---

## What Are Insertion Rules?

Insertion Rules are used to define **where** (which pages), **when** (on load or after delay), and **how** (synchronously or asynchronously) integration scripts are injected in your documentation portal.

These rules help optimize:

- Page load performance
- Script behavior
- Targeted script execution

---

## Rule Types

You can define rules based on:

### 1. Page Level
Decide whether the script should load on all pages or only on selected pages.

- **All pages**: The script will be injected globally.
- **Selected pages**: You can choose specific pages/articles using filters.

### 2. Script Position
Choose where in the HTML the script is injected.

- **Head**
- **Body (start)**
- **Body (end)**

### 3. Execution Mode

- **Synchronous**: Script loads with the page (may delay page rendering).
- **Asynchronous**: Script loads independently (recommended for performance).

### 4. Delay Load

Option to delay script execution by a specified number of seconds after the page is loaded.

---

## Page Filters

To apply rules only on certain pages, use filters:

### Article Path
- Target articles using their URL path.
- Supports wildcards for broad selection.

**Examples**:
- `/getting-started/*` → All articles under "getting-started"
- `/faq/article1` → A specific article

### Language
Inject scripts only for specific language versions of your documentation.

### Version
Apply rules based on the version of the documentation.

---

## Use Case Examples

### Example 1: Insert Chat Widget Only on Specific Pages
- Condition: Path starts with `/support/*`
- Execution: Asynchronous
- Position: Body (end)

### Example 2: Load Analytics Script on All Pages
- Condition: All pages
- Execution: Asynchronous
- Position: Head

### Example 3: Delay Loading a Feedback Tool
- Condition: All pages
- Execution: After 5-second delay
- Position: Body (end)

---

## Managing Insertion Rules

1. Navigate to **Settings → Integrations**.
2. Select an integration.
3. Enable **Advanced Insertion Rules**.
4. Define rules using the provided interface.
5. Save and publish the settings.

---

## Best Practices

- Use asynchronous mode for non-critical scripts to improve performance.
- Apply path-level filters to limit scripts only to where needed.
- Avoid too many scripts in the `head` tag to maintain SEO and load speed.
- Use delay for widgets that should not interfere with initial loading.

---

## Summary

Advanced Insertion Rules allow fine-grained control over how integrations are applied across your knowledge base. Use them to tailor the behavior, performance, and user experience of your documentation site effectively.
