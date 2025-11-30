# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository status

As of now, this repository only contains the Git metadata directory (`.git`) and no source files, configuration files, or documentation (for example, there is no `README.md`, `package.json`, `pyproject.toml`, or similar tooling file at the project root).

Because there is no visible application code or build/test configuration yet, there are currently no project-specific commands or architectural patterns to document.

## Commands

No standard build, lint, or test commands can be inferred yet.

When project tooling is added (for example, a language-specific build system, test runner configuration, or task runner scripts), update this section with concrete commands for:
- Building the project
- Running the full test suite
- Running a single test or subset of tests
- Running any project-specific linters or formatters

## Future architecture notes

Once source code and configuration files are added, future instances of Warp should:
- Inspect the top-level directories (for example, `src`, `app`, `backend`, `frontend`) and language-specific entrypoints to infer the high-level architecture.
- Identify framework- or library-specific conventions (for example, Next.js `app/` versus `pages/`, Django `manage.py` and `settings.py`, etc.).
- Summarize the main modules and how they depend on each other at a high level (without listing every single file).

At that point, extend this file with:
- A concise overview of the main components/services and how they interact.
- Any project-specific rules or preferences for AI assistants (coding style, file organization, or tool choices) that are not already encoded elsewhere (for example, in `CLAUDE.md`, `.cursorrules`, or Copilot instructions).
