# .github

Default community health files for repositories owned by [@prprnya](https://github.com/prprnya).

This repository provides fallback community files for my public GitHub repositories. When an individual repository defines its own version of one of these files, the repository-specific file takes precedence.

## Included files

| File | Purpose |
| --- | --- |
| `CODE_OF_CONDUCT.md` | Defines expected community behavior and private reporting instructions for possible violations. |
| `CONTRIBUTING.md` | Provides default contribution guidance for issues, pull requests, commit messages, tooling, and AI-assisted contributions. |
| `SECURITY.md` | Explains how to privately report potential security vulnerabilities. |
| `SUPPORT.md` | Explains where to ask questions, report problems, request features, and find the correct private reporting channel. |
| `.github/ISSUE_TEMPLATE/` | Provides default issue forms and issue chooser configuration. |
| `.github/pull_request_template.md` | Provides the default pull request template. |

## How defaults work

GitHub uses supported files from this repository as defaults for repositories that do not provide their own corresponding files.

Repository-local files are authoritative. If a repository has its own `CONTRIBUTING.md`, `SECURITY.md`, issue templates, pull request template, or other community files, follow that repository's version instead of this default.

## Reporting privately

Do not use public issues, pull requests, discussions, or comments for security vulnerabilities or Code of Conduct reports.

Use the relevant policy instead:

- Security vulnerabilities: see [`SECURITY.md`](SECURITY.md)
- Code of Conduct reports: see [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md)

## Not provided by this repository

This repository does not provide a default license. Licenses should be added to individual repositories so that they are included when those repositories are cloned, downloaded, or packaged.

This repository also does not replace repository-specific documentation, build instructions, release notes, roadmaps, or maintainer decisions.
