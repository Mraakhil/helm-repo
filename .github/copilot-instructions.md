# Copilot Instructions for helm-repo

## Project Overview

**helm-repo** is a minimal test repository demonstrating Git workflow and repository initialization. Currently, it contains basic project scaffolding with a simple test file.

- **Repository**: Git-based project at `c:\Users\HP\.vscode\helm-repo`
- **Main Branch**: `main` (synced with `origin/main`)
- **Status**: Early stage - foundational setup only

## Architecture & Structure

```
helm-repo/
├── .git/              # Git history and configuration
├── README.md          # Project documentation (minimal)
├── its-a-project      # Test/placeholder file
└── .github/           # GitHub-specific configurations
```

**Current state**: This is a starter project without established architectural patterns yet. No complex components, services, or data flows exist.

## Development Workflows

### Git Workflow
- **Push changes**: `git push -u origin main`
- **Typical branch strategy**: Commits to `main` directly (consider establishing feature branches as project grows)
- **Remote**: `origin` configured and synced

### Project Setup
- No build system, tests, or dependencies currently configured
- **Next steps for AI agents**: When adding features, establish:
  - Build/test framework (e.g., npm, poetry, cargo depending on language choice)
  - CI/CD pipelines in `.github/workflows/`
  - Dependency management configuration

## Project Conventions

*To be established as the project grows*. Current observations:
- File naming: Descriptive names preferred (`its-a-project` appears to be a test placeholder)
- Git discipline: Clean history, meaningful commit messages

## Integration Points & Dependencies

**Current**: Minimal external dependencies - this is a bare project foundation.

**For AI Agents**: When expanding:
1. Document any external APIs or services in this file
2. Add dependency manifests (package.json, requirements.txt, Cargo.toml, etc.)
3. Include authentication/configuration patterns

## Guidance for AI Agents

1. **First task**: Clarify project purpose and technology stack with the maintainer
2. **Documentation first**: Update this file with patterns/conventions as they emerge
3. **Scalability**: Establish file organization standards early (src/, tests/, docs/, etc.)
4. **Version control**: Use semantic commits; consider conventional commits when CI/CD is added

---

*Last updated: February 2026*  
*Maintain this file as the single source of truth for AI-assisted development patterns.*
