# AGENTS

## General Workflow
- Before starting work or amending commits, ensure your branch is up to date with `master` to avoid merge conflicts when multiple PRs are in flight:
  - `git fetch origin`
  - `git rebase origin/master` (or `git merge origin/master` if you prefer)
- Format code with `cargo fmt --all`.
- Run `cargo clippy --all-targets --all-features -- -D warnings`.
- Run the test suite with `cargo test`.

## Pull Request Guidelines
- Use descriptive commit messages and PR titles.
- Keep commits focused and small when possible.
