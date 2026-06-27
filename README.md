# CompTIA Security+ (SY0-701) — A Deep-Dive Study Textbook

In-depth, objective-by-objective study notes I'm writing as I prepare for the
CompTIA Security+ (SY0-701) exam and a SOC / blue team career. Each official exam
objective is taught from first principles — not just *what* a concept is, but
*why* it exists, *how* it works, how attackers abuse it, and how defenders detect
and mitigate it.

> These are my own study notes, structured against the official **CompTIA Security+
> SY0-701 Exam Objectives, Version 5.0**. Every objective number and statement is
> taken from that document. Work in progress — I add objectives as I study them.

## Why this exists

Watching a course once is passive. Writing the material in my own structured words
— with comparison tables, diagrams, attacker/defender views, and practice
questions — is how I move concepts from "saw it once" to "can explain and apply
it." Keeping it public keeps it organized and might help others studying the same
exam.

## How each chapter is structured

Every objective follows the same consistent template: official statement →
concept overview → deep technical explanation → why it exists / how it works →
advantages & disadvantages → real-world & enterprise usage → attacker &
defender perspectives → detection & mitigation → best practices → comparison
tables → ASCII diagrams → exam tips → common question styles → interview notes →
common mistakes → memory tricks → key facts → quick revision sheet → practice
questions → PBQ-style scenarios.

## Repository layout

```
security-plus-textbook/
├── README.md                  ← this file (master index)
├── 00-TABLE-OF-CONTENTS.md    ← all 5 domains, official objective numbering
├── vol1/  Domain 1 — General Security Concepts            (1.1–1.4)
├── vol2/  Domain 2 — Threats, Vulnerabilities & Mitigations (2.1–2.5)
├── vol3/  Domain 3 — Security Architecture                (3.1–3.4)
├── vol4/  Domain 4 — Security Operations                  (4.1–4.9)
└── vol5/  Domain 5 — Security Program Management & Oversight (5.1–5.6)
```

Each objective is a single markdown file named `N.N-short-title.md` inside its
volume folder. New objectives drop straight into the right `volN/` folder — no
restructuring needed.

## Progress

| Domain | Volume | Status |
|--------|--------|--------|
| 1.0 General Security Concepts | vol1 | ✅ Complete (1.1–1.4) |
| 2.0 Threats, Vulnerabilities & Mitigations | vol2 | ✅ Complete (2.1–2.5) |
| 3.0 Security Architecture | vol3 | ✅ Complete (3.1–3.4) |
| 4.0 Security Operations | vol4 | ✅ Complete (4.1–4.9) |
| 5.0 Security Program Management & Oversight | vol5 | ✅ Complete (5.1–5.6) |

See the [full Table of Contents](00-TABLE-OF-CONTENTS.md) for every objective.

## Chapters

### Volume 1 — Domain 1.0: General Security Concepts ✅

| Objective | Title |
|-----------|-------|
| [1.1](vol1/1.1-security-controls.md) | Compare and contrast various types of security controls |
| [1.2](vol1/1.2-fundamental-concepts.md) | Summarize fundamental security concepts |
| [1.3](vol1/1.3-change-management.md) | Explain the importance of change management processes and the impact to security |
| [1.4](vol1/1.4-cryptographic-solutions.md) | Explain the importance of using appropriate cryptographic solutions |

### Volume 2 — Domain 2.0: Threats, Vulnerabilities, and Mitigations ✅

| Objective | Title |
|-----------|-------|
| [2.1](vol2/2.1-threat-actors.md) | Compare and contrast common threat actors and motivations |
| [2.2](vol2/2.2-threat-vectors.md) | Explain common threat vectors and attack surfaces |
| [2.3](vol2/2.3-vulnerabilities.md) | Explain various types of vulnerabilities |
| [2.4](vol2/2.4-malicious-activity.md) | Given a scenario, analyze indicators of malicious activity |
| [2.5](vol2/2.5-mitigation-techniques.md) | Explain the purpose of mitigation techniques used to secure the enterprise |

### Volume 3 — Domain 3.0: Security Architecture ✅

| Objective | Title |
|-----------|-------|
| [3.1](vol3/3.1-architecture-models.md) | Compare and contrast security implications of different architecture models |
| [3.2](vol3/3.2-secure-infrastructure.md) | Given a scenario, apply security principles to secure enterprise infrastructure |
| [3.3](vol3/3.3-data-protection.md) | Compare and contrast concepts and strategies to protect data |
| [3.4](vol3/3.4-resilience-recovery.md) | Explain the importance of resilience and recovery in security architecture |

### Volume 4 — Domain 4.0: Security Operations ✅

| Objective | Title |
|-----------|-------|
| [4.1](vol4/4.1-secure-computing.md) | Given a scenario, apply common security techniques to computing resources |
| [4.2](vol4/4.2-asset-management.md) | Explain the security implications of proper hardware, software, and data asset management |
| [4.3](vol4/4.3-vulnerability-management.md) | Explain various activities associated with vulnerability management |
| [4.4](vol4/4.4-monitoring.md) | Explain security alerting and monitoring concepts and tools |
| [4.5](vol4/4.5-enterprise-capabilities.md) | Given a scenario, modify enterprise capabilities to enhance security |
| [4.6](vol4/4.6-iam.md) | Given a scenario, implement and maintain identity and access management |
| [4.7](vol4/4.7-automation-orchestration.md) | Explain the importance of automation and orchestration related to secure operations |
| [4.8](vol4/4.8-incident-response.md) | Explain appropriate incident response activities |
| [4.9](vol4/4.9-investigation-data.md) | Given a scenario, use data sources to support an investigation |

### Volume 5 — Domain 5.0: Security Program Management and Oversight ✅

| Objective | Title |
|-----------|-------|
| [5.1](vol5/5.1-security-governance.md) | Summarize elements of effective security governance |
| [5.2](vol5/5.2-risk-management.md) | Explain elements of the risk management process |
| [5.3](vol5/5.3-third-party-risk.md) | Explain the processes associated with third-party risk assessment and management |
| [5.4](vol5/5.4-security-compliance.md) | Summarize elements of effective security compliance |
| [5.5](vol5/5.5-audits-assessments.md) | Explain types and purposes of audits and assessments |
| [5.6](vol5/5.6-security-awareness.md) | Given a scenario, implement security awareness practices |

## About me

Aspiring SOC Analyst transitioning into cybersecurity (B.Tech, NIT Srinagar).
Currently studying for CompTIA Security+ and building hands-on labs and tools.
Other repos: [python-security-tools](https://github.com/NumanBhat1/python-security-tools),
[linux-security-scripts](https://github.com/NumanBhat1/linux-security-scripts),
[hackthebox-writeups](https://github.com/NumanBhat1/hackthebox-writeups),
[cybersecurity-notes](https://github.com/NumanBhat1/cybersecurity-notes).

---

*Source of truth: CompTIA Security+ SY0-701 Certification Exam Objectives, Version 5.0
(© 2023 CompTIA, Inc.). This is independent study material and is not affiliated
with or endorsed by CompTIA. "CompTIA" and "Security+" are trademarks of CompTIA, Inc.*
