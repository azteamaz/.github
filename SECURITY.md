# Security Policy

AzTeam takes the security of its software, services and users seriously. We appreciate responsible disclosure and will work with you to understand and resolve issues quickly.

## Supported Versions

Security fixes are provided for the latest released version and the current default branch of each repository. Older versions may not receive patches. If a repository defines its own support policy in its own `SECURITY.md`, that policy takes precedence.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public issues, pull requests or discussions.**

Use one of the following private channels:

1. **GitHub Private Vulnerability Reporting** (preferred) — open the affected repository, go to the **Security** tab and choose **Report a vulnerability**.
2. **Contact page** — send your report through [azteam.az/elaqe](https://azteam.az/elaqe) and mark it as a *Security report*. Please do not include full exploit details until we confirm a private channel.

### What to Include

A good report helps us act faster. Please provide, as far as you can:

- The affected repository, component and version or commit.
- A clear description of the vulnerability and its potential impact.
- Step-by-step instructions to reproduce it, or a proof of concept.
- Any suggested mitigation or fix.
- Your preferred name or handle for credit (optional).

## What to Expect

| Stage | Target timeframe |
|---|---|
| Acknowledgement of your report | within 3 business days |
| Initial assessment and severity rating | within 7 business days |
| Status updates | at least every 14 days until resolved |
| Fix and coordinated disclosure | depends on severity and complexity |

These are targets, not guarantees, but we will always keep you informed of progress.

## Disclosure Policy

- We follow **coordinated disclosure**: please give us reasonable time to fix the issue before sharing details publicly.
- Once a fix is available, we may publish a security advisory and credit the reporter, unless you prefer to stay anonymous.

## Scope

In scope:

- Code in repositories of the AzTeam GitHub organization.
- Official AzTeam websites and services operated by AzTeam, such as [azteam.az](https://azteam.az).

Out of scope:

- Vulnerabilities in third-party software or services (report these to the respective vendor).
- Social engineering, phishing or physical attacks against AzTeam staff or infrastructure.
- Denial-of-service, spam or automated high-volume testing.
- Reports based only on missing best-practice headers without a demonstrable impact.

## Safe Harbor

If you act in good faith and follow this policy, we will not pursue legal action against you for your research. Please:

- Avoid accessing, modifying or deleting data that is not yours.
- Stop testing and report immediately if you encounter personal or sensitive data.
- Do not degrade the availability of our services.

## Protecting Your Own Deployments

If you use AzTeam code in your own projects: keep dependencies up to date, never commit secrets, and rotate any credential that may have been exposed.

Thank you for helping keep AzTeam and its users safe.
