# 📘 Documentation Workflow  
**Ironyx Labs — Trunk‑Based Workflow for Documentation**

The documentation repository follows a lightweight, fast, and highly maintainable workflow.  
GitFlow is intentionally not used here, as documentation evolves continuously and benefits from minimal overhead.

---

## 🚀 Core Principles

- `main` always reflects the latest stable documentation  
- All changes are made through short‑lived branches  
- Small, focused pull requests  
- Minimal ceremony, maximum clarity  
- No GitFlow, no long‑running branches like `develop`, `release`, or `hotfix`  

---

## 🌿 Branching Strategy

Every change begins from `main` and is developed in a short‑lived branch:


**Examples:**
- `docs/naming-conventions`
- `docs/architecture-overview`
- `docs/update-readme`
- `docs/add-design-principles`

---

## 📝 Commit Conventions

This repository follows the **Conventional Commits** standard.

Format:


**Common types:**
- `docs` — documentation content  
- `refactor` — structural reorganization  
- `chore` — minor maintenance  

**Examples:**
- `docs(workflows): add trunk-based workflow`
- `docs(architecture): update system overview`
- `refactor(structure): reorganize docs folders`

---

## 🔀 Pull Request Workflow

- Keep PRs small and focused  
- One reviewer recommended  
- Merge strategy: **Squash & Merge**  
- PR description should include:
  - purpose  
  - summary of changes  
  - affected files  
  - any relevant notes  

---

## 📌 Why Trunk‑Based?

- Enables fast iteration  
- Reduces complexity  
- Avoids unnecessary branching overhead  
- Matches the natural flow of documentation updates  
- Scales cleanly as Ironyx Labs grows  

---

## 🧩 Summary

The documentation repository uses a **trunk‑based workflow** to ensure clarity, speed, and consistency.  
The goal is simple: **keep the process lightweight while maintaining high‑quality, well‑structured documentation.**
