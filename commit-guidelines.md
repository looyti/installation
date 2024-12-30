# Commit Types and Guidelines

This document describes the types of commits and provides examples for writing clear and concise commit messages. Use these conventions to maintain consistency across the project.

---

## General Format

```
<type>/<ISSUE-NO> description
```

- **`type`**: The purpose of the commit (e.g., `feat`, `fix`).
- **`ISSUE-NO`**: The issue or task number related to the commit.
- **`description`**: A brief summary of the changes.

### Examples

```
feat/LYT-213 add new about us page

- Designed and implemented the new About Us page.
- Added team member details and company history sections.
- Included responsive styles for mobile and tablet devices.
```

---

## Commit Types

### 1. `feat` - New Features

Use for introducing a new feature.

### 2. `fix` - Bug Fixes

Use for fixing bugs or errors in the codebase.

### 3. `refactor` - Code Refactoring

Use for restructuring code without changing its functionality.

### 4. `chore` - Maintenance Tasks

Use for non-functional changes like dependency updates or build tasks.

### 5. `docs` - Documentation Updates

Use for changes related to documentation only.

### 6. `test` - Adding or Updating Tests

Use for adding or improving test cases.

---

## Best Practices

- Keep commit messages concise but informative.
- Include details in the description when necessary.
- Reference the related issue or task for better traceability.