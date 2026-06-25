# Contributing

Contributions are welcome. All changes go through pull requests (no direct pushes to `main`).

## Workflow

1. Fork or create a branch
2. Make your changes
3. Run `cargo build --release` to verify
4. Run the binary on a sample WeChat silk file to confirm behavior
5. Open a PR

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — new feature
- `fix:` — bug fix
- `docs:` — docs only
- `refactor:` — code change with no behavior change
- `test:` — test additions/changes
- `chore:` — tooling, CI, etc.

## Code style

- `cargo fmt` before committing
- `cargo clippy -- -D warnings` for new code
- No external network calls (see SECURITY.md)

## Reporting issues

Open a GitHub issue with:
- silk version (`silk --version`)
- OS + arch
- Reproduction command
- Sample silk file (if you can share)

For security issues, see [SECURITY.md](SECURITY.md).
