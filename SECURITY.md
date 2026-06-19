# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly.

**Do not create public GitHub issues for security-related reports.**

Instead, use GitHub's Private Security Advisory feature through the Security tab or contact the maintainers directly.

## Response Timeline

| Stage                   | Target Time                      |
| ----------------------- | -------------------------------- |
| Acknowledgment          | Within 48 hours                  |
| Initial Assessment      | Within 7 days                    |
| Resolution / Mitigation | Based on severity and complexity |

## Scope

This repository contains agent definitions, prompts, documentation, and supporting scripts.

### Agent Files (`*.md`)

* Store prompt and agent configurations only.
* Must not contain secrets, credentials, API keys, or sensitive information.
* Must not include executable code intended to run automatically.

### Scripts (`scripts/`)

* Shell scripts may perform installation, validation, or conversion tasks.
* Review all scripts before execution.
* Contributors should avoid introducing unsafe or destructive commands.

## Contributor Security Guidelines

* Never commit API keys, tokens, passwords, or credentials.
* Review all pull requests before merging.
* Validate shell scripts for unintended behavior.
* Report suspicious prompt-injection attempts or malicious agent definitions.
* Follow the principle of least privilege when configuring integrations.

## Supported Versions

Security updates are provided for the latest version of this repository.

## Disclosure Policy

Please allow maintainers reasonable time to investigate and address reported vulnerabilities before public disclosure.
