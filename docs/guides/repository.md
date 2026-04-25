# 1. Core Principles

Every new repository must follow these three principles:
- **Clarity** - the prupose of the repo must be immediately understandable
- **Consistency** - all repos follow the same structure and workflow

# 2. Repository Naming Rules
Repository names must be:
- **short, clean, unambiguous**
- **kebab-case (not camelCase)**
- **aligned with the project structure**

Examples:
- ironyx-gateway
- ironyx-docs

# 3. Mandatory Files in Every Repository
## 3.1 README.md
Must include
- short description
- purpose/scope

## 3.2 Pipeline Configuration
- `.github/workflows/ci.yml`

# 1. Required Folder Structure
## Backend (.NET)
```
/src
/tests
/docs (optional)
```

## Frontend
```
/src
/public
```

# 4. Branching Rules
Repositories use **GitFlow**. 
- **main**: for stable version. Must be protected.
- **develop**: for version under devleopment. Must be protected.
- **release/**: for release candidate versions. Must be protected.
- **feature/**: feature branch.
- **fix/**: fix branch.

# 5. Commit Message Rules
Conventional Commits are required:
- **feat**: new feature
- **fix**: bug fix
- **docs**: documentation
- **refactor**: structural change
- **test**: add or modify tests
- **chore**: non-code tasks

# 6. Repository Creation Checklist
When creating a new repo, ensure:
- [] Name follows naming rules
- [] README.md created
- [] CI pipeline configured
- [] Base folder structure created
- [] Branch protection rules enabled
- [] Secred scanning enabled
