# 🧾 Contributing Guidelines

Welcome to the Neksoft Consultancy Services GitHub organization!

To maintain quality, consistency, and collaboration across all projects, **please follow these contribution guidelines** when working on any repository.

---

## 📁 Repository Branching Strategy

We use a 3-branch strategy for all active repositories:

| Branch | Purpose                     |
|--------|-----------------------------|
| `main` | Production-ready code (stable & protected) |
| `dev`  | Ongoing development & testing |
| `feature/*` | Feature or bug-specific branches created by developers |

---

## 🌿 Creating a New Branch

### ✅ Always branch off from `dev`

```bash
git checkout dev
git pull origin dev
git checkout -b feature/<task-name>
```

### 📌 Naming Examples:

| Type      | Branch Name                    |
|-----------|--------------------------------|
| Feature   | `feature/login-page`           |
| Bugfix    | `bugfix/user-email-validation` |
| Hotfix    | `hotfix/urgent-token-expiry`   |

Avoid vague names like `test`, `newcode`, or `fix1`.

---

## 📥 Submitting a Pull Request (PR)

When your work is ready for review:

### ✅ Open PR **from your feature branch to `dev`**

#### 📝 Example Pull Request:

| Field        | Content                                                           |
|--------------|-------------------------------------------------------------------|
| **Title**    | `feat: implemented login validation with email support`           |
| **Description** | > This PR adds client-side and server-side validation for login.<br>Includes email and password length validation.<br>Fixes issue #42. |
| **Base branch** | `dev` (never `main`)                                           |
| **Reviewers** | Assign a teammate or maintainer                                  |

> 📎 **Attach issues using keywords** like `Fixes #42`, `Closes #17` in your PR description to auto-close them upon merge.

---

## ✅ PR Review Process

- PRs into `main` require **at least 1 approval**
- All conversations must be **resolved**
- Avoid merging your own PRs into `main` unless you’re an admin

---

## 📄 Commit Message Format

Use meaningful and conventional commit messages:

| Prefix | Use For              | Example                                       |
|--------|----------------------|-----------------------------------------------|
| `feat:` | New features         | `feat: add user profile component`           |
| `fix:`  | Bug fixes            | `fix: correct API pagination issue`          |
| `refactor:` | Code cleanup    | `refactor: simplify loop logic`              |
| `docs:` | Documentation only   | `docs: update README for installation`       |
| `test:` | Tests                | `test: add unit tests for login form`        |

---

## 🚫 What NOT to Do

- ❌ Don’t push directly to `main`
- ❌ Don’t skip PR descriptions
- ❌ Don’t merge PRs with unresolved comments
- ❌ Don’t use generic branch names like `patch1` or `update-code`

---

## 🤝 Code of Conduct

Be respectful, collaborative, and professional in all discussions and code reviews.

---

## 📬 Need Help?

- Contact the team lead: `@Neksoft-Daya-2025`
- Or open an issue with your question

Thank you for contributing to Neksoft Consultancy Services projects!
