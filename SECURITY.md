# Security policy

This is the default security policy for public Edilec repositories that do not
provide their own `SECURITY.md`. A repository-specific policy always takes
precedence.

## Supported versions

Check the affected repository for a support matrix or maintenance notice. When
none is published, only the latest stable release is considered for a security
fix, and support is assessed case by case. Experimental, archived, and
explicitly unsupported projects may not receive a fix.

## Report a vulnerability privately

Do not open a public issue, discussion, or pull request for a suspected
vulnerability. Email [hello@edilec.com](mailto:hello@edilec.com) with the
subject **Security report** and include:

- the affected repository, version, and commit when known;
- the security impact and conditions required to reproduce it;
- a minimal, non-destructive reproduction;
- the expected and observed behavior; and
- a safe way to contact you about the report.

Include only the data needed to validate the finding. Do not send live
credentials, customer data, third-party personal information, or data obtained
without authorization.

If the repository has GitHub private vulnerability reporting enabled, its
**Security** tab may be used instead.

## Research and disclosure boundaries

Test only systems and data you own or are authorized to assess. Do not degrade
availability, retain private data, move laterally, or continue testing after
confirming the issue. This policy does not create a bug-bounty program or grant
permission to test Edilec-hosted services beyond an existing authorization.

Edilec will assess reproducibility, affected versions, impact, remediation,
and disclosure with the reporter where practical. Details should remain
private until a fix or mitigation is available and coordinated disclosure is
agreed. No acknowledgement or remediation deadline is promised by this default
policy.

Dependency vulnerabilities should be reported to the responsible upstream
project when the issue is not introduced by Edilec code. If an Edilec project
uses the affected dependency in a way that creates a concrete risk, also
report that impact privately to Edilec.
