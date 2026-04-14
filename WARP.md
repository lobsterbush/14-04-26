# Thoughts on AI and Instruction

**Status:** Active
**Description:** Slide deck on challenges AI poses for education, featuring Kiln and deb8.tv.
**Authors:** Charles Crabtree, Senior Lecturer, School of Social Sciences, Monash University
**Last Updated:** 2026-04-14

## Tech Stack

- reveal.js 4.6.1 via CDN (no local install)
- Google Fonts: Space Grotesk, Inter, JetBrains Mono
- Single self-contained `index.html` — no build step
- GitHub Pages deployment from `master` branch root

## Deployment

- Repo: https://github.com/lobsterbush/14-04-26
- Live: https://lobsterbush.github.io/14-04-26/
- Push to `master` triggers automatic Pages rebuild

## Key Architecture

- Original dark theme (charcoal `#0f0f1a`, amber `#e8a838`, teal `#4ecca3`) — not based on any reveal.js theme package
- Built using `beautiful-deck` skill philosophy (assertion titles, MB/MC equivalence, no bullets) adapted for HTML output
- Screenshots (`kiln_hero.png`, `deb8_hero.png`, `ai_deb8_hero.png`) are local files referenced with relative paths
- `kiln_activities.png` is identical to `kiln_hero.png` (copied from Figures/)
- Links to usekiln.org, deb8.tv, ai.deb8.tv are live clickable links on title slide

## Content Sources

- Op-ed: "The University Is Not an Output Machine" (`~/Documents/GitHub/opeds/ai-university-oped.md`)
- Research: Crabtree, Holbein, Bosley & Sevi — AI prejudice reduction paper (conditionally accepted, PNAS Nexus)
- Kiln content from https://usekiln.org
- deb8/ai.deb8 content from https://deb8.tv and https://ai.deb8.tv
