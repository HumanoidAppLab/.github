# Security Policy

The **DataRealm Humanoid Application Lab** (`HumanoidAppLab`) takes the security of our software, robotic control pipelines, and user data seriously. This document outlines our policy for reporting security vulnerabilities across all repositories within the organization.

---

## Supported Versions

Security updates and patches are prioritized for active, supported releases:

| Project / Version | Supported          |
| ----------------- | ------------------ |
| Latest Release    | :white_check_mark: |
| Default (`main`)  | :white_check_mark: |
| Older Versions    | :x: (Best effort)  |

Individual repositories may define repository-specific support matrices in their own `SECURITY.md` which supersede this organization-level default.

---

## Reporting a Vulnerability

> [!CAUTION]
> **Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

If you believe you have found a security vulnerability in any `HumanoidAppLab` repository, please report it through one of the following channels:

### 1. GitHub Private Vulnerability Reporting (Preferred)

If enabled on the specific repository:
1. Navigate to the repository's **Security** tab.
2. Under "Reporting", click **Report a vulnerability**.
3. Fill out the advisory form with detailed reproduction steps and impact details.

### 2. Email Disclosure

If Private Vulnerability Reporting is not available, please send an encrypted or plain email to:
- **Contact**: [info@DataRealmInc.com](mailto:info@DataRealmInc.com)
- **Subject**: `[SECURITY VULNERABILITY] <Repository Name> - <Brief Summary>`

### What to Include in Your Report

To help us triage and resolve the issue quickly, please include:
- A clear description of the vulnerability and its potential impact.
- The specific repository, branch, tag, or commit hash where the vulnerability was discovered.
- Detailed step-by-step instructions or a minimal Proof of Concept (PoC) to reproduce the vulnerability.
- Any known mitigations or workarounds.
- Your preferred method of attribution if a public advisory is published.

---

## Response Process & Timelines

1. **Acknowledgment**: We aim to acknowledge receipt of your vulnerability report within **48 to 72 hours**.
2. **Assessment & Validation**: Maintainers will evaluate the report, verify the impact, and keep you informed of our findings.
3. **Remediation**: Once verified, we will develop and test a fix in a private branch or advisory draft.
4. **Coordinated Disclosure**: We will coordinate with you regarding the release of the patch and advisory publication. We request that you maintain confidentiality until an official fix is released.

---

## Safe Harbor

We consider security research conducted in good faith to be authorized. If you:
- Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our services,
- Do not exploit a security issue beyond what is necessary to demonstrate it, and
- Give us reasonable time to resolve the issue before disclosing it publicly,

we will not pursue legal action against you regarding your research.
