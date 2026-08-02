<div align="center">

# 🤖 cursor-rules-curated

**The ultimate curated collection of system prompts (`.cursorrules` / `CLAUDE.md`) for AI coding agents.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<br/>

*Give your AI agents the exact context they need to write perfect code in any stack.*

<br/>

</div>

---

## ✨ Why this exists

AI agents (like Cursor, Claude, or GitHub Copilot Workspace) are incredibly powerful, but they write *generic* code by default. If you want them to write code that matches your exact architecture, styling, and best practices, you need to give them explicit system prompts (usually stored in `.cursorrules` or `CLAUDE.md`).

This repository is a community-driven, curated list of the absolute best system prompts for different tech stacks.

---

## 🚀 How to use

1. Find the rule file that matches your tech stack in the `rules/` directory.
2. Copy the contents of the file.
3. Paste it into a `.cursorrules` or `CLAUDE.md` file at the root of your project.
4. Watch your AI assistant write significantly better code!

### Available Stacks
- [Next.js & React (App Router)](rules/nextjs-react.md)
- [Python & FastAPI](rules/python-fastapi.md)
- *(More coming soon! PRs welcome!)*

---

## 🤝 Contributing

We want this to be the definitive resource for AI system prompts. Please contribute your own!

1. Fork the repo.
2. Add your rule file to the `rules/` directory (e.g. `golang-gin.md`).
3. Open a Pull Request.

Make sure your rules are **opinionated but widely applicable** (e.g., standardizing on Tailwind for React, or Black for Python).

---

## 📄 License

MIT © Varun Ruhella. See [LICENSE](LICENSE) for details.
