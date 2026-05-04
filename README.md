[![BeLikeNative](https://img.shields.io/badge/by-BeLikeNative-2563eb)](https://belikenative.com) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) [![GitHub Actions](https://img.shields.io/badge/CI-passing-brightgreen)]()

# BeLikeNative Website Grader

A free, instant website performance grader. Analyze speed, SEO, accessibility, and best practices with Google Lighthouse data.

**[Try it live](https://theluckystrike.github.io/bln-website-grader/)** — no signup required.

## Features

- **Performance** — Core Web Vitals, load time, resource optimization
- **SEO** — Meta tags, headings, structured data, crawlability
- **Accessibility** — WCAG compliance, contrast ratios, ARIA attributes
- **Best Practices** — HTTPS, image optimization, JavaScript errors

## How It Works

1. Enter any URL
2. The grader runs a Lighthouse audit via the PageSpeed Insights API
3. Get an instant report with scores, metrics, and actionable recommendations

No API key required. No signup. Completely free.

## Tech Stack

- Single-page HTML/CSS/JS application
- Google PageSpeed Insights API (public, no key needed)
- Hosted on GitHub Pages

---

## BeLikeNative Developer Tools

This tool is part of the **[BeLikeNative](https://belikenative.com)** ecosystem — AI-powered writing tools for non-native English speakers.

| Tool | Type | Description |
|------|------|-------------|
| [Grammar Check](https://github.com/theluckystrike/belikenative-grammar-check) | GitHub Action | PR grammar checker with 60 rules and L1-aware insights |
| [Writing Assistant](https://github.com/theluckystrike/bln-writing-assistant) | GitHub Action | Writing quality analysis: readability, structure, clarity |
| [i18n Checker](https://github.com/theluckystrike/bln-i18n-checker) | GitHub Action | Find hardcoded strings that need internationalization |
| [Commit Lint](https://github.com/theluckystrike/bln-commit-lint) | GitHub Action | Commit message grammar, format & clarity checker |
| [MCP Grammar Server](https://github.com/theluckystrike/bln-mcp-grammar-server) | MCP Server | 70 local grammar rules for Claude Desktop & Cursor |

**[BeLikeNative Chrome Extension](https://chromewebstore.google.com/detail/belikenative-ai-writing-a/gchojmpfpbpmpfgdppfdkpchikbcgabp)** — AI writing assistant for 100+ languages, 15 tones, 15 styles. 10,000+ users, 4.6★ rating.

## License

MIT
