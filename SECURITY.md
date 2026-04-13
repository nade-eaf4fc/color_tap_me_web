# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest (main branch) | ✅ |
| older commits        | ❌ |

## Scope

This is a **client-side only** web application. All image processing runs entirely in the browser using the Canvas API. No data is transmitted to or stored on any server.

**In scope:**
- Cross-Site Scripting (XSS) vulnerabilities in HTML/JavaScript
- Malicious file handling via the image input
- Third-party dependency vulnerabilities (e.g. Twitter/X embed widget)

**Out of scope:**
- Server-side vulnerabilities (there is no server)
- Issues specific to a user's local browser environment or OS
- Social engineering attacks

## Reporting a Vulnerability

If you discover a security vulnerability, please **do not** open a public issue.

Instead, report it via one of the following:

- **X (Twitter) DM**: [@nade_eaf4fc](https://x.com/nade_eaf4fc)
- **GitHub**: Use [GitHub's private vulnerability reporting](../../security/advisories/new) for this repository

Please include:
1. A description of the vulnerability
2. Steps to reproduce
3. Potential impact

## Response

I will acknowledge receipt within **7 days** and aim to release a fix within **30 days** depending on severity.
