# Sol + Jev Android UI Testing Blueprint

A self-contained HTML architecture and implementation proposal for a mobile UI tester using a strong planning model, Jev for focused visual decisions, and a local runner over ADB or raw mobile MCP.

**Read online:** [HTML proposal](https://samir-sayyed.github.io/sol-jev-android-ui-testing/)

## Contents

- Planner, runner, visual model and device responsibilities
- Execution loop, immutable assertions and typed plan contracts
- Jev HTTP example, image preparation and coordinate mapping
- Proposed Python module layout and event schema
- Interactive routing simulation and editable latency/cost calculator
- Six implementation stages and a three-arm benchmark plan
- Primary documentation and explicit evidence status

## Open locally

Open `index.html` directly in a browser. No install, build or network request is needed for the page, calculator or routing simulation. Only the optional theme preference uses localStorage. External documentation links open only when clicked.

Alternatively:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit <http://127.0.0.1:8000>.

## Status

This repository contains a design document, not a working Android test runner. The device runner, provider integrations and benchmark suite are proposed implementation work. Embedded examples are labeled; no mobile execution or provider API requests are performed by the HTML.

Calculator defaults are hypothetical assumptions, not measured latency, verified savings or provider price quotes. Jev image and Box support is experimental according to the linked TypeSafe documentation checked on 15 October 2026.

The design is inspired by narrow decision models. No THUD integration is proposed.

## Files

- `index.html` — standalone document, styles and interactive components
- `social-preview.png` — sharing preview
- `apple-touch-icon.png` — optional browser icon
- `.nojekyll` — publish plain static HTML with GitHub Pages

## Publication

GitHub Pages serves `main` at the repository root. No workflow, API keys, test screenshots, project source or private data are required.
