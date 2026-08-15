# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a GitHub profile README repo (`ersanyamarya/ersanyamarya`) — the special repository GitHub renders on a user's profile page. It contains no application code, no build system, and no tests.

## Structure

- `README.md` — the profile content itself, rendered on github.com/ersanyamarya. Uses shields.io badges, simpleicons/svgporn CDN images for skill icons, and github-readme-stats/streak-stats for live stat cards.
- `assets/images/` — static images referenced by `README.md` (e.g. `header.png`, `mqtizer.png`), loaded via raw.githubusercontent.com URLs.

## Working in this repo

Edits here are almost always direct changes to `README.md` (bios, work experience, project links, badges) or adding/replacing images in `assets/images/`. There is nothing to build, lint, or test — verify changes by checking that Markdown renders correctly and that any new image paths/URLs resolve.

When editing `README.md`, keep the existing structure and formatting conventions (centered `<p>`/`<h1>` blocks, shields.io badge style, section dividers with `---`).
