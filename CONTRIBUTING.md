# Contributing

These defaults guide contributors and coding agents when a repository in this organization does not provide more specific instructions.
A repository's own `CONTRIBUTING.md`, `AGENTS.md`, `CLAUDE.md`, or equivalent workflow document takes precedence for that repository.

## Before changing files

Read the repository README and local instructions.
Open or identify an issue for a non-trivial change so the intended outcome and scope are reviewable before implementation.
Report security concerns through the private route in `SECURITY.md` instead of a public issue.

## Branches and commits

Do not commit or push directly to `main`.
Use a short branch name beginning with `feat/`, `fix/`, `docs/`, or `chore/`.
Keep one logical change in each commit, and write the commit message to explain why the change exists.

## Verification

Run the repository's documented checks before opening a pull request.
Add or update tests when behavior changes.
Record the commands and results in the pull request so a reviewer can reproduce them.

## Pull requests

Keep each pull request focused on one reviewable outcome.
Explain its purpose, governing issue or specification, verification evidence, and security or operational effects.
Resolve review conversations and keep required checks passing before merge.

Maintainers may close a proposal that conflicts with a repository's purpose, governing documentation, security boundary, or maintenance capacity.
