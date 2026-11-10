---
trigger: always_on
---

# Specification Synchronization (`spec/`)

Every project maintains its authoritative specifications inside the `spec/` directory at the project root (typically as `.md` or `.adoc` files). Treat `spec/` as a living source of truth that stays synchronized with the codebase in both directions.

## 1. Initial Check & Spec Discovery
- At the start of a task or when exploring a project, check the `spec/` directory (and `git status` / `git diff` on `spec/` when applicable) to understand current specifications and detect any recent specification changes.
- Preserve the existing format conventions in `spec/` (Markdown `.md` or AsciiDoc `.adoc`).

## 2. Implementation -> Spec (Keep `spec/` Updated)
- Whenever features, architecture, goals, APIs, or project requirements are added, changed, or clarified during implementation or discussion, update or expand the corresponding `.md` or `.adoc` files in `spec/` as part of the same task.
- If a new feature or requirement is introduced and no matching specification file (or `spec/` folder) exists yet, create it in `spec/`.
- Do not consider an implementation task complete if its behavior diverges from `spec/` without updating `spec/` accordingly.

## 3. Spec -> Implementation (Offer to Implement `spec/` Changes)
- Whenever you detect new, modified, or unimplemented specifications in `spec/` (whether edited by the user, visible in version control diffs, or discovered while reading `spec/`):
  1. Summarize the detected specification changes and their impact on the codebase.
  2. Proactively offer to implement those changes into the project before or alongside your current work.
