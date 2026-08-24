# Governance

## Ownership and scope

Edilec Private Limited owns this account-wide defaults repository. Individual
repositories may publish their own governance, maintainer, security, and
release rules; those project-specific files take precedence.

These defaults do not create Edilec ownership or release authority over an
upstream project represented by a transparent GitHub fork.

## Roles

**Maintainers** are authorized to review changes, set project boundaries,
manage issues, prepare releases, and protect security and licence obligations.
The current accountable maintainer is listed in [`MAINTAINERS.md`](./MAINTAINERS.md).

**Contributors** propose code, documentation, tests, reviews, issue reports, or
other project improvements. Contribution does not by itself grant release,
administrative, or ownership authority.

Automated accounts may open clearly identified dependency or maintenance
changes, but automation does not replace human review for releases or
security-sensitive decisions.

## Decisions

Maintainers evaluate proposals using evidence relevant to the repository,
including correctness, user impact, security, compatibility, provenance,
maintenance cost, and project scope. Decisions should be recorded in an issue,
pull request, release note, or architecture record when the context is useful
to future maintainers.

Routine changes may be approved by one accountable maintainer. Changes to
licensing, security boundaries, release permissions, repository visibility,
canonical ownership, or published support commitments require explicit Edilec
owner review.

## Releases and maintenance status

Only an authorized maintainer may publish a release. A release must follow the
checks documented by its repository; the absence of an automated check is not
evidence that the release is safe.

Repositories should state whether they are experimental, maintained, stable,
deprecated, or archived. Maintenance priorities may change, and this policy
does not create a release or response schedule.

## Maintainer changes and disputes

Maintainer appointments and removals are decided by the Edilec account owner
and should be documented in a reviewed change to `MAINTAINERS.md`. Conduct
concerns follow [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md). A maintainer with
a direct conflict should not make the final enforcement decision.
