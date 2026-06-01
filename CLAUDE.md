# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository status

This repository (`talakanzel-lab/-`) is currently a fresh, empty project. The only tracked file is a placeholder `README.md`. There is no source code, build system, dependency manifest, test suite, or tooling configuration yet.

Because nothing has been established, there are no project-specific build, lint, test, or run commands to document at this time. Do not assume a language, framework, or toolchain — none has been chosen.

## Working in this repository

When the first real code is introduced, the choices made at that point define the project's conventions. Pay attention to and follow whatever is established by the initial scaffolding:

- The language and package manager (e.g. the presence of `package.json`, `pyproject.toml`, `go.mod`, `Cargo.toml`, etc.) determines build/test/run commands.
- Any tooling config that appears (linters, formatters, CI workflows under `.github/workflows/`) defines the expected quality gates — run them before committing.

## Maintaining this file

This CLAUDE.md should be updated as soon as the codebase takes shape. Once code exists, replace this section with concrete guidance:

1. **Commands** — the actual build, lint, test, and run commands, including how to run a single test.
2. **Architecture** — the big-picture structure that spans multiple files and isn't obvious from a quick directory listing.

Keep it specific to what is actually in the repo; remove this placeholder content once it no longer applies.
