# Contributing to KAYVRA

Thank you for your interest in contributing to KAYVRA projects. These guidelines help us keep collaboration clear, reviewable, and secure.

## 1. Before You Start

- Check the repository README and any project-specific contribution instructions.
- Review existing Issues and Pull Requests before opening a new one.
- For substantial changes, open an Issue first to discuss the problem, scope, and proposed approach.
- Do not begin security testing against any system unless you have explicit authorization and a clearly defined scope.

## 2. Choose or Create an Issue

Use an Issue to describe a bug, improvement, research task, or documentation change.

A useful Issue includes:
- A concise title.
- Context and expected outcome.
- Reproduction steps, where relevant.
- Relevant versions, environment details, and sanitized logs.
- Acceptance criteria for larger tasks.

Do not include credentials, API keys, personal information, client data, private logs, or digital-forensic evidence.

## 3. Branching

Do not commit directly to the default branch unless a repository maintainer has explicitly approved an exceptional change.

Use descriptive branch names, for example:

- `feature/add-detection-rule`
- `fix/parser-validation`
- `docs/update-installation-guide`
- `research/log-analysis-study`

Keep changes focused. Avoid mixing unrelated fixes, formatting changes, and features in one Pull Request.

## 4. Commit Messages

Write short, descriptive commit messages. We recommend this pattern:

`type: concise description`

Examples:
- `feat: add event normalization`
- `fix: handle empty input safely`
- `docs: clarify deployment steps`
- `test: add parser regression cases`

## 5. Quality and Security Checks

Before opening a Pull Request:

- Run the relevant tests and checks.
- Review your own diff for accidental changes.
- Update documentation when behavior or setup instructions change.
- Remove temporary files, local databases, build outputs, and unrelated artifacts.
- Never commit secrets, private keys, tokens, passwords, or populated environment files.
- Never commit real client data, personal information, production logs, or investigation evidence.
- Use synthetic or properly sanitized data in examples and tests.
- Confirm that any security testing described in the contribution was authorized.

## 6. Pull Requests

A Pull Request should:
- Explain what changed and why.
- Link the related Issue when one exists.
- Describe tests performed and their results.
- Include safe screenshots or sample output when useful.
- Identify known limitations or follow-up work.
- Confirm that no secrets or sensitive data are included.

A maintainer may request changes, additional tests, or documentation before merging.

## 7. Review and Merging

- Be respectful and constructive during review.
- Address review comments or explain why a suggestion is not applicable.
- Do not merge your own change when repository policy requires independent review.
- Follow any additional branch protection or release rules configured for the repository.

## 8. Responsible Security Reporting

Do not report exploitable vulnerabilities in public Issues or Pull Requests. Follow the instructions in [SECURITY.md](SECURITY.md) instead.

## 9. Project-Specific Rules

A repository may define stricter requirements for its language, tooling, tests, licensing, data handling, or release process. Those requirements take precedence where they are more specific.

Thank you for helping us build and maintain useful, responsible security work.
