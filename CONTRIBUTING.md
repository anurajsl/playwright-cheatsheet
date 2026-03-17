# Contributing to Playwright Master Cheatsheet

Thanks for your interest in contributing! This project is a single-file interactive cheatsheet — contributions that improve content quality, coverage, and usability are all welcome.

## How to Contribute

### 1. Fork & Clone

```bash
git clone https://github.com/anurajsl/playwright-cheatsheet.git
cd playwright-cheatsheet
open index.html  # Preview in browser
```

### 2. Make Your Changes

The entire cheatsheet is in `index.html`. It's a self-contained file with:
- **HTML** — section content, code examples
- **CSS** — all styles in a `<style>` block
- **JavaScript** — all interactivity in a `<script>` block

### 3. Test Your Changes

- Open `index.html` in a browser
- Verify the section renders correctly
- Test dark/light theme
- Test on mobile viewport (responsive)
- Verify copy-to-clipboard works on your code blocks
- Run through the command palette (⌘K) to ensure your section appears

### 4. Submit a PR

- Create a feature branch: `git checkout -b add-visual-testing-section`
- Commit with a clear message: `git commit -m "Add visual comparison testing section"`
- Push and open a PR against `main`

## What to Contribute

### High-Impact Contributions

- **New sections**: Component testing, visual regression, Playwright fixtures deep-dive, custom reporters
- **Missing language examples**: Some sections may not have all 5 languages — adding the missing ones is very valuable
- **Updated code**: Playwright releases new APIs — updating examples to use the latest patterns
- **Bug fixes**: Broken code examples, incorrect API usage, typos

### Code Example Guidelines

When adding or editing code examples:

1. **Use the existing HTML structure** for code blocks:
```html
<div class="code-block">
    <div class="code-header">
        <span class="code-label">Description</span>
        <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    </div>
    <pre><code>// Your code here</code></pre>
</div>
```

2. **For multi-language examples**, use tabbed blocks with unique `data-tab` / `data-content` IDs

3. **Use syntax highlighting spans**:
   - `<span class="keyword">` — `const`, `await`, `import`, `async`
   - `<span class="string">` — string values
   - `<span class="function">` — function/method names
   - `<span class="comment">` — comments
   - `<span class="number">` — numeric values
   - `<span class="property">` — object properties

4. **Test that your code actually works** with the current Playwright version

### Section Structure

Each section follows this pattern:

```html
<div class="section" id="section-N" data-category="category" data-difficulty="beginner|intermediate|advanced">
    <div class="section-header" role="button" tabindex="0" aria-expanded="false">
        <!-- Header content -->
    </div>
    <div class="section-body" id="section-N-body">
        <div class="subsection">
            <h3 class="subsection-title">Topic</h3>
            <p class="description">Explanation</p>
            <!-- Code blocks -->
        </div>
    </div>
</div>
```

**Categories**: `setup`, `locators`, `actions`, `assertions`, `framework`, `network`, `auth`, `debugging`, `cicd`, `best-practices`

**Difficulty**: `beginner`, `intermediate`, `advanced`

## Style Guidelines

- Keep explanations concise — this is a cheatsheet, not a tutorial
- Use `<div class="tip">` for pro tips
- Use `<div class="warning">` for common pitfalls
- Use `<div class="example">` for real-world usage patterns
- Prefer practical, copy-paste-ready examples over abstract ones

## Code of Conduct

Be respectful and constructive. This is a community resource — let's keep it welcoming for everyone.

## Questions?

Open an issue with the `question` label and we'll help out.
