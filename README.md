# FlyRank Frontend AI Engineering Capstone

A capstone repository for the **FlyRank Frontend AI Engineering** track. This project explores building AI-assisted frontend applications with modern web technologies and agent-driven development workflows using [Cursor](https://cursor.com).

## Overview

The goal of this capstone is to design, build, and document production-minded frontend applications while integrating AI tools into the development lifecycle—from scaffolding and component generation to testing, refactoring, and code review.

### Learning objectives

- Build responsive, accessible UIs with React and modern CSS
- Apply AI-assisted development workflows in a real project context
- Practice Git collaboration, branching, and [Conventional Commits](https://www.conventionalcommits.org/)
- Write maintainable, modular code with clear component boundaries
- Ship features with attention to performance, error handling, and developer experience

### Focus areas

| Area | Description |
|------|-------------|
| **AI-assisted development** | Use Cursor agents, prompts, and rules to accelerate implementation while keeping code reviewable |
| **Modern UI** | Component-driven design, responsive layouts, and polished user experience |
| **Engineering practices** | Linting, testing, environment configuration, and incremental delivery |
| **Collaboration** | Clear commits, pull requests, and documentation for reviewers |

## Tech stack

| Layer | Technologies |
|-------|--------------|
| **Frontend** | HTML, CSS, JavaScript, React |
| **Runtime / tooling** | Node.js, npm |
| **AI workflow** | Cursor, `.cursorrules` project conventions |
| **Version control** | Git, GitHub |

> Stack may evolve as the capstone progresses (e.g., Vite, TypeScript, testing libraries).

## Project status

🚧 **Early stage** — repository scaffolding is in place. Application code, build tooling, and deployment configuration will be added as milestones are completed.

### Roadmap

- [ ] Initialize frontend app (React + build tooling)
- [ ] Define core UI components and layout
- [ ] Integrate AI-assisted features into the application
- [ ] Add tests and CI checks
- [ ] Deploy a production build

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [Git](https://git-scm.com/)
- [Cursor](https://cursor.com/) (recommended for AI-assisted workflow)

### Installation

```bash
git clone https://github.com/SamreethaJR-05/flyrank-fe-ai-capstone.git
cd flyrank-fe-ai-capstone
```

> Setup and run instructions will be added once the application scaffold is initialized.

```bash
# Coming soon
npm install
npm run dev
```

## Development

### Conventions

This project follows conventions defined in [`.cursorrules`](.cursorrules):

- Use clear, descriptive variable and component names
- Prefer reusable, modular components over one-off implementations
- Keep code simple and readable
- Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages

### AI-assisted workflow

When working in Cursor:

1. Reference project rules in `.cursorrules` so agents follow established patterns
2. Break features into small, reviewable tasks
3. Review AI-generated code before committing—treat suggestions as drafts, not final output
4. Document non-obvious decisions in commit messages or inline comments

### Branching

```text
main          ← stable, reviewable work
feature/*     ← new features or experiments
fix/*         ← bug fixes
```

## Project structure

```text
flyrank-fe-ai-capstone/
├── .cursorrules      # AI and coding conventions for Cursor
├── .gitignore
├── LICENSE
└── README.md
```

Structure will expand as the application is scaffolded, for example:

```text
src/
├── components/       # Reusable UI components
├── pages/            # Route-level views
├── hooks/            # Custom React hooks
├── utils/            # Shared helpers
└── styles/           # Global and shared styles
```

## License

This project is licensed under the [MIT License](LICENSE) — Copyright (c) 2026 SamreethaJR-05.
