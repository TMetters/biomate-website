# CLAUDE.md — BioMate Website

> For full global rules, see ~/.claude/CLAUDE.md. This file contains project-specific overrides and context.

---

## Project Identity

- **Name:** BioMate Marketing Website
- **Type:** Static marketing site
- **Domain:** biomate.education
- **Users:** Prospective users — IB DP Biology teachers discovering BioMate
- **Deployment:** GitHub Pages (CNAME configured)
- **Repository:** https://github.com/TMetters/biomate-website
- **Goal:** Convert visitors into BioMate subscribers — credible, professional, compelling

## Tech Stack

- Static HTML, CSS, JavaScript (no framework, no build step)
- Images: WebP format preferred (PNG as fallback)
- Hosted via GitHub Pages
- No server-side code, no API keys, no environment variables

## Visual Identity

- Primary font: Montserrat (Google Fonts)
- Navy: `#0d2240`
- Blue: `#0099d6`
- Red: `#cc0011`
- White: `#ffffff`
- Tone: Professional, credible, international — targeting IB Biology teachers globally
- Do NOT use generic AI aesthetics, purple gradients, or informal styling

## Core Rules (Every Session)

1. Always read a file fully before editing it
2. Never rewrite whole files — make targeted edits only
3. After every edit, run: `git diff` to show exactly what changed
4. After every edit, run: `git add . && git commit -m "auto: [describe change]"`
5. Never use `cp` to overwrite a file — always edit in place
6. Check for broken paths, missing tags, and syntax errors after every change
7. If unsure about a path or filename, list the directory first before acting

## Branch Rules

- Always work on the `agent-work` branch (current: `agent-work-20260517`)
- Never commit to `main`
- Thomas reviews and merges — never auto-deploy

## Security Rules

- Never read, print, or `cat` any `.env` file under any circumstances
- No API keys or secrets belong in this repository

## Autonomous Operation

- Work through tasks without asking for confirmation
- Make sensible decisions and keep moving
- Only stop if genuinely blocked on ambiguous project-specific details
