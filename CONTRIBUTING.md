# Contributing Guidelines

Thanks for contributing to this project. This document explains the coding standards and pull request process we use.

## Getting Started

1. Fork or branch from `master`.
2. Keep changes focused on a single purpose.
3. Test your changes locally before opening a PR.

## Coding Standards

### General

- Prioritize readability over cleverness.
- Keep functions and modules small and focused.
- Avoid introducing unused code, dependencies, or files.
- Use clear names for variables, functions, and files.
- Keep comments concise and only where behavior is not obvious.

### HTML/CSS/JS Conventions

- Use semantic HTML elements when possible.
- Keep indentation consistent (2 spaces in frontend files unless a file already uses a different style).
- Prefer simple, dependency-free JavaScript for small interactions.
- Avoid inline styles/scripts when a separate block or file is clearer.

### Quality Expectations

- Ensure no obvious console errors or runtime regressions.
- Keep browser behavior consistent for modern evergreen browsers.
- Run formatting/linting tools if configured in the repository.

## Pull Request Process

### Before Opening a PR

- Confirm your branch is up to date with `master`.
- Review your own diff and remove accidental changes.
- Verify the change solves the intended issue.

### PR Requirements

Each pull request should include:

- A clear title describing the change.
- A short summary of what changed and why.
- Testing notes (what you tested and expected result).
- Screenshots or recordings for visible UI changes.

### Scope and Review

- Keep PRs small and focused to make review easier.
- Address reviewer feedback with follow-up commits.
- Do not force-push over reviewed history unless requested by maintainers.

### Merge Expectations

- PRs should be approved before merge.
- Ensure checks are green (if CI is configured).
- Squash or rebase according to maintainer guidance.

## Commit Message Guidance

- Use descriptive, imperative commit messages.
- Recommended format:
  - `docs: add contributing guidelines`
  - `fix: correct button alignment on home page`
  - `feat: add keyboard navigation for menu`

## Questions

If something is unclear, open a draft PR and ask for early feedback.
