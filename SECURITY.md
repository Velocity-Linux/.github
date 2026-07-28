# Security Policy

## Supported Versions

Velocity OS provides security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| Current | Yes                |
| Previous | Yes               |
| Older   | No                 |

The "Current" version is the latest stable release. The "Previous" version is the immediate predecessor. Security fixes for unsupported versions are not backported.

## Reporting Vulnerabilities

**Do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Velocity OS takes security seriously. If you discover a vulnerability, please report it privately so we can address it before public disclosure.

### Private Disclosure Process

1. Email your report to **velocityos@tutamail.com** with the subject line `Velocity OS Security Report`.
2. Include a detailed description of the vulnerability, affected versions, and steps to reproduce.
3. If known, include suggested fixes or mitigations.
4. Encrypt sensitive reports using our [PGP public key](https://keys.openpgp.org/search?q=velocityos@tutamail.com).

### What to Expect

- We will acknowledge receipt of your report within 3 business days.
- We will provide a more detailed response within 10 business days, indicating our plans to address the issue.
- We will keep you informed of progress toward a fix and announcement.
- We will credit you in the security advisory unless you request anonymity.

## Security Response Timeline

- **Day 0-3**: Acknowledgment of report.
- **Day 3-10**: Initial triage and confirmation.
- **Day 10-30**: Development of fix and coordinated disclosure timeline.
- **Day 30+**: Patch release and public advisory.

Timelines may vary based on severity and complexity. Critical vulnerabilities are prioritized.

## Package Signing Policy

All Velocity OS packages are signed with our official GPG key. Users should verify package signatures before installation.

The current signing key fingerprint is published in the release artifacts and on docs.velocityos.org.

## Responsible Disclosure

We ask that you:

- Do not exploit the vulnerability beyond what is necessary to demonstrate it.
- Do not share the vulnerability details with others until we have issued a fix.
- Give us reasonable time to investigate and develop a fix before any public disclosure.

We are committed to working with researchers to acknowledge contributions and ensure responsible disclosure.

## Contact

- **Security email**: velocityos@tutamail.com
- **PGP key**: https://keys.openpgp.org/search?q=velocityos@tutamail.com
