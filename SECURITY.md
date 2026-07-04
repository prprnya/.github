# Security Policy

This is the default security policy for public repositories owned by [@prprnya](https://github.com/prprnya). Individual repositories may provide their own `SECURITY.md`; when they do, the repository-specific policy takes precedence.

## Reporting a vulnerability

Please do not report security vulnerabilities through public GitHub issues, pull requests, discussions, or comments.

Report potential vulnerabilities privately by email: <security@prpr.cat>.

Please include:

- the affected repository
- the affected version, commit, branch, deployment, or URL if known
- a clear description of the issue
- reproduction steps or proof of concept, if available
- expected impact
- any relevant logs, screenshots, or environment details
- whether the issue has been disclosed elsewhere

Reports may be written in English or Chinese.

## Scope

This policy applies by default to public repositories owned by [@prprnya](https://github.com/prprnya) that do not define their own security policy.

The following are generally in scope:

- vulnerabilities in source code maintained in the repository
- insecure default configuration
- exposed secrets committed to a repository
- dependency or build configuration issues with practical security impact
- documentation that could cause unsafe deployment or use

The following are generally out of scope unless a repository says otherwise:

- vulnerabilities in third-party services or platforms not controlled by the repository
- automated reports without a practical exploit scenario
- social engineering
- spam, phishing, or abuse unrelated to a maintained repository
- denial-of-service testing
- destructive testing or attempts to access, modify, or exfiltrate data

## Safe testing expectations

When researching or reporting a vulnerability:

- avoid accessing data that does not belong to you
- avoid destructive testing
- avoid service disruption
- do not publicly disclose the issue before there has been a reasonable opportunity to review and address it
- stop testing and report promptly if you encounter sensitive data or unintended access

## Handling process

Reports will be reviewed as availability allows. If the report appears valid and actionable, I will try to coordinate a fix and disclosure in a way that is proportionate to the severity and practical impact of the issue.

No fixed response time or bounty is promised by this policy.

## Code of conduct reports

For harassment, abuse, or other code of conduct concerns, follow the reporting instructions in `CODE_OF_CONDUCT.md`.
