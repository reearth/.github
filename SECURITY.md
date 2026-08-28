# Security Policy

This policy applies to every repository in the [Re:Earth organization](https://github.com/reearth) that does not publish its own `SECURITY.md`.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, pull requests, or Discord.**

Instead, use GitHub's private vulnerability reporting:

1. Go to the affected repository.
2. Open the **Security** tab → **Report a vulnerability**.

This creates a private advisory visible only to you and the maintainers. If the repository does not have that option enabled, open a report on [reearth/.github](https://github.com/reearth/.github/security/advisories/new) instead and tell us which repository is affected.

## What to include

The more of this you can give us, the faster we can act:

- The affected repository, version or commit, and deployment (self-hosted or a `*.reearth.io` / `*.reearth.land` service).
- The type of issue (e.g. authentication bypass, injection, SSRF, privilege escalation).
- Step-by-step instructions to reproduce it, including any proof-of-concept.
- The impact you believe an attacker could achieve.

## What to expect

- We aim to acknowledge your report within **5 business days**.
- We will keep you updated on our assessment and the fix, and we will let you know when a patch ships.
- We will credit you in the advisory unless you ask us not to.

Please give us a reasonable window to release a fix before disclosing the issue publicly.

## Supported versions

We provide security fixes for the **latest release** of each product. Older releases are not patched — if you run a pinned version, please plan to upgrade.

## Scope

Reports about our own code and hosted services are in scope. The following generally are not:

- Vulnerabilities in third-party dependencies that we do not control — report those upstream first, then tell us so we can bump the dependency.
- Findings that require physical access, a compromised account, or social engineering of our team.
- Missing security headers, or automated scanner output, with no demonstrated impact.
