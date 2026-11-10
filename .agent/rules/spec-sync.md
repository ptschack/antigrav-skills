---
trigger: always_on
---

# Specification Synchronization (`spec/`)

Every project stores its official specifications in the `spec/` directory at the project root (usually as `.md` or `.adoc` files). The `spec/` directory is the primary source of truth. Keep the `spec/` directory and the code synchronized at all times.

## 1. Initial Check and Specification Discovery
- Before you start a task or examine a project, check the `spec/` directory.
- Run `git status` and `git diff` on the `spec/` directory to find recent changes.
- Keep the existing file format in the `spec/` directory (Markdown `.md` or AsciiDoc `.adoc`).

## 2. Update Specifications After Code Changes
- When you add or change functions, architecture, APIs, or requirements, update the related `.md` or `.adoc` files in `spec/`.
- If no specification file or `spec/` directory exists for a new feature, create it.
- Do not finish an implementation task until the `spec/` directory matches the code behavior.

## 3. Implement Specification Changes in Code
- When you find new, modified, or unimplemented specifications in the `spec/` directory:
  1. Summarize the specification changes and their effect on the code.
  2. Offer to implement these changes in the code before or during your current task.

