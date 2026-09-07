# Curated Cursor Rules and AI Coding-Agent Prompts

A focused, community-maintained collection of reusable instructions for **Cursor, Claude Code, and other AI coding agents**. Copy a rule into your project when you want an agent to understand the conventions of a Next.js/React or Python/FastAPI codebase before it edits code.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Why this exists

AI coding agents are most useful when they receive explicit project context. Small, opinionated rule files can make architecture, testing, styling, and review expectations visible without forcing every prompt to repeat them.

This repository keeps those rules short, reviewable, and easy to copy. It is a starting point—not a guarantee that generated code is correct or secure.

## Quick start

1. Choose a rule that matches your stack.
2. Read it and adapt any project-specific assumptions.
3. Copy it into your repository as `.cursorrules`, `CLAUDE.md`, or the equivalent file supported by your coding agent.
4. Run your normal formatter, tests, type checker, and security checks before accepting generated changes.

```bash
git clone https://github.com/varungor365/cursor-rules-curated.git
cd cursor-rules-curated
cat rules/nextjs-react.md
```

## Available rules

- [Next.js and React](rules/nextjs-react.md)
- [Python and FastAPI](rules/python-fastapi.md)

More stacks can be added through reviewed pull requests.

## Use cases

- Establish consistent conventions for a small team using AI-assisted coding.
- Give an agent a safe baseline for a new Next.js or FastAPI project.
- Compare prompt guidance across stacks in a transparent, version-controlled format.
- Start a project-specific `CLAUDE.md` or `.cursorrules` file without writing one from scratch.

## Safe defaults and limitations

These files are guidance, not executable policy. They do not replace code review, tests, dependency scanning, secret management, least-privilege controls, or framework documentation. Always adapt examples to the versions and architecture of your project, and never paste secrets into an agent context.

## Contributing

Add a rule only when it is broadly useful, technically accurate, and explicit about assumptions. Keep rules readable, avoid vendor-specific claims that are not verified, and include practical testing and security expectations. Then open a pull request with a short rationale and examples.

## Why star this repository?

Star this repository if you want a small, transparent starting point for AI coding-agent instructions, or if you plan to contribute a rule for another language or framework.

## License

MIT. See [LICENSE](LICENSE).
