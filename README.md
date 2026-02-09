<p align="center">
  <img alt="Kronk CMS" src="https://plugins.jetbrains.com/files/29886/950671/icon/default.svg" width="80">
</p>

<h1 align="center">Kronk CMS</h1>

<h3 align="center">You think it. AI creates it. Kronk safeguards it.</h3>

<p align="center">
  AI-native content management for JetBrains IDEs.
</p>

<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/29886-kronk-cms"><img src="https://img.shields.io/badge/version-2026.1.1-7C3AED.svg" alt="Version"></a>
  <a href="https://plugins.jetbrains.com/plugin/29886-kronk-cms"><img src="https://img.shields.io/badge/IntelliJ%20Platform-2023.3+-orange.svg" alt="IntelliJ Platform"></a>
  <a href="https://plugins.jetbrains.com/plugin/29886-kronk-cms"><img src="https://img.shields.io/badge/pricing-free-06B6D4.svg" alt="Free"></a>
  <a href="https://getkronk.com"><img src="https://img.shields.io/badge/web-getkronk.com-84CC16.svg" alt="Website"></a>
</p>

<p align="center">
  <img src="https://getkronk.com/assets/images/kronk-screenshots/ide-visual-canvas.png" alt="Kronk CMS - Visual Canvas" width="800">
</p>

---

## What is Kronk CMS?

Kronk is an IDE-native CMS built for the AI coding era. It manages Hugo, Jekyll, Astro, and 6 more static site generators directly inside your JetBrains IDE -- no browser tabs, no context switching.

Kronk detects your framework, organizes your content, installs addons, generates AI guardrails, and gives you a visual canvas for wireframing layouts. AI does the heavy lifting. Kronk makes sure it does it right.

## Features

### Multi-CMS Support

Manage 9 static site frameworks from a single tool window. Kronk auto-detects your framework from config files and adapts its UI accordingly -- content trees, addon sources, build commands, and deployment configs all adjust to your stack.

**Hugo** | **Jekyll** | **Astro** | **Next.js** | **Gatsby** | **Eleventy** | **Nuxt** | **Hexo** | **Strapi**

### Content Navigator

Hierarchical content tree with framework-aware collections, posts, pages, and data files. Filter by type, status, or directory. Navigate your entire site structure without leaving the IDE.

### Addon Manager

Browse and install themes, plugins, and integrations with one click. Supports npm, gem, go modules, and git sources. Only shows addons compatible with your detected framework. Built-in update checker keeps everything current.

### AI Integration

Generate configuration files for 4 AI coding assistants:

- **Claude Code** -- CLAUDE.md with framework-specific rules
- **Cursor** -- .cursorrules for Cursor AI
- **Windsurf** -- rules.md for Windsurf
- **Antigravity** -- config.yaml for Antigravity

Each tool gets organized rules in `.kronk/` subdirectories. The Context Builder copies rich project context to your clipboard for pasting into any AI tool.

### Visual ASCII Builder

Draw page layouts on a visual canvas using drag-and-drop components (Header, Nav, Sidebar, Content, Footer). Export as ASCII art that AI tools can interpret and turn into real templates. Component palette included.

### Quality Dashboard

Built-in auditing for content quality:

- **SEO** -- Title length, meta descriptions, heading hierarchy, alt text
- **Accessibility** -- WCAG 2.1 AA compliance checks
- **Performance** -- Image optimization, lazy loading, modern formats

### Media Gallery

Thumbnail browser for all media assets in your project. Drag-and-drop support for adding images to content files.

### Deployment

Generate deployment configs for popular hosting platforms:

- **Netlify** | **Vercel** | **Cloudflare Pages** | **GitHub Pages** | **AWS S3** | **Firebase**
- CI/CD templates for **GitHub Actions**, **GitLab CI**, **Bitbucket Pipelines**, **CircleCI**
- SSH/rsync deployment with key, agent, or password authentication

### Dev Server Management

Start, stop, and monitor your framework's dev server directly from the IDE. Live output in the tool window.

## Supported Frameworks

| Framework | Config Detection | Content Directory | Package Manager |
|-----------|-----------------|-------------------|-----------------|
| **Hugo** | hugo.toml, config.toml | content/ | go modules |
| **Jekyll** | _config.yml | _posts/, _pages/ | gem |
| **Astro** | astro.config.mjs | src/content/ | npm |
| **Next.js** | next.config.js | pages/, app/ | npm |
| **Gatsby** | gatsby-config.js | src/pages/ | npm |
| **Eleventy** | .eleventy.js | src/, content/ | npm |
| **Nuxt** | nuxt.config.js | pages/, content/ | npm |
| **Hexo** | _config.yml | source/_posts/ | npm |
| **Strapi** | config/database.js | src/api/ | npm |

## Getting Started

1. **Install** from the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/29886-kronk-cms)
2. **Open** any supported static site project
3. **Find** the Kronk CMS tool window in the sidebar
4. **Explore** Content, Addons, AI Rules, Visual Builder, and Deployment tabs

## Kronk CLI

Kronk also ships as a standalone CLI for terminal-based workflows. The CLI provides framework detection, guardrail generation, content scaffolding, quality audits, and 12 AI methodology skills for Claude Code.

```bash
npm install -g kronk-cms
```

- **npm:** [@aivorynet/kronk-cli](https://www.npmjs.com/package/@aivorynet/kronk-cli)
- **GitHub:** [aivorynet/kronk-cms](https://github.com/aivorynet/kronk-cms)

The IDE plugin and CLI are complementary -- the plugin provides the visual interface, the CLI provides the terminal workflow and AI skills.

## Requirements

- **IntelliJ IDEA 2023.3+** (Community or Ultimate)
- **WebStorm**, **PhpStorm**, **GoLand**, **RubyMine**, **PyCharm**, **Rider**, **CLion** also supported
- **Java 17+** (included with JetBrains Runtime)

## This Repository

This repository is the public issue tracker for the Kronk CMS JetBrains plugin. It does not contain source code.

**Use it to:**

- [Report bugs](https://github.com/aivorynet/kronk-jetbrains/issues/new?template=bug_report.md)
- [Request features](https://github.com/aivorynet/kronk-jetbrains/issues/new?template=feature_request.md)
- Browse [open issues](https://github.com/aivorynet/kronk-jetbrains/issues)

## Links

- **Website:** [getkronk.com](https://getkronk.com)
- **JetBrains Marketplace:** [Kronk CMS](https://plugins.jetbrains.com/plugin/29886-kronk-cms)
- **CLI (npm):** [@aivorynet/kronk-cli](https://www.npmjs.com/package/@aivorynet/kronk-cli)
- **CLI (GitHub):** [aivorynet/kronk-cms](https://github.com/aivorynet/kronk-cms)
- **Company:** [AIVory, Inc.](https://aivory.net)

