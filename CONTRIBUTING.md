# Contributing to offsteel

Thank you for your interest in offsteel. This guide applies to every repository of the organization, unless a repository has its own `CONTRIBUTING.md`.

## Before you start

- Search the open issues first. If nothing matches, open a new issue with one of the templates before you write code, so we can agree on the approach.
- Security issues never go to public issues. Follow [SECURITY.md](SECURITY.md).
- By taking part you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Branches

Create a branch from the default branch, named after the type and the issue:

```
<type>/<issue-number>-<short-slug>
```

Examples: `feat/123-node-heartbeat`, `fix/88-retry-dns`, `chore/12-bump-go`.

Allowed types: `feat`, `fix`, `chore`, `docs`, `refactor`, `test`, `perf`, `ci`, `build`.

## Commits and pull request titles

We use [Conventional Commits](https://www.conventionalcommits.org/) in English:

```
type(scope): short summary
```

Mark breaking changes with `!` after the type or with a `BREAKING CHANGE:` footer.

Pull requests are merged with squash, and the pull request title becomes the commit title. Write the title carefully: it drives the changelog.

## Sign off

Every commit must carry a Developer Certificate of Origin sign off:

```
git commit -s
```

This adds a `Signed-off-by: Your Name <you@example.com>` line, which certifies that you wrote the change or have the right to submit it under the license of the repository ([developercertificate.org](https://developercertificate.org/)).

## Pull requests

- Link the issue in the description (`Closes #123`).
- Keep each pull request focused on one change.
- Add or update tests for the behavior you change.
- Update the documentation when behavior or usage changes.
- Every pull request needs passing checks and an approving review from a code owner before it can be merged.

## License

Contributions are accepted under the license of the repository they target, as stated in its `LICENSE` file.
