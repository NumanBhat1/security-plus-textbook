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
| 2.0 Threats, Vulnerabilities & Mitigations | vol2 | ⏳ In progress |
| 3.0 Security Architecture | vol3 | ⏳ Planned |
| 4.0 Security Operations | vol4 | ⏳ Planned |
| 5.0 Security Program Management & Oversight | vol5 | ⏳ Planned |

See the [full Table of Contents](00-TABLE-OF-CONTENTS.md) for every objective.

## Chapters

### Volume 1 — Domain 1.0: General Security Concepts ✅

| Objective | Title |
|-----------|-------|
| [1.1](vol1/1.1-security-controls.md) | Compare and contrast various types of security controls |
| [1.2](vol1/1.2-fundamental-concepts.md) | Summarize fundamental security concepts |
| [1.3](vol1/1.3-change-management.md) | Explain the importance of change management processes and the impact to security |
| [1.4](vol1/1.4-cryptographic-solutions.md) | Explain the importance of using appropriate cryptographic solutions |

### Volume 2 — Domain 2.0: Threats, Vulnerabilities, and Mitigations
*(in progress — chapters added here as I write them)*

### Volume 3 — Domain 3.0: Security Architecture
*(planned)*

### Volume 4 — Domain 4.0: Security Operations
*(planned)*

### Volume 5 — Domain 5.0: Security Program Management and Oversight
*(planned)*

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
