# react-utility-hooks

A handful of React hooks I keep copy-pasting between projects

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Highlights

- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React
- useDebounce with leading/trailing options

## Installation

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── package.json
```
