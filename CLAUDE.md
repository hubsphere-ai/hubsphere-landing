# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

```bash
npm start       # Dev server at localhost:3000
npm test        # Run tests (watch mode)
npm run build   # Production build
```

To run a single test file: `npm test -- --testPathPattern=App`

## Architecture

This is a Create React App (React 19) project bootstrapped with `react-scripts`. The codebase is currently in its early stages with the default CRA template as a starting point for the HubSphere landing page.

- `src/App.js` — Root component; primary entry point for all UI work
- `src/index.js` — Mounts the React tree into `public/index.html`
- `public/` — Static assets served as-is (favicon, manifest, robots.txt)

ESLint uses the `react-app` config (no separate `.eslintrc`); linting runs automatically during `npm start` and `npm test`.
