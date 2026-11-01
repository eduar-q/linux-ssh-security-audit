# Linux SSH Security Audit

A Python-based project focused on reviewing SSH server security configurations on Linux systems.

The goal is to build a simple and reliable tool that helps identify insecure SSH settings, understand their potential impact, and provide practical recommendations for improvement.

## Project Status

**Early development.**

The project structure and development environment are ready. The auditing functionality has not been implemented yet.

## Objectives

The project aims to:

- Review OpenSSH server configuration.
- Identify potentially insecure SSH settings.
- Check relevant file permissions and ownership.
- Evaluate authentication and access control settings.
- Provide clear findings with evidence and remediation guidance.
- Generate reports in readable formats.

## Scope

The initial focus is Linux systems running OpenSSH.

The audit will consider effective SSH configuration, including configuration files, included files, and selected connection-specific rules where applicable.

The tool is intended to operate in read-only mode. It will not modify SSH configuration files, users, permissions, keys, or running services.

## Project Principles

- Keep the code simple and maintainable.
- Prefer clear findings over excessive security warnings.
- Avoid reporting issues without sufficient evidence.
- Document recommendations and their technical justification.
- Test behavior before adding new functionality.

## Planned Technologies

- Python 3
- OpenSSH
- pytest
- Git and GitHub

## Disclaimer

This project is intended for defensive security auditing on systems that you own or are authorized to assess.

It is not a penetration testing tool or a complete infrastructure security assessment.

## Development

This project is under active development. Features, documentation, and testing will be added incrementally.
