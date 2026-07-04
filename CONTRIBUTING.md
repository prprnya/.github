# Contributing

Thanks for your interest in contributing.

This document is the default contributing guide for public repositories owned by [@prprnya](https://github.com/prprnya). Individual repositories may provide their own `CONTRIBUTING.md`; when they do, the repository-specific guide takes precedence.

## Before you start

Please keep contributions focused and easy to review. Small, well-scoped changes are preferred over large pull requests that mix unrelated fixes.

For substantial changes, architectural changes, new features, or behavior that may affect compatibility, please open an issue first so the direction can be discussed before implementation work begins.

## Issues

Use issues for:

- reproducible bugs
- feature requests
- documentation problems
- maintenance suggestions
- questions that are specific to a repository

When opening an issue, include enough context for someone else to understand and reproduce the problem. For bug reports, include the current behavior, expected behavior, reproduction steps, and relevant environment details.

Do not open public issues for security vulnerabilities or code of conduct reports. Report those privately using the channels described in [`SECURITY.md`](./SECURITY.md) and [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md).

## Pull requests

Pull requests should:

- address one topic at a time
- explain what changed and why
- include tests or verification steps when applicable
- update documentation when behavior, configuration, or public usage changes
- avoid unrelated formatting churn or dependency changes
- respect the license and attribution requirements of any code, assets, or documentation included in the change

A pull request may be closed without merge if it is out of scope, too broad to review, duplicates existing work, lacks enough context, or conflicts with the direction of the project.

## Commit messages

Clear commit messages are preferred. When practical, use a [Conventional Commits](https://www.conventionalcommits.org/)-style prefix, such as:

- `fix: correct incorrect behavior`
- `feat: add a small capability`
- `docs: update usage notes`
- `refactor: simplify implementation without changing behavior`
- `test: add or update tests`
- `chore: update maintenance files`

This is a preference, not a strict requirement unless a specific repository says otherwise.

## AI-assisted contributions

AI-assisted contributions are welcome when they are reviewed, understood, and tested by the contributor.

Do not submit generated changes that you cannot explain. You are responsible for checking correctness, licensing, attribution, security implications, and project fit before opening a pull request.

## Style and tooling

Follow the conventions already present in the repository you are contributing to. If a repository defines formatters, linters, tests, type checks, or build commands, run the relevant checks before submitting a pull request.

Avoid introducing new dependencies unless they are clearly justified.

## Repository-specific rules

This file provides default guidance. Repository-local files, scripts, documentation, issue templates, pull request templates, and maintainer comments override this document for that repository.

## Code of conduct

Participation in these repositories is governed by the [Code of Conduct](./CODE_OF_CONDUCT.md).
