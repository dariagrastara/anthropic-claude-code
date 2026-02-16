# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

**Repository:** anthropic-claude-code
**Status:** Newly initialized — no application code has been added yet.

This repository is intended for development related to Anthropic's Claude Code CLI tool.

## Project Structure

```
anthropic-claude-code/
├── CLAUDE.md          # AI assistant guidance (this file)
└── .git/              # Git repository metadata
```

As the project grows, update this section to reflect the directory layout, entry points, and module boundaries.

## Development Workflow

### Getting Started

1. Clone the repository and check out your working branch.
2. Install dependencies once a package manager is configured (e.g., `npm install`, `pip install -r requirements.txt`).
3. Follow the branching and commit conventions described below.

### Branching

- Feature branches should follow the pattern `claude/<description>-<session-id>`.
- Always push with `git push -u origin <branch-name>`.
- Do not push directly to `main` or `master` without explicit permission.

### Commits

- Write clear, concise commit messages that describe **why** the change was made.
- Use conventional commit style when applicable (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
- Keep commits focused — one logical change per commit.

### Testing

- Run the full test suite before pushing. Update this section with the specific test command once one is configured.
- All new features and bug fixes should include corresponding tests.

### Linting / Formatting

- Follow the project's linter and formatter configuration once established. Update this section with the specific lint/format commands.

## Key Conventions

### Code Style

- Prefer clarity over cleverness.
- Keep functions small and focused on a single responsibility.
- Avoid over-engineering: solve the problem at hand without unnecessary abstractions.

### Security

- Never commit secrets, API keys, or credentials (`.env`, `credentials.json`, etc.).
- Validate all external input at system boundaries.
- Be mindful of OWASP top-10 vulnerabilities (injection, XSS, etc.).

### Documentation

- Keep this CLAUDE.md up to date as the project evolves.
- Document public APIs and non-obvious implementation decisions in code comments.
- Do not add comments that merely restate what the code already says.

## AI Assistant Guidelines

When working in this repository, AI assistants should:

1. **Read before writing.** Always read existing code before proposing changes.
2. **Minimize scope.** Only make changes that are directly requested or clearly necessary.
3. **Track work.** Use todo lists to plan and track multi-step tasks.
4. **Ask when unsure.** Clarify ambiguous requirements before implementing.
5. **Test changes.** Run available tests and verify changes work before committing.
6. **Keep this file current.** Update CLAUDE.md when adding new tooling, conventions, or architectural decisions.
