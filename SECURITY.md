# Security Policy

This policy covers the repositories in the Re:Earth organization. If a
repository ships its own `SECURITY.md`, that one takes precedence for the
project it lives in.

## Reporting a vulnerability

Please report security issues privately. Don't open a public issue, pull
request, or discussion, and don't disclose the problem publicly until a fix is
available.

There are two ways to reach us, in order of preference:

1. **GitHub private vulnerability reporting.** On the affected repository, open
   the **Security** tab and choose **Report a vulnerability**. This creates a
   private advisory only the maintainers can see and lets us work on the fix in
   the same place. GitHub's
   [guide](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)
   walks through it if you haven't used it before.
2. **Email.** If private reporting isn't enabled on the repo, or you'd rather
   use email, write to [community@reearth.io](mailto:community@reearth.io).

For problems with the hosted Re:Earth service or your account, rather than the
source code, email [support@reearth.io](mailto:support@reearth.io).

## What to include

A report we can act on quickly usually has:

- the repository and the version, tag, or commit affected,
- the type of issue and the part of the code involved,
- steps to reproduce, or a short proof of concept,
- what an attacker could do with it, and
- a suggested fix, if you have one.

Plain language beats security jargon. The thing we need most is a reliable way
to reproduce the issue.

## A note on AI-assisted reports

AI tools are useful for finding bugs, and you're welcome to use them. You're
still responsible for what you send us. Before reporting, confirm the issue
yourself and include a working proof of concept that reproduces it against the
current code.

We close reports that are clearly machine-generated and can't be reproduced, or
that describe a theoretical problem with no proof of concept, without a detailed
response. Triage time is the one thing a small team can't get back, and
unverified reports spend it for no benefit. If you used AI tooling in your
research, please say so.

## What to expect from us

- We'll acknowledge your report within three business days.
- We'll confirm the issue, keep you updated as we work on a fix, and tell you
  when it ships.
- For confirmed vulnerabilities we open a GitHub Security Advisory, credit you
  unless you'd rather stay anonymous, and request a CVE when one is warranted.
- We work to a coordinated disclosure timeline of up to 90 days, and we're glad
  to adjust it with you when a fix needs longer.

## Scope

This policy is about vulnerabilities in the code in actively maintained Re:Earth
repositories. Some things that are usually out of scope:

- output from automated scanners with no working proof of concept,
- issues in third-party dependencies (report those upstream, and tell us if a
  Re:Earth project needs to update),
- missing hardening or best-practice headers with no demonstrated impact,
- reports that depend on social engineering, physical access, or an already
  compromised device, and
- volumetric denial of service.

If you're not sure whether something counts, report it anyway and we'll look.

## Supported versions

Each product follows its own release and patch cadence. Security fixes land on
the actively maintained release lines, which are noted in each repository's
releases and changelog.

## Safe harbor

We treat security research done in good faith under this policy as authorized.
We won't pursue or support legal action against you for it, as long as you stay
within scope, avoid accessing or changing data that isn't yours, don't degrade
the service for others, and give us a reasonable chance to fix the issue before
going public.
