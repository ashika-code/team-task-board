# Team Task Board

> A collaborative project management repository for Team Task Board

---

## Project Description

The team Task Board is a collaborative project repository designed to help a software development team organize and track project work. It uses Git for version control and Agile practices to organize tasks, sprint planning, and development activities.

---

## Team Members

| Name | Role |
|------|------|
| Ashika Balamurugan | Developer |

---

## Tech Stack

- Git
- GitHub
-Linux/Bash
- Markdown

---

## Getting Started

### Prerequisites

- Git installed
- [Any other requirements]

### Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd team-task-board

# Run the setup script
chmod +x scripts/setup.sh
./scripts/setup.sh
```

---

## Project Structure

```
team-task-board/
├── docs/           # Project documentation and Agile artifacts
├── src/            # Source code
├── tests/          # Test files
└── scripts/        # Utility shell scripts
```

---

## Agile Workflow

- **Sprint Length:** 1 week
- **Stand-up:** Daily at [TIME]
- **Sprint Review:** [DAY] at [TIME]
- **Backlog:** See `docs/sprint-backlog.md`
- **Definition of Done:** See `docs/definition-of-done.md`

---

## Branch Strategy

| Branch Pattern | Purpose |
|----------------|---------|
| `main` | Production-ready code |
| `feature/<name>` | New features |
| `fix/<name>` | Bug fixes |
| `docs/<name>` | Documentation changes |

---

## Git Commit Conventions

Format: `type: short description`

| Type | When to use |
|------|-------------|
| `feat` | Adding a new feature |
| `fix` | Fixing a bug |
| `docs` | Documentation only |
| `chore` | Build/tooling changes |
| `refactor` | Code refactoring |
