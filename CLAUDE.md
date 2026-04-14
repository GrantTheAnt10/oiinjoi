# CLAUDE.md

## Repository Overview

This repository contains **RAGDOLL PLAYGROUND** — a browser-based, zero-dependency ragdoll physics simulation built with a single HTML file.

## Project Structure

```
Main/
  rgplayground.html   # The entire application (HTML + CSS + JS, self-contained)
README.md
```

## Development

There is no build step, package manager, or test suite. The project is a single self-contained HTML file.

To run locally, open `Main/rgplayground.html` directly in a browser (no server required).

## Key Notes

- All source code lives in `Main/rgplayground.html` — HTML, CSS, and JavaScript are all inline.
- No external runtime dependencies (Google Fonts are loaded via CDN for the UI only).
- No linter, bundler, or test runner is configured.
- Changes can be validated by opening the file in a browser and interacting with the simulation.
