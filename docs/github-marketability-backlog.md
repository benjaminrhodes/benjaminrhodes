# GitHub Marketability Backlog

Goal: make `github.com/benjaminrhodes` read like a credible public-company cybersecurity portfolio: clear narrative, fewer flagship projects, verifiable engineering discipline, and mapping to enterprise risk concerns.

## Current Audit Summary

- Profile repo only had `README.md`, so the profile is the primary conversion surface.
- Public repo count inspected via GitHub API: 41 public repositories.
- Most 30-day security portfolio repos already include strong baseline hygiene: `README.md`, `LICENSE`, `SECURITY.md`, `CONTRIBUTING.md`, `pyproject.toml`, tests, and a simple CI workflow.
- Main gap is not repo quantity. The gap is recruiter/hiring-manager signal: many READMEs are short, some use placeholder feature text, many GitHub descriptions are empty, and security/compliance mapping is inconsistent.
- `fw-dao-hackathon-scam-shield` has real marketable potential but still has the default Next.js README and no CI/security docs. It should be polished before being featured heavily.

## Recommended Flagship Order

1. `prompt-injection-detector` — best AI security headline; maps to AppSec, AI governance, and LLM threat modeling.
2. `pii-scanner-redactor` — clear public-company data protection signal; maps to privacy/DLP/NIST Protect.
3. `pci-dss-iac-linter` — strongest compliance/cloud/IaC story; maps directly to regulated enterprise environments.
4. `sbom-signature-verifier` — supply-chain security signal; maps to secure SDLC and third-party risk.
5. `agent-audit-normalizer` — AI governance/auditability; useful if applying to AI security or GRC-adjacent roles.
6. `cardholder-data-discovery` — PCI DSS data discovery; pairs with `pci-dss-iac-linter`.
7. `security-dashboard` — portfolio integration, but README needs more substance before it becomes a top project.

## Repo Descriptions to Set in GitHub

Use `gh repo edit benjaminrhodes/<repo> --description "..." --add-topic "..."` after authentication.

- `prompt-injection-detector`: Detect LLM prompt injection, jailbreak, and system-prompt extraction attempts with a CLI and Python API.
  - Topics: `ai-security`, `llm-security`, `prompt-injection`, `appsec`, `python`, `security-tools`
- `pii-scanner-redactor`: Detect and redact PII in text files for privacy, DLP, and data-protection workflows.
  - Topics: `pii`, `privacy`, `dlp`, `data-protection`, `python`, `security-tools`
- `pci-dss-iac-linter`: Map Terraform AWS resources to PCI DSS controls and flag common compliance gaps.
  - Topics: `pci-dss`, `iac`, `terraform`, `cloud-security`, `compliance`, `python`
- `sbom-signature-verifier`: Verify SBOM integrity and signatures for SPDX and CycloneDX supply-chain workflows.
  - Topics: `sbom`, `supply-chain-security`, `spdx`, `cyclonedx`, `devsecops`, `python`
- `agent-audit-normalizer`: Normalize AI-agent audit logs for governance, triage, and incident-response review.
  - Topics: `ai-security`, `audit-logs`, `agent-security`, `incident-response`, `python`
- `cardholder-data-discovery`: Scan files and logs for payment card data and mask findings for PCI DSS review.
  - Topics: `pci-dss`, `pan`, `data-discovery`, `compliance`, `python`
- `fw-dao-hackathon-scam-shield`: Next.js scam-awareness and wallet-risk education app built for a Fort Worth DAO hackathon.
  - Topics: `web3-security`, `scam-detection`, `nextjs`, `typescript`, `security-awareness`

## Priority Work

### P0 — Profile Conversion

- [x] Rewrite profile README with a public-company cybersecurity narrative.
- [x] Put flagship projects above the full 30-project list.
- [x] Add framework/security-signal mapping for NIST CSF, MITRE ATT&CK, PCI DSS, Secure SDLC, and AI Governance.

### P1 — Top Three Flagship Repos

- [x] Rewrite `prompt-injection-detector` README with risk model, quickstart, sample output, tests, framework mapping, limitations, and roadmap.
- [x] Rewrite `pii-scanner-redactor` README with privacy/DLP positioning, safe sample input/output, and limitations.
- [x] Rewrite `pci-dss-iac-linter` README with PCI DSS mapping, Terraform examples, and compliance caveats.
- [x] Add security workflow files for CodeQL and dependency review where useful.

### P2 — Next Repos to Polish

- [ ] `sbom-signature-verifier`: expand README with SPDX/CycloneDX examples, threat model, and supply-chain risk framing.
- [ ] `agent-audit-normalizer`: show normalized input/output examples and a sample incident-response workflow.
- [ ] `cardholder-data-discovery`: improve README sample data, clarify masking behavior, and add PCI DSS caveats.
- [ ] `fw-dao-hackathon-scam-shield`: replace default Next.js README, add screenshots, add CI, add SECURITY.md/LICENSE.

### P3 — Repo Hygiene Across Portfolio

- [ ] Set missing GitHub descriptions and topics.
- [ ] Add screenshots or terminal recordings for visual projects.
- [ ] Archive or de-emphasize repos with thin/no README if they distract from the flagship narrative.
- [ ] Add consistent badges only where they communicate useful status: CI, Python version, license, security scan.

## Hiring-Manager Narrative

Benjamin builds small, testable security tools that connect technical findings to business risk: AI guardrails, PII redaction, PCI-aware IaC checks, SBOM verification, audit normalization, and security dashboards. The portfolio is strongest when it presents those tools as evidence of secure SDLC, compliance awareness, detection thinking, and clear documentation.
