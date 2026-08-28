# Contributing to Re:Earth

Thanks for taking the time to contribute. Bug reports, documentation, examples and code are all welcome.

This is the organization-wide default. If the repository you are working in has its own `CONTRIBUTING.md`, that one wins — read it first.

## Before you start

- **Questions** belong on [Discord](https://discord.com/invite/XJhYkQQDAu), not in issues. See [SUPPORT.md](./SUPPORT.md).
- **Security vulnerabilities** must not be reported publicly. See [SECURITY.md](./SECURITY.md).
- All participation is covered by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Reporting bugs

Open an issue in the repository where the bug lives, and include:

- the version or commit you are on, and how you run it,
- what you expected and what actually happened,
- the smallest set of steps that reproduces it.

## Proposing changes

For anything beyond a small fix, **open an issue first** and let us agree on the approach. It is much less painful than finding out at review time that the design should have been different.

## Pull requests

1. Fork the repository and create a branch from `main`.
2. Make your change, and add tests when the repository has a test suite.
3. Run the repository's lint, test and build commands before pushing.
4. Fill in the pull request template — reviewers rely on it.

### Commit messages and PR titles

We follow [Conventional Commits](https://www.conventionalcommits.org/). Pull requests are squash-merged, so **the PR title becomes the commit message** and feeds the changelog:

```
feat(visualizer): add layer style presets
fix(cms): handle empty asset uploads
chore(deps): bump cesium to 1.120
```

Common types: `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `chore`, `ci`.

### Review

- Keep pull requests focused — one concern per PR is far easier to review than five.
- Mark it as a draft while it is still in progress.
- Expect at least one maintainer review before merge.

## Licensing

By contributing, you agree that your contribution is licensed under the same license as the repository you are contributing to. Do not submit code you do not have the right to contribute, and do not paste in code with an unknown or incompatible license.
