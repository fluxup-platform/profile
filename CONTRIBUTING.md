# Contributing Guide

Thank you for contributing to **profile**. Follow these guidelines to keep the process consistent and efficient.

---

## 1. Register a Task on the Board

Before writing any code:

1. Open (or locate) the task on the [project board](https://github.com/orgs/fluxup-platform/projects/1).
2. Assign yourself and move the task to **In Progress**.
3. Tag relevant members using `@username` (e.g. `@diovanibmotta`).

> Never start development without a registered task.

---

## 2. Branch Convention

Create your branch from `main` following this pattern:

| Type | Pattern | Example |
|------|---------|---------|
| New feature | `feature/<kebab-description>` | `feature/add-auth-guard` |
| Bug fix | `bugfix/<issue-number>` | `bugfix/42` |
| Task / chore / docs | `task/<issue-number>` | `task/99` |

```bash
git checkout main
git pull origin main
git checkout -b task/99
```

---

## 3. Commit Convention

Follow **Semantic Release** with emoji prefixes. Subject must be imperative, ≤72 chars, no trailing period. Always include `AFFECT TASK`.

| Type | Emoji | When |
|------|-------|------|
| `feat` | ✨ | New feature |
| `fix` | 🐛 | Bug fix |
| `refactor` | ♻️ | Code change without feature/fix |
| `test` | ✅ | Add/update tests |
| `docs` | 📝 | Documentation only |
| `chore` | 🔧 | Build, config, tooling |
| `perf` | ⚡ | Performance improvement |
| `style` | 💄 | Formatting, no logic change |
| `ci` | 👷 | CI/CD config |

**Format:**

```text
<emoji> <type>(<scope>): <short description>

[optional body: explain WHY if non-obvious]

AFFECT TASK: #<issue-number>
```

**Example:**

```text
✨ feat(profile): add organization profile overview

AFFECT TASK: #99
```

---

## 4. Documentation

- Document the **task**: describe what was done, decisions made, and any relevant context in the GitHub issue.
- Document the **PR**: fill in the PR template (summary, motivation, test plan).
- After opening the PR, move the **task to "Code Review"** and the **PR to "Review"** on the board.
- Tag project members with `@username` for visibility.

---

## 5. Pull Request Review Process

1. Open the PR as **Draft** while implementing.
2. When ready, remove the draft status and request review.
3. The PR will be reviewed by the team. If approved, it proceeds to versioning and release.
4. Address all review comments before merging.
5. **Do not merge your own PR.**

---

## 6. Follow the Repository Guidelines

Read and follow the contribution guidelines in this file before contributing. For questions about architecture, code patterns, or naming conventions, open a [discussion](https://github.com/fluxup-platform/profile/discussions).
