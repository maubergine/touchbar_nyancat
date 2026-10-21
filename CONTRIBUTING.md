# Contributing

Nyan Cat animation for the MacBook Pro Touch Bar (a fork of the original touchbar_nyancat app).

Bug reports and feature requests are welcome as [issues](https://github.com/maubergine/touchbar_nyancat/issues). Pull requests are
welcome too; CI on a pull request from a fork may wait for the maintainer to approve it.

## Commits

Use [Conventional Commits](https://www.conventionalcommits.org/): `fix:`, `feat:`, `chore:`, `docs:` and so on. This
fork doesn't cut releases, so the type only describes the change. CI checks every commit (`commitlint.yml`). To check them locally before you push:

```sh
npm install   # installs commitlint and turns on .githooks/commit-msg
```

Commits to `master` must be signed.

## Tests

CI builds the app on macOS with `xcodebuild` (see `.github/workflows/ci.yml` for the exact flags).
