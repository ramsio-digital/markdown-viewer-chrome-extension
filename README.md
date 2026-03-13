# RAMSIO Markdown Viewer — Chrome Extension

A free Chrome extension that renders Markdown files beautifully in your browser — with 3 themes, PDF/HTML export, Mermaid diagrams, KaTeX math, and GitHub/GitLab/Bitbucket integration. No sign-up, no telemetry, fully offline processing.

## Features

- **3 Themes** — GitHub (light), Professional (business), Minimal (distraction-free)
- **Color Scheme** — Light, Dark, and Auto (follows system preference)
- **Mermaid Diagrams** — Flowcharts, sequence diagrams, class diagrams, and more
- **Math Equations** — KaTeX rendering for inline and display math
- **Syntax Highlighting** — Code blocks with Prism.js
- **Export** — PDF (via print dialog) and self-contained HTML
- **Document Outline** — Auto-generated heading hierarchy (H1–H6) with click-to-jump navigation
- **Document Statistics** — Word count, character count, estimated reading time
- **Platform Integration** — Right-click "Preview with RAMSIO Markdown Viewer" on GitHub, GitLab, and Bitbucket
- **File Upload** — Open local .md, .markdown, or .txt files via file picker or drag-and-drop
- **Zoom Controls** — 75%–200% in 25% increments
- **Zero Telemetry** — No data collection, no analytics, no external network calls

## Privacy

This extension collects **zero personal data**. All Markdown processing happens entirely within your browser. No file content, browsing data, or personal information is ever transmitted to any server. The extension makes zero outbound network requests beyond user-initiated file fetches from allowed domains (GitHub, GitLab, Bitbucket).

Settings are stored locally via Chrome's `chrome.storage.local` API and are automatically deleted when you uninstall the extension.

Read our full [Privacy Policy](https://www.ramsio.tools/legal/privacy).

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Shift+M` | Open extension |
| `Ctrl+Shift+P` | Preview current Markdown file |
| `Alt+O` | Toggle Document Outline |
| `Ctrl+I` | Show Document Statistics |
| `Alt+H` | Export to HTML |
| `Ctrl+P` | Print / Export to PDF |
| `F11` | Toggle Fullscreen |
| `F1` | Help |
| `Ctrl++` / `Ctrl+-` | Zoom in / out |
| `Ctrl+0` | Reset zoom |

## Context Menu

Right-click on any page to access:
- **Preview with RAMSIO Markdown Viewer** — Open a markdown link in the viewer
- **Preview Selected Markdown** — Render selected text as Markdown
- **Export to HTML / PDF** — Available when viewing a preview
- **Settings** — Quick access to extension settings

## Settings

| Setting | Options | Default |
|---|---|---|
| Color Scheme | Light / Dark / Auto | Auto |
| Theme | GitHub / Professional / Minimal | GitHub |
| Default Zoom | 75%–200% (25% steps) | 100% |
| Show Outline | On / Off | On |
| Show Statistics | On / Off | Off |
| Enable Mermaid | On / Off | On |
| Enable Math | On / Off | On |
| Syntax Highlighting | On / Off | On |
| Auto Theme | On / Off | On |
| Auto Save | On / Off | On |
| Update Notifications | On / Off | On |

## Supported Sites

- GitHub (github.com, raw.githubusercontent.com, gist.github.com)
- GitLab (gitlab.com)
- Bitbucket (bitbucket.org)
- Local files (file:// URLs — requires enabling "Allow access to file URLs" in Chrome extension settings)

## System Requirements

- Google Chrome 110 or later (Manifest V3)
- Works on Windows, macOS, Linux, and Chrome OS
- No internet required — works entirely offline

## Feedback & Support

This repository is the public issue tracker for RAMSIO Markdown Viewer Chrome Extension.

- **Report a bug** — [Open a bug report](../../issues/new?template=bug_report.md)
- **Request a feature** — [Open a feature request](../../issues/new?template=feature_request.md)
- **Email support** — [support@ramsio.tools](mailto:support@ramsio.tools)
- **Support page** — [www.ramsio.tools/support](https://www.ramsio.tools/support)

## Legal

- [Privacy Policy](https://www.ramsio.tools/legal/privacy)
- [Terms of Service](https://www.ramsio.tools/legal/terms)
- [EULA](https://www.ramsio.tools/legal/eula)

## About

Published by **RAMSIO Digital** — a GST-registered sole proprietorship based in Bengaluru, India.

- Website: [www.ramsio.tools](https://www.ramsio.tools)
- Corporate: [www.ramsiodigital.com](https://www.ramsiodigital.com)

© 2025–2026 RAMSIO Digital. All rights reserved.
