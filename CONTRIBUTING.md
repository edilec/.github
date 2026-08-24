# Contributing to Edilec repositories

Thank you for considering a contribution. This document is the default for
public Edilec repositories that do not publish a more specific contribution
guide.

## Start with the project boundary

Read the repository README, licence, open issues, and any architecture or
security documentation before proposing work. A repository-specific guide
overrides this file.

For a bug, provide a minimal reproduction before preparing a broad change. For
a feature, explain the user problem, alternatives considered, compatibility
impact, and expected maintenance cost. Opening an issue first is useful for
large or behavior-changing proposals, but it does not reserve the work or
guarantee acceptance.

Suspected vulnerabilities must follow [`SECURITY.md`](./SECURITY.md), not a
public issue or pull request.

## Prepare a focused change

1. Create a branch from the repository's default branch.
2. Keep the change limited to one clear problem.
3. Add or update tests for behavior changes where the project has tests.
4. Run the documented formatting, linting, type-checking, test, and build commands.
5. Update user-facing documentation and release notes when behavior changes.
6. Explain what you verified and any remaining limitation in the pull request.

Do not include credentials, customer or personal data, private infrastructure
details, unpublished vulnerability information, or third-party code that you
do not have permission to contribute.

## Provenance and licences

Contributors must have the right to submit their work. Preserve upstream
copyright, licence, NOTICE, and attribution requirements. Identify forks,
templates, generated material, and substantial third-party sources accurately.

Unless a repository says otherwise, a contribution is submitted under that
repository's existing licence. A repository without a licence is not an
invitation to copy or redistribute its contents.

## Review and acceptance

Maintainers may request tests, documentation, narrower scope, design changes,
or security review. They may decline a change that conflicts with the project
boundary, duplicates planned work, creates unsupported maintenance cost, or
lacks clear provenance.

Review availability varies by project. These defaults do not promise a
response or merge time.

Participation is subject to the [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md).
