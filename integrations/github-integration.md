# GitHub Integration

Sync your Document360 documentation workflow with GitHub to manage content alongside your codebase.

---

## Overview

The GitHub integration enables teams to maintain documentation version control, trigger content updates from code events, and keep docs in sync with software releases.

---

## Prerequisites

- A GitHub account with repository access
- Document360 project admin access
- GitHub Personal Access Token (PAT) with appropriate scopes

---

## Setup Steps

1. Go to **Settings → Integrations → GitHub** in Document360.
2. Enter your **GitHub Personal Access Token**.
3. Select the repository you want to link.
4. Configure the branch and folder path for documentation files.
5. Click **Save and Sync**.

---

## Features

- **Two-Way Sync** – Changes in GitHub markdown files reflect in Document360 and vice versa.
- **Release Triggers** – Automatically publish documentation updates on a new GitHub release.
- **Pull Request Hooks** – Notify the docs team when code PRs are merged.

---

## Use Cases

- Maintain API documentation in sync with code changes.
- Use GitHub Actions to auto-update the knowledge base on deployment.
- Collaborate on docs using standard Git workflows (branches, PRs, reviews).

---

## Best Practices

- Use a dedicated `docs/` folder in your repository for documentation files.
- Add branch protection rules to require reviews before merging doc changes.
- Use commit messages that clearly describe documentation changes.

---

## Summary

The GitHub integration brings developer-friendly version control to your documentation workflow, making it easy to keep technical docs accurate and up-to-date.
