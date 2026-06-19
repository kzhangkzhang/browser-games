# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A collection of small browser games, each a single self-contained `.html` file (inline `<style>` and `<script>`, no external assets, no build step, no package manager). Currently: `tic-tac-toe.html`, `shooter.html` (top-down shooter with Web Audio synthesized sound effects, no audio files).

When adding a new game, follow the same pattern: one HTML file at the project root with embedded CSS/JS, runnable by opening directly in a browser.

## Running / previewing

No dev server or build step. Open a game directly, e.g.:

```
start "F:/tmp/ClaudeCodePOC/shooter.html"
```

## Git workflow

- Commit and push to `origin/master` after every meaningful change — don't wait to be asked.
- Commit directly to `master`; no feature branches or PRs for this solo project.
- Still ask before any destructive git operation (force-push, history rewrite, reset --hard, etc.).
- Git identity for this repo: `Kevin Zhang <kezhangkezhang@gmail.com>`.
