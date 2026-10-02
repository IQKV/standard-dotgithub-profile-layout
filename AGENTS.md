# AI Agent Development Guide

## Project Overview

**standard-dotgithub-profile-layout** — Template for GitHub organization profile repositories (`.github` profile). Contains the `profile/README.md` rendered on the GitHub organization page and brand assets.

**Key characteristics:**

- No application code — Markdown, images, and brand assets only
- Node.js tooling (pnpm + Husky) for commit hooks and formatting only
- OxFmt for formatting, Stylelint for CSS

## Execution Discipline

- Read the existing file before editing it.
- No speculative additions — change only what the request requires.
- After two identical failures without new evidence, change approach.

## Security

- Keep credentials and tokens out of commits and shared text.
- Do not include personal contact details or internal URLs in profile content.
- Flag unusual package names before installing.
- Never bypass `--no-verify` unless explicitly requested.

## AI Agent Guidelines

- **Ask before applying**: describe the change, wait for approval.
- **Approval phrases**: "Yes", "Proceed", "Apply", "Do it", "Looks good"
- **Never create** summary or review markdown files automatically.
- Content changes to `profile/README.md` are the primary work — keep them factual and accurate.

## Commit Standards

Format: `type(scope): subject`

- Subject: imperative, lowercase, no trailing period, ≤ 72 chars
- Types: `feat`, `fix`, `docs`, `style`, `chore`, `ci`, `revert`
- Scope: affected area (e.g., `profile`, `brand`, `deps`)
- For `fix`: symptom + trigger, not the code change

Examples:

- `docs(profile): update tech stack badges`
- `feat(brand): add dark mode logo variant`
- `chore(deps): update oxfmt`
