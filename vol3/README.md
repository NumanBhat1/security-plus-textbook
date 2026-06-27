# Volume 3 — Domain 3.0: Security Architecture

Domain 3.0 is **18%** of the CompTIA Security+ (SY0-701) exam. This volume covers how systems are designed and arranged for security: architecture models (cloud, on-prem, containers, IoT/ICS), securing infrastructure (firewalls, IDS/IPS, zones, VPNs), protecting data (classification, states, encryption/tokenization), and building for resilience and recovery (HA, sites, backups, power).

Each chapter follows the same 30-part template (concept overview, deep technical explanation, attacker/defender perspectives, exam tips, practice questions, and a PBQ-style scenario), built strictly from the official CompTIA SY0-701 exam objectives.

## Chapters (all complete ✅)

| Objective | Title | File |
|-----------|-------|------|
| 3.1 | Compare and contrast security implications of different architecture models | [3.1-architecture-models.md](3.1-architecture-models.md) |
| 3.2 | Apply security principles to secure enterprise infrastructure | [3.2-secure-infrastructure.md](3.2-secure-infrastructure.md) |
| 3.3 | Compare and contrast concepts and strategies to protect data | [3.3-data-protection.md](3.3-data-protection.md) |
| 3.4 | Explain the importance of resilience and recovery | [3.4-resilience-recovery.md](3.4-resilience-recovery.md) |

## High-yield distinctions to memorize

- **Cloud shared responsibility:** customer always secures data + IAM · IaaS = customer secures most, SaaS = least
- **Containers vs. VMs:** containers share the host kernel (lighter, weaker isolation) · VMs = full OS (stronger isolation)
- **IDS vs. IPS:** detect+alert (passive/tap) vs. detect+block (active/inline)
- **Fail-open vs. fail-closed:** allow on failure (availability) vs. block on failure (security)
- **Encryption vs. hashing:** reversible (key) vs. one-way · **masking vs. tokenization:** hide for display vs. replace with vaulted token
- **Data states:** at rest (encrypt disk) · in transit (TLS/IPSec) · in use (hardest)
- **Recovery sites:** hot (fast/expensive) · warm (middle) · cold (slow/cheap) — choose by RTO
- **UPS vs. generator:** short battery outages vs. long outages · **load balancing vs. clustering:** spread traffic vs. servers act as one

---

*Independent study material based on the public CompTIA Security+ SY0-701 exam objectives. Not affiliated with or endorsed by CompTIA.*
