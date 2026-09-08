# readmeter

MV3 extension playground: page reading-time estimator

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## What it does

- No remote calls, everything stays local
- Manifest V3, service worker based
- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```
