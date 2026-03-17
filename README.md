<div align="center">

# 🎭 Playwright Master Cheatsheet

**The most comprehensive Playwright cheatsheet on the internet.**

22 sections · 139 code examples · 5 languages · Fully interactive

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Playwright](https://img.shields.io/badge/Playwright-v1.40+-45ba4b.svg)](https://playwright.dev/)
[![Languages](https://img.shields.io/badge/Languages-JS%20|%20TS%20|%20Python%20|%20C%23%20|%20Java-blueviolet.svg)](#languages)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[**🔗 Live Demo**](https://anurajsl.github.io/playwright-cheatsheet/) · [**📖 View Cheatsheet**](index.html) · [**🐛 Report Bug**](https://github.com/anurajsl/playwright-cheatsheet/issues) · [**💡 Request Feature**](https://github.com/anurajsl/playwright-cheatsheet/issues)

</div>

---

## ✨ What Makes This Different

This isn't another markdown cheatsheet. It's an **interactive single-file web app** with features you'd expect from a documentation tool:

| Feature | Description |
|---------|-------------|
| ⌘K **Command Palette** | Fuzzy search to jump to any section instantly |
| ⭐ **Bookmarks** | Star sections you reference often (persisted in localStorage) |
| ✅ **Progress Tracker** | Mark sections as learned, visual completion ring in sidebar |
| 🔗 **Deep Links** | Share a link to any specific section — `index.html#section-5` |
| 🏷️ **Difficulty Tags** | Every section labeled Beginner / Intermediate / Advanced |
| 🤖 **Search Assistant** | Ask Playwright questions — instant answers from all 22 sections, no API needed |
| 🎨 **Dark & Light Theme** | Toggle with one click, preference saved |
| 📱 **Fully Responsive** | Sidebar collapses to hamburger menu on mobile |
| 🖨️ **Print Friendly** | All sections auto-expand, chrome hidden |
| 📦 **Zero Dependencies** | Single HTML file — no build step, no framework, no npm |

## 📚 What's Covered

22 deep-dive sections spanning the entire Playwright API:

**Beginner**
- Multi-Language Support (JS, TS, Python, C#, Java)
- Getting Started & Installation
- Locators & Selectors
- Actions & Interactions
- Assertions & Expectations
- Quick Command Reference

**Intermediate**
- Test Framework Structure
- Configuration & Setup
- Network Handling & Mocking
- Authentication Patterns
- API Testing
- Page Object Model (POM)
- Mobile & Responsive Testing
- Debugging & Tracing
- Common Issues & Solutions
- File Operations (Upload/Download)

**Advanced**
- CI/CD Integration (GitHub Actions, GitLab, Docker)
- Best Practices & Patterns
- Advanced Techniques
- Advanced Browser Features
- Multiple Windows & Tabs
- Accessibility Testing (axe-core)

## 🚀 Usage

### Option 1: Just open it
```bash
# Clone and open
git clone https://github.com/anurajsl/playwright-cheatsheet.git
open playwright-cheatsheet/index.html
```

### Option 2: Serve locally
```bash
# Any static server works
npx serve playwright-cheatsheet/
# or
python -m http.server -d playwright-cheatsheet/ 8080
```

### Option 3: GitHub Pages
Fork this repo → Go to Settings → Pages → Deploy from main branch. Done.

## 🤖 Built-in Search Assistant

Click the 💬 button in the bottom-right corner to open the assistant. It:

- Searches all 22 sections instantly using embedded content
- Returns the most relevant snippets with matching code examples
- Clickable links open the referenced section directly
- Works 100% offline — no API keys, no internet needed
- Suggestion chips for common questions on first open

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘K` or `Ctrl+K` | Open command palette |
| `/` | Open command palette |
| `↑` `↓` | Navigate palette results |
| `Enter` | Jump to selected section |
| `Esc` | Close palette |

## 🗂️ Languages

Every code example is available in **5 languages** via tabbed code blocks:

- **JavaScript** — Node.js with `@playwright/test`
- **TypeScript** — Full type annotations
- **Python** — `pytest-playwright`
- **C#** — `Microsoft.Playwright.NUnit`
- **Java** — `com.microsoft.playwright`

## 🤝 Contributing

Contributions are welcome! Whether it's fixing a typo, adding a new section, or improving code examples.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Quick ideas for contributions:**
- Add code examples for missing languages in a section
- Add a new section (e.g., Component Testing, Visual Comparison)
- Fix or update code examples for newer Playwright versions
- Improve accessibility of the cheatsheet itself
- Translate the UI labels

## 📝 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

Free to use, fork, modify, and distribute. Attribution appreciated but not required.

---

<div align="center">

**Built for the QA community** · Star ⭐ if this helped you

</div>
