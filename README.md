# Benjamin Rhodes

**Cybersecurity analyst building defensive security automation for AI, AppSec, compliance, and incident response.**

Former Army combat medic and current cybersecurity practitioner focused on practical tools that make risk visible: scanners, linters, audit normalizers, detection helpers, and security dashboards that a team can actually run.

<a href="https://www.linkedin.com/in/benjamin-k-rhodes/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://tryhackme.com/r/p/slimeyskeleton"><img src="https://img.shields.io/badge/-TryHackMe-212C42?&style=for-the-badge&logo=tryhackme&logoColor=white" /></a>

---

## What I Build

- **AI security controls** — prompt-injection checks, PII redaction, model integrity checks, agent audit tooling, and guardrails for AI-enabled workflows.
- **Secure SDLC / DevSecOps tooling** — secret detection, SBOM verification, IaC linting, CI security checks, and least-privilege analyzers.
- **Compliance-aware automation** — small tools that map technical findings to PCI DSS, NIST CSF, access control, logging, and data protection outcomes.
- **Detection and response support** — normalized audit logs, dashboards, and playbook-friendly outputs for triage and investigation.

My goal with this portfolio is simple: show that I can reduce risk in a large organization by building tools that are documented, testable, and easy for security teams to adopt.

---

## Flagship Security Projects

### AI Security & Agent Risk

