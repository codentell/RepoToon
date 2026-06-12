# Changelog

## v0.2.0 — The Breaking Storm

- feat: episode hub page with automatic episode listing
- feat: panel-level changelog citations
- fix: crash when a release body contained more than 64 entries
- fix: memory leak in the renderer made long episodes unreadable
- BREAKING CHANGE: episode config migrated from JSON to TOML; `repotoon.json` is no longer read
- chore: bump dependencies

## v0.1.0 — First Panel

- feat: dramatize GitHub release notes into webtoon panels
- feat: autonomous publish to GitHub Pages on every release
- fix: dialogue bubbles overflowed narrow panels
- chore: initial CI setup
