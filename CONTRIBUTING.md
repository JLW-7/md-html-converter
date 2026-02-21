# Contributing to Marky

Thanks for your interest in contributing! Here's how to get involved.

## Getting Started

This is a pure static site — no build step required.

1. **Fork** the repo and clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/md-html-converter.git
   cd md-html-converter
   ```

2. **Open locally**: Just open `index.html` in your browser, or use a local server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```

3. **Make your changes**, then open a pull request against `main`.

## Project Structure

```
md-html-converter/
├── index.html          # Landing page
└── convert/
    └── index.html      # Converter tool
```

## Guidelines

- **Keep it dependency-free** (no build tools, no bundlers). All dependencies are loaded via CDN.
- **Test in multiple browsers** before submitting — Chrome, Firefox, and Safari.
- **Write clear commit messages** that describe what changed and why.
- **Open an issue first** for large or breaking changes so we can discuss before you invest time writing code.

## Reporting Bugs

Please open a [GitHub Issue](https://github.com/JLW-7/md-html-converter/issues) with:
- A clear description of the bug
- Steps to reproduce
- Expected vs. actual behavior
- Browser & OS information

## Feature Requests

Open a [GitHub Issue](https://github.com/JLW-7/md-html-converter/issues) with the `enhancement` label. Describe the feature and why it would be useful.

## Code Style

- Use 2-space indentation.
- Prefer `addEventListener` over inline `on*` handlers.
- Keep JS in the `<script>` block at the bottom of the HTML file (no separate JS files needed for this scale of project).
- Tailwind utility classes are preferred over custom CSS unless a reusable component class is needed.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