- **[prompt-injection-detector](https://github.com/benjaminrhodes/prompt-injection-detector)** — Detects prompt injection, jailbreak, and system-prompt extraction attempts in LLM inputs.
  - **Signal:** AI application security, policy enforcement, LLM threat modeling.
  - **Evidence:** CLI, Python API, tests, CI, documented detection categories.

- **[pii-scanner-redactor](https://github.com/benjaminrhodes/pii-scanner-redactor)** — Detects and redacts SSNs, emails, phone numbers, and US-style addresses in text files.
  - **Signal:** Data protection, privacy engineering, DLP support.
  - **Evidence:** CLI workflow, deterministic redaction, unit tests, safe synthetic examples.

- **[agent-audit-normalizer](https://github.com/benjaminrhodes/agent-audit-normalizer)** — Normalizes AI-agent audit logs into a consistent format for review and downstream analysis.
  - **Signal:** AI governance, auditability, incident response readiness.
  - **Evidence:** JSON/CSV/plain-text parsing, CLI, tests, CI.

### Compliance, Cloud, and Secure SDLC

- **[pci-dss-iac-linter](https://github.com/benjaminrhodes/pci-dss-iac-linter)** — Maps Terraform AWS resources to PCI DSS controls and flags common compliance gaps.
  - **Signal:** Compliance-aware cloud security, IaC review, PCI DSS familiarity.
  - **Evidence:** Terraform parser, PCI control mapping, compliance rules, tests.

- **[cardholder-data-discovery](https://github.com/benjaminrhodes/cardholder-data-discovery)** — Scans files/logs for payment card numbers and masks findings for safe reporting.
  - **Signal:** PCI DSS data discovery, sensitive-data handling.
  - **Evidence:** Luhn validation, masked output, tests, CI.

- **[sbom-signature-verifier](https://github.com/benjaminrhodes/sbom-signature-verifier)** — Verifies SBOM package integrity and signatures for SPDX/CycloneDX workflows.
  - **Signal:** Software supply-chain security, SBOM integrity, build trust.
  - **Evidence:** CLI, checksum/signature verification, tests, CI.

- **[security-dashboard](https://github.com/benjaminrhodes/security-dashboard)** — Multi-domain dashboard concept tying together security tool outputs.
  - **Signal:** Executive reporting, risk visibility, portfolio integration.
  - **Evidence:** Python implementation, tests, CI; roadmap includes richer reporting views.

---

## Public-Company Security Signals

- **NIST CSF:** Identify, Protect, Detect, Respond themes show up across data discovery, secure configuration, audit logging, and incident-response support tools.
- **MITRE ATT&CK / Detection Engineering:** Projects emphasize detection logic, normalized evidence, and analyst-readable output rather than only toy scripts.
- **PCI DSS:** Payment-data discovery and IaC compliance tooling demonstrate how technical controls connect to regulated environments.
- **Secure SDLC:** Repositories use tests, CI, security documentation, and dependency-aware project structure where practical.
- **AI Governance:** AI-security projects focus on prompt injection, privacy redaction, model integrity, permissions, memory, and auditability.

---

## Certifications

<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-CompTIA_CYSA%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Google_Cybersecurity-34A853?&style=for-the-badge&logo=Google&logoColor=white" />
<img src="https://img.shields.io/badge/-Google_IT_Support-007BFF?&style=for-the-badge&logo=Google&logoColor=white" />
<img src="https://img.shields.io/badge/-Lean_Six_Sigma_Yellow_Belt-FDD835?&style=for-the-badge&logo=LeanSixSigma&logoColor=white" />
<img src="https://img.shields.io/badge/-TCM_Sec-FF0000?&style=for-the-badge&logoColor=white" />
</div>

Certifications available upon request.

---

## Full Security Engineering Portfolio

I completed a 30-project security engineering challenge across crypto, payments/PCI DSS, AI security, and AI-agent security. The strongest projects are featured above; the full index is below for breadth.

### Crypto Security

- [mnemonic-analyzer](https://github.com/benjaminrhodes/mnemonic-analyzer) — Mnemonic phrase entropy analyzer.
- [secret-linter](https://github.com/benjaminrhodes/secret-linter) — Detects accidentally committed crypto secrets.
- [tx-anomaly-detector](https://github.com/benjaminrhodes/tx-anomaly-detector) — Blockchain transaction anomaly detection.
- [smart-contract-checker](https://github.com/benjaminrhodes/smart-contract-checker) — Solidity static analyzer.
- [seed-phrase-scanner](https://github.com/benjaminrhodes/seed-phrase-scanner) — Phishing page detector.
- [crypto-price-integrity](https://github.com/benjaminrhodes/crypto-price-integrity) — Oracle integrity verifier.
- [wallet-address-validator](https://github.com/benjaminrhodes/wallet-address-validator) — Wallet format validator.

### Payments / PCI DSS

- [cardholder-data-discovery](https://github.com/benjaminrhodes/cardholder-data-discovery) — PAN scanner for files/logs.
- [pci-dss-iac-linter](https://github.com/benjaminrhodes/pci-dss-iac-linter) — IaC to PCI DSS mapper.
- [log-retention-auditor](https://github.com/benjaminrhodes/log-retention-auditor) — Log retention compliance checker.
- [pan-masking-validator](https://github.com/benjaminrhodes/pan-masking-validator) — Credit-card masking validator.
- [tls-config-auditor](https://github.com/benjaminrhodes/tls-config-auditor) — TLS hardening checker.
- [vendor-risk-checklist](https://github.com/benjaminrhodes/vendor-risk-checklist) — Vendor assessment generator.
- [access-control-checker](https://github.com/benjaminrhodes/access-control-checker) — IAM policy least-privilege analyzer.

### AI Security

- [prompt-injection-detector](https://github.com/benjaminrhodes/prompt-injection-detector) — LLM injection pattern detector.
- [pii-scanner-redactor](https://github.com/benjaminrhodes/pii-scanner-redactor) — PII detection/redaction.
- [model-integrity-checker](https://github.com/benjaminrhodes/model-integrity-checker) — ML model checksum verification.
- [inference-policy-gate](https://github.com/benjaminrhodes/inference-policy-gate) — Rate limiting for LLMs.
- [adversarial-sanitizer](https://github.com/benjaminrhodes/adversarial-sanitizer) — ML input sanitizer.
- [model-card-summarizer](https://github.com/benjaminrhodes/model-card-summarizer) — Risk summary from model cards.

### AI Agent Security

- [capability-manifest-linter](https://github.com/benjaminrhodes/capability-manifest-linter) — Agent capability validator.
- [tool-sandbox-policy](https://github.com/benjaminrhodes/tool-sandbox-policy) — File/network access policies.
- [secrets-boundary-test](https://github.com/benjaminrhodes/secrets-boundary-test) — Secret leakage tests.
- [agent-audit-normalizer](https://github.com/benjaminrhodes/agent-audit-normalizer) — Agent log normalizer.
- [sbom-signature-verifier](https://github.com/benjaminrhodes/sbom-signature-verifier) — SBOM integrity verification.
- [agent-memory-redaction](https://github.com/benjaminrhodes/agent-memory-redaction) — PII redaction for agent memory.
- [agent-permission-analyzer](https://github.com/benjaminrhodes/agent-permission-analyzer) — Permission scope analyzer.
- [tool-rate-limiter](https://github.com/benjaminrhodes/tool-rate-limiter) — Agent tool rate limiter.

---

## Earlier Lab Work

- [Vulnerability-Management](https://github.com/benjaminrhodes/Vulnerability-Management)
- [threat-hunting-scenario-tor](https://github.com/benjaminrhodes/threat-hunting-scenario-tor)
- [programmatic-vulnerability-remediations](https://github.com/benjaminrhodes/programmatic-vulnerability-remediations)
- [windows-virtual-machine-set-up](https://github.com/benjaminrhodes/windows-virtual-machine-set-up)
- [ubuntu-vm-setup](https://github.com/benjaminrhodes/ubuntu-vm-setup)

---

## How I Think About Security Work

I like tools that produce clear evidence: a finding, a mapped control, a test result, a normalized event, or a decision a security team can act on. Good security work should survive scrutiny from both sides: understandable to leadership and defensible to engineers.
