# Contributing to gravion-ux

Thanks for your interest in contributing! gravion-ux — full-stack team task manager (MERN): JWT auth, role-based access, projects, kanban boards with drag-and-drop, tasks, comments.

This document explains how to set up the project locally, run its tests, and
submit changes that can be reviewed and merged quickly.

## Getting started

1. Fork the repository and clone your fork:

   ```bash
   git clone https://github.com/<your-username>/gravion-ux.git
   cd gravion-ux
   ```

2. Set up the project:

This project has separate `server/` and `client/` packages. Install both:

```bash
npm --prefix server install
npm --prefix client install
```

3. Create a branch for your change:

   ```bash
   git checkout -b my-change
   ```

## Running the tests

Run the full test suite before opening a pull request:

```bash
cd server && npm test && cd ../client && npm test
```

All tests must pass. If your change adds behaviour, add or update tests for it.

## Pull request rules

- **One change per PR.** Keep each pull request focused on a single fix,
  feature, or improvement — small PRs get reviewed faster.
- **Tests must pass.** Run the test suite locally and make sure it is green
  before requesting review; CI must pass on the final commit.
- **No secrets.** Never commit API keys, tokens, passwords, private keys, or
  personal data — in code, tests, fixtures, or examples. Use clearly fake
  placeholder values instead.
- **Match the existing style.** Follow the naming, formatting, and structure
  already used in the codebase; don't reformat unrelated code.
- **Describe your change.** In the PR description, say what changed, why, and
  how you tested it.
- **Licence.** By contributing, you agree that your contribution is provided
  under the repository's existing licence.

## Reporting bugs and requesting features

Use the GitHub issue templates (Bug report / Feature request) so reports
include the information needed to reproduce and evaluate them.

## Reporting security vulnerabilities

Please do **not** open a public issue for a security vulnerability. Follow
the private reporting process in [SECURITY.md](SECURITY.md) instead.

## Code of conduct

Participation in this project is governed by the
[Code of Conduct](CODE_OF_CONDUCT.md).
