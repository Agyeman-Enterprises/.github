# Security Policy — Agyeman Enterprises

## Reporting a Vulnerability

If you discover a security vulnerability in any Agyeman Enterprises product, please report it responsibly:

**Email:** admin@agyemanenterprises.com
**Response time:** 48 hours for acknowledgment, 14 days for assessment

Please do **not** open public GitHub issues for security vulnerabilities.

## Supported Versions

We maintain security patches for all actively deployed products. End-of-life versions are not patched.

## Security Scanning

All repositories in this organization are automatically scanned on every commit:
- **CVE scanning**: pip-audit (Python), npm audit (Node.js)
- **Secret detection**: Gitleaks
- **SAST**: Semgrep (OWASP Top 10, language-specific rules)
- **Dependency review**: GitHub Dependency Review Action (blocks PRs with HIGH+ vulns)
- **Dependabot**: Weekly automated dependency updates

Auto-fix PRs are opened immediately when patches are available.
