# Security Policy

## Scope

This repository is the public issue tracker for GWW-RGSS projects. Application source code is maintained in separate repositories.

Use this policy to report suspected vulnerabilities affecting GWW-RGSS applications or services, including unauthorized access, permission bypasses, exposed credentials, and disclosure of private student or staff information. Ordinary bugs and feature requests belong in the public issue tracker.

## Supported versions

This issue tracker does not publish application releases. Reports should identify the affected application, deployment, and version or commit, if known.

Please report suspected vulnerabilities even if you are unsure which version is affected. Maintainers will assess the report and determine which maintained versions need a fix; fixes for older versions are not guaranteed.

## Reporting a vulnerability

**Do not post vulnerability details, exploit instructions, credentials, or personal information in a public issue, pull request, or discussion.**

1. Open the [Security tab](https://github.com/GWW-RGSS/issues/security).
2. If **Report a vulnerability** is available, use it to submit a private report to the repository maintainers.
3. If private reporting is unavailable, use an established private contact for a project maintainer. If you do not have one, open an issue titled **Request for private security contact** and ask only how to contact the maintainers privately. Do not include the affected endpoint, technical details, screenshots, or sensitive information in that issue.

### What to include in a private report

- The affected application or service, URL or endpoint, and version or commit if known.
- A clear description of the issue and its potential impact.
- Minimal steps to reproduce it, including any account role or permissions required.
- A small proof of concept or redacted screenshots and logs, if useful.
- Whether the issue appears to expose data or is being actively exploited.

Use test accounts and synthetic data wherever possible. Never include passwords, active access tokens, classroom codes, or unnecessary personal information. Describe an exposed secret and its location without copying its value into the report.

## Responsible testing

- Test only systems and accounts you own or have explicit permission to test.
- Use the minimum interaction needed to demonstrate the issue.
- Do not access, download, modify, or delete another person's data.
- Do not disrupt services, perform denial-of-service testing, attempt social engineering, or use stolen credentials.
- If you unexpectedly encounter private information, stop testing and report the exposure privately. Do not collect additional records.

This policy is a reporting process and does not grant permission to test school, school-board, or third-party systems.

## Handling and disclosure

Maintainers will review reports, request additional information when needed, and coordinate remediation and disclosure through the private reporting channel. Priority depends on impact, exploitability, and available resources; response and resolution times are not guaranteed.

Please coordinate public disclosure with maintainers so affected users can be protected before reproduction details are published. Any public advisory should exclude personal information and secrets. Let maintainers know whether you would like acknowledgment or prefer to remain anonymous.
