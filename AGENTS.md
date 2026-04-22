# AGENTS.md

> Guidelines for AI coding assistants (GitHub Copilot, Repo Assist, etc.) working in this repository.

## Project Overview

`my-awesome-repo` is currently in early setup. The repository has no source code yet — the focus has been on establishing community health files (CONTRIBUTING.md, CODE_OF_CONDUCT.md, SECURITY.md, LICENSE, etc.) via open draft pull requests.

## Repository Structure

| Path | Description |
|------|-------------|
| `README.md` | Project overview |
| `AGENTS.md` | This file — guidance for AI assistants |

*(Community health files are in pending draft PRs and will appear here once merged.)*

## Contribution Guidelines

- **Minimal changes**: Make the smallest change necessary to address the task. Avoid sweeping refactors.
- **One concern per PR**: Keep pull requests focused and easy to review.
- **No new dependencies**: Do not introduce external dependencies without prior discussion in an issue.
- **No breaking changes**: Never remove or rename public-facing interfaces without maintainer approval.

## Build & Test

There is no build or test pipeline configured yet. When a CI workflow is added, update this section with the commands to build, lint, and test the project.

## Notes for Repo Assist

- All reasonable community health files have been proposed. Do not create new community health file PRs until existing ones are reviewed.
- The `gh-aw/actions/setup-cli` version bump (tracked in issues #19–#22) requires `workflows` write permission — do not retry automated pushes; the maintainer must apply it manually.
- Issue triage and PR nudges are low-priority until the project gains source code contributors.
