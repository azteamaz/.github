# Contributing to AzTeam

Thank you for your interest in contributing to AzTeam projects. Every bug report, idea, documentation fix and pull request helps us build better products.

This guide applies to all repositories in the [AzTeam GitHub organization](https://github.com/azteamaz) unless a repository provides its own `CONTRIBUTING.md`.

## Code of Conduct

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## Ways to Contribute

- **Report bugs** — use the *Bug report* issue form.
- **Suggest features** — use the *Feature request* issue form.
- **Improve documentation** — fix typos, clarify instructions, add examples.
- **Submit code** — fix bugs or implement agreed features through a pull request.
- **Review** — read open pull requests and share constructive feedback.

> **Security issues:** never report vulnerabilities in public issues. Follow [SECURITY.md](SECURITY.md) instead.

## Before You Start

1. Search existing [issues](../../issues) and pull requests to avoid duplicates.
2. For anything larger than a small fix, open an issue first and describe what you plan to do. This avoids wasted effort if the change does not fit the project direction.
3. Wait for a maintainer to confirm the approach on larger changes.

## Development Workflow

1. **Fork** the repository and clone your fork.
2. **Create a branch** from the default branch using a descriptive name:

   | Prefix | Use for | Example |
   |---|---|---|
   | `feature/` | New functionality | `feature/user-balance-page` |
   | `fix/` | Bug fixes | `fix/login-redirect-loop` |
   | `docs/` | Documentation only | `docs/update-install-guide` |
   | `refactor/` | Code changes without behavior change | `refactor/payment-module` |
   | `chore/` | Tooling, dependencies, config | `chore/update-dependencies` |

3. **Make your changes** in small, focused commits.
4. **Test** your changes locally (see project README for instructions).
5. **Push** your branch and open a **pull request** using the provided template.

## Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) style:

```
<type>(optional scope): <short summary>

Optional longer description explaining what and why.
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

Examples:

```
feat(auth): add Google sign-in
fix(invoice): correct VAT rounding
docs(readme): add local setup steps
```

Keep the summary under 72 characters and write it in the imperative mood ("add", not "added").

## Pull Request Guidelines

- Keep pull requests **focused** — one logical change per PR.
- Fill in the pull request template completely.
- Link the related issue (for example `Closes #123`).
- Make sure existing tests pass and add tests for new behavior where practical.
- Update documentation when behavior, configuration or setup changes.
- Include screenshots or recordings for visible UI changes.
- Do not include unrelated formatting changes, generated files or secrets.
- Be responsive to review comments. Maintainers may request changes before merging.

A pull request is ready to merge when it has maintainer approval, passes all automated checks and has no unresolved review threads.

## Coding Standards

- Follow the conventions already used in the repository (style, naming, structure).
- Prefer clear, readable code over clever code.
- Write comments to explain *why*, not *what*.
- Validate and sanitize all user input; use prepared statements for database access.
- Never commit credentials, API keys, tokens, `.env` files or personal data.
- Keep dependencies minimal and only add well-maintained packages.
- Respect accessibility and responsive design for user-facing interfaces.

## Documentation

Documentation is part of the product. If your change affects how something is installed, configured or used, update the relevant README or docs in the same pull request.

## Licensing of Contributions

By submitting a contribution, you confirm that you have the right to submit it and agree that it will be released under the license of the repository you are contributing to.

## Getting Help

Questions about contributing? See [SUPPORT.md](SUPPORT.md) or reach us through [azteam.az/elaqe](https://azteam.az/elaqe).

Thank you for helping make AzTeam better.
