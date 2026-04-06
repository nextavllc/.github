# Security Policy

NextAV takes the security of our geospatial platform, AI models, and client data seriously. We are committed to maintaining the highest standards of security and confidentiality.

## Supported Versions

Security updates and patches are provided for active deployments and current production systems.

| Version / Deployment | Supported |
| :--- | :--- |
| Active client deployments | Yes |
| Current production (main branch) | Yes |
| Staging environments | Yes |
| Legacy / deprecated branches | No |

## Reporting a Vulnerability

If you believe you have discovered a security vulnerability in any NextAV software, infrastructure, or AI model, please report it to us immediately.

**Do not open a public issue or publicly disclose the vulnerability.**

1. **Email your report** to [contact@nextav.ai](mailto:contact@nextav.ai) with "SECURITY" in the subject line.
2. **Include detailed information**, such as:
   - A description of the vulnerability
   - Steps to reproduce the issue
   - The specific system, repository, or component affected
   - Potential impact or risk assessment

## Response Process

- We will acknowledge receipt of your vulnerability report within **48 hours**.
- Our engineering team will triage and investigate the issue.
- We will provide updates on our progress and notify you when a patch or mitigation has been deployed.

## Responsible Disclosure

We ask that you act in good faith to protect the privacy and data of NextAV and our clients. Please do not exploit the vulnerability beyond what is absolutely necessary to verify its existence, and do not share details of the vulnerability with any third parties without our explicit written permission.

## Security Practices

- All repositories require two-factor authentication (2FA) for org members
- Dependabot alerts and secret scanning are enabled across all repositories
- Code reviews are required before merging to protected branches
- Secrets are managed via AWS Secrets Manager and GitHub Secrets (never committed to code)
- Container images are scanned for vulnerabilities before deployment
