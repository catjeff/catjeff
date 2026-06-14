# Repository Guidelines

## Project Structure & Module Organization

This repository currently contains a single `README.md`, which appears to be the GitHub profile README for `catjeff/catjeff`. There is no application source tree, test suite, package manifest, or asset directory yet.

When adding project code, keep the structure explicit and predictable:

- `src/` for application or library source code.
- `tests/` for automated tests that mirror the source layout.
- `assets/` for images, static files, or other non-code resources.
- `docs/` for longer documentation that does not belong in `README.md`.

Keep the root directory limited to repository-level files such as `README.md`, `AGENTS.md`, license files, and build or package configuration.

## Build, Test, and Development Commands

No build or test commands are defined at this time. Before introducing tooling, add the relevant manifest or config file and document the command in `README.md`.

Examples for future projects:

- `npm test` for a JavaScript or TypeScript test suite.
- `npm run lint` for linting and formatting checks.
- `make build` for projects that standardize workflows through a `Makefile`.

Prefer a small, memorable command set over many overlapping scripts.

## Coding Style & Naming Conventions

Follow the conventions of the language or framework introduced by future changes. Keep formatting automated where possible, and commit the formatter or linter configuration with the code it governs.

Use clear, descriptive names. For Markdown files, prefer uppercase repository-standard names such as `README.md` and `AGENTS.md`; for documentation pages under `docs/`, use lowercase kebab-case such as `setup-guide.md`.

## Testing Guidelines

There is no testing framework configured yet. When code is added, include tests for behavior that can regress and document how to run them.

Use test names that describe expected behavior, not implementation details. Keep tests close enough to the source layout that contributors can find the relevant coverage quickly.

## Commit & Pull Request Guidelines

The Git history currently contains only `Initial commit`, so no detailed commit convention is established. Use short, imperative commit subjects, for example `Add profile README sections` or `Document setup steps`.

Pull requests should include a concise summary, the reason for the change, and any verification performed. For visual README or documentation changes, include screenshots or rendered previews when useful.

## Agent-Specific Instructions

Before editing, check whether requested files already exist and avoid overwriting user-authored content. Keep repository guidance concise and update this file when project structure, commands, or contribution workflows change.
