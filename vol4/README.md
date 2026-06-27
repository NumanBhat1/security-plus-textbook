# Volume 4 — Domain 4.0: Security Operations

Domain 4.0 is **28%** of the CompTIA Security+ (SY0-701) exam — the **largest domain** and the most directly relevant to a SOC analyst role. This volume covers securing computing resources, asset and vulnerability management, monitoring/alerting, enterprise security capabilities, identity and access management, automation, incident response, and using data sources for investigations.

Each chapter follows the same 30-part template (concept overview, deep technical explanation, attacker/defender perspectives, exam tips, practice questions, and a PBQ-style scenario), built strictly from the official CompTIA SY0-701 exam objectives.

## Chapters (all complete ✅)

| Objective | Title | File |
|-----------|-------|------|
| 4.1 | Apply common security techniques to computing resources | [4.1-secure-computing.md](4.1-secure-computing.md) |
| 4.2 | Security implications of hardware, software, and data asset management | [4.2-asset-management.md](4.2-asset-management.md) |
| 4.3 | Activities associated with vulnerability management | [4.3-vulnerability-management.md](4.3-vulnerability-management.md) |
| 4.4 | Security alerting and monitoring concepts and tools | [4.4-monitoring.md](4.4-monitoring.md) |
| 4.5 | Modify enterprise capabilities to enhance security | [4.5-enterprise-capabilities.md](4.5-enterprise-capabilities.md) |
| 4.6 | Implement and maintain identity and access management | [4.6-iam.md](4.6-iam.md) |
| 4.7 | Automation and orchestration related to secure operations | [4.7-automation-orchestration.md](4.7-automation-orchestration.md) |
| 4.8 | Incident response activities | [4.8-incident-response.md](4.8-incident-response.md) |
| 4.9 | Use data sources to support an investigation | [4.9-investigation-data.md](4.9-investigation-data.md) |

## High-yield distinctions to memorize

- **SIEM vs SOAR:** SIEM detects/correlates logs · SOAR automates the response
- **SIEM vs NetFlow:** log correlation vs traffic metadata · **SNMP trap** = device pushes an alert
- **Email auth:** SPF (authorized senders) · DKIM (signature) · DMARC (policy + reporting)
- **Access models:** MAC (labels) · DAC (owner) · RBAC (role) · ABAC (attributes)
- **SAML vs OAuth:** authentication/SSO vs authorization (delegated) · **MFA** = 2+ different factor *types*
- **CVE vs CVSS:** unique ID vs severity score · **false positive vs false negative**
- **IR order:** Preparation → Detection → Analysis → **Containment → Eradication → Recovery** → Lessons Learned (contain *before* eradicate)
- **Chain of custody** = documented evidence handling · **packet capture** = actual traffic content (vs logs = that it happened)
- **EDR vs XDR vs UEBA** · **sanitization vs destruction** · **PAM:** JIT / vaulting / ephemeral

---

*Independent study material based on the public CompTIA Security+ SY0-701 exam objectives. Not affiliated with or endorsed by CompTIA.*
