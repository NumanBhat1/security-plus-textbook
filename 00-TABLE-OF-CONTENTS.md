# The Definitive CompTIA Security+ (SY0-701) Textbook Series

**Author:** Numan Khalid Bhat
**Co-authored with an AI cybersecurity educator**
**Source of truth:** CompTIA Security+ SY0-701 Certification Exam Objectives, Version 5.0 (© 2023 CompTIA, Inc.)

> Every objective number and official objective statement in this series is reproduced verbatim
> from the official SY0-701 Exam Objectives document. Sub-bullets are taken from the same source
> and become numbered subsections per the project's subsection rule.

---

## MASTER TABLE OF CONTENTS (7 Volumes)

---

# VOLUME 1 — Domain 1.0: General Security Concepts (12%)

### Objective 1.1 — Compare and contrast various types of security controls.
- 1.1.1 Categories: Technical
- 1.1.2 Categories: Managerial
- 1.1.3 Categories: Operational
- 1.1.4 Categories: Physical
- 1.1.5 Control types: Preventive
- 1.1.6 Control types: Deterrent
- 1.1.7 Control types: Detective
- 1.1.8 Control types: Corrective
- 1.1.9 Control types: Compensating
- 1.1.10 Control types: Directive

### Objective 1.2 — Summarize fundamental security concepts.
- 1.2.1 Confidentiality, Integrity, and Availability (CIA)
- 1.2.2 Non-repudiation
- 1.2.3 Authentication, Authorization, and Accounting (AAA)
  - Authenticating people
  - Authenticating systems
  - Authorization models
- 1.2.4 Gap analysis
- 1.2.5 Zero Trust — Control Plane (Adaptive identity, Threat scope reduction, Policy-driven access control, Policy Administrator, Policy Engine)
- 1.2.6 Zero Trust — Data Plane (Implicit trust zones, Subject/System, Policy Enforcement Point)
- 1.2.7 Physical security (Bollards, Access control vestibule, Fencing, Video surveillance, Security guard, Access badge, Lighting, Sensors: Infrared, Pressure, Microwave, Ultrasonic)
- 1.2.8 Deception and disruption technology (Honeypot, Honeynet, Honeyfile, Honeytoken)

### Objective 1.3 — Explain the importance of change management processes and the impact to security.
- 1.3.1 Business processes impacting security operation (Approval process, Ownership, Stakeholders, Impact analysis, Test results, Backout plan, Maintenance window, Standard operating procedure)
- 1.3.2 Technical implications (Allow lists/deny lists, Restricted activities, Downtime, Service restart, Application restart, Legacy applications, Dependencies)
- 1.3.3 Documentation (Updating diagrams, Updating policies/procedures)
- 1.3.4 Version control

### Objective 1.4 — Explain the importance of using appropriate cryptographic solutions.
- 1.4.1 Public key infrastructure (PKI) (Public key, Private key, Key escrow)
- 1.4.2 Encryption — Level (Full-disk, Partition, File, Volume, Database, Record)
- 1.4.3 Encryption — Transport/communication
- 1.4.4 Encryption — Asymmetric
- 1.4.5 Encryption — Symmetric
- 1.4.6 Encryption — Key exchange
- 1.4.7 Encryption — Algorithms
- 1.4.8 Encryption — Key length
- 1.4.9 Tools (Trusted Platform Module (TPM), Hardware security module (HSM), Key management system, Secure enclave)
- 1.4.10 Obfuscation (Steganography, Tokenization, Data masking)
- 1.4.11 Hashing
- 1.4.12 Salting
- 1.4.13 Digital signatures
- 1.4.14 Key stretching
- 1.4.15 Blockchain
- 1.4.16 Open public ledger
- 1.4.17 Certificates (Certificate authorities, CRLs, OCSP, Self-signed, Third-party, Root of trust, CSR generation, Wildcard)

---

# VOLUME 2 — Domain 2.0: Threats, Vulnerabilities, and Mitigations (22%)

### Objective 2.1 — Compare and contrast common threat actors and motivations.
- 2.1.1 Threat actors (Nation-state, Unskilled attacker, Hacktivist, Insider threat, Organized crime, Shadow IT)
- 2.1.2 Attributes of actors (Internal/external, Resources/funding, Level of sophistication/capability)
- 2.1.3 Motivations (Data exfiltration, Espionage, Service disruption, Blackmail, Financial gain, Philosophical/political beliefs, Ethical, Revenge, Disruption/chaos, War)

### Objective 2.2 — Explain common threat vectors and attack surfaces.
- 2.2.1 Message-based (Email, SMS, Instant messaging)
- 2.2.2 Image-based
- 2.2.3 File-based
- 2.2.4 Voice call
- 2.2.5 Removable device
- 2.2.6 Vulnerable software (Client-based vs. agentless)
- 2.2.7 Unsupported systems and applications
- 2.2.8 Unsecure networks (Wireless, Wired, Bluetooth)
- 2.2.9 Open service ports
- 2.2.10 Default credentials
- 2.2.11 Supply chain (MSPs, Vendors, Suppliers)
- 2.2.12 Human vectors/social engineering (Phishing, Vishing, Smishing, Misinformation/disinformation, Impersonation, Business email compromise, Pretexting, Watering hole, Brand impersonation, Typosquatting)

### Objective 2.3 — Explain various types of vulnerabilities.
- 2.3.1 Application (Memory injection, Buffer overflow, Race conditions: TOC, TOU, Malicious update)
- 2.3.2 Operating system (OS)-based
- 2.3.3 Web-based (SQLi, XSS)
- 2.3.4 Hardware (Firmware, End-of-life, Legacy)
- 2.3.5 Virtualization (VM escape, Resource reuse)
- 2.3.6 Cloud-specific
- 2.3.7 Supply chain (Service provider, Hardware provider, Software provider)
- 2.3.8 Cryptographic
- 2.3.9 Misconfiguration
- 2.3.10 Mobile device (Side loading, Jailbreaking)
- 2.3.11 Zero-day

### Objective 2.4 — Given a scenario, analyze indicators of malicious activity.
- 2.4.1 Malware attacks (Ransomware, Trojan, Worm, Spyware, Bloatware, Virus, Keylogger, Logic bomb, Rootkit)
- 2.4.2 Physical attacks (Brute force, RFID cloning, Environmental)
- 2.4.3 Network attacks (DDoS: Amplified, Reflected; DNS attacks, Wireless, On-path, Credential replay, Malicious code)
- 2.4.4 Application attacks (Injection, Buffer overflow, Replay, Privilege escalation, Forgery, Directory traversal)
- 2.4.5 Cryptographic attacks (Downgrade, Collision, Birthday)
- 2.4.6 Password attacks (Spraying, Brute force)
- 2.4.7 Indicators (Account lockout, Concurrent session usage, Blocked content, Impossible travel, Resource consumption, Resource inaccessibility, Out-of-cycle logging, Published/documented, Missing logs)

### Objective 2.5 — Explain the purpose of mitigation techniques used to secure the enterprise.
- 2.5.1 Segmentation
- 2.5.2 Access control (Access control list (ACL), Permissions)
- 2.5.3 Application allow list
- 2.5.4 Isolation
- 2.5.5 Patching
- 2.5.6 Encryption
- 2.5.7 Monitoring
- 2.5.8 Least privilege
- 2.5.9 Configuration enforcement
- 2.5.10 Decommissioning
- 2.5.11 Hardening techniques (Encryption, Installation of endpoint protection, Host-based firewall, HIPS, Disabling ports/protocols, Default password changes, Removal of unnecessary software)

---

# VOLUME 3 — Domain 3.0: Security Architecture (18%)

### Objective 3.1 — Compare and contrast security implications of different architecture models.
- 3.1.1 Architecture and infrastructure concepts — Cloud (Responsibility matrix, Hybrid considerations, Third-party vendors)
- 3.1.2 Infrastructure as code (IaC)
- 3.1.3 Serverless
- 3.1.4 Microservices
- 3.1.5 Network infrastructure (Physical isolation: Air-gapped; Logical segmentation; Software-defined networking (SDN))
- 3.1.6 On-premises
- 3.1.7 Centralized vs. decentralized
- 3.1.8 Containerization
- 3.1.9 Virtualization
- 3.1.10 IoT
- 3.1.11 ICS/SCADA
- 3.1.12 Real-time operating system (RTOS)
- 3.1.13 Embedded systems
- 3.1.14 High availability
- 3.1.15 Considerations (Availability, Resilience, Cost, Responsiveness, Scalability, Ease of deployment, Risk transference, Ease of recovery, Patch availability, Inability to patch, Power, Compute)

### Objective 3.2 — Given a scenario, apply security principles to secure enterprise infrastructure.
- 3.2.1 Infrastructure considerations (Device placement, Security zones, Attack surface, Connectivity, Failure modes: Fail-open/Fail-closed, Device attribute: Active vs. passive/Inline vs. tap/monitor)
- 3.2.2 Network appliances (Jump server, Proxy server, IPS/IDS, Load balancer, Sensors)
- 3.2.3 Port security (802.1X, EAP)
- 3.2.4 Firewall types (WAF, UTM, NGFW, Layer 4/Layer 7)
- 3.2.5 Secure communication/access (VPN, Remote access, Tunneling: TLS, IPSec; SD-WAN, SASE)
- 3.2.6 Selection of effective controls

### Objective 3.3 — Compare and contrast concepts and strategies to protect data.
- 3.3.1 Data types (Regulated, Trade secret, Intellectual property, Legal information, Financial information, Human- and non-human-readable)
- 3.3.2 Data classifications (Sensitive, Confidential, Public, Restricted, Private, Critical)
- 3.3.3 General data considerations (Data states: at rest/in transit/in use; Data sovereignty; Geolocation)
- 3.3.4 Methods to secure data (Geographic restrictions, Encryption, Hashing, Masking, Tokenization, Obfuscation, Segmentation, Permission restrictions)

### Objective 3.4 — Explain the importance of resilience and recovery in security architecture.
- 3.4.1 High availability (Load balancing vs. clustering)
- 3.4.2 Site considerations (Hot, Cold, Warm, Geographic dispersion)
- 3.4.3 Platform diversity
- 3.4.4 Multi-cloud systems
- 3.4.5 Continuity of operations
- 3.4.6 Capacity planning (People, Technology, Infrastructure)
- 3.4.7 Testing (Tabletop exercises, Fail over, Simulation, Parallel processing)
- 3.4.8 Backups (Onsite/offsite, Frequency, Encryption, Snapshots, Recovery, Replication, Journaling)
- 3.4.9 Power (Generators, Uninterruptible power supply (UPS))

---

# VOLUME 4 — Domain 4.0: Security Operations (28%)

### Objective 4.1 — Given a scenario, apply common security techniques to computing resources.
- 4.1.1 Secure baselines (Establish, Deploy, Maintain)
- 4.1.2 Hardening targets (Mobile devices, Workstations, Switches, Routers, Cloud infrastructure, Servers, ICS/SCADA, Embedded systems, RTOS, IoT devices)
- 4.1.3 Wireless devices (Installation considerations: Site surveys, Heat maps)
- 4.1.4 Mobile solutions (MDM, Deployment models: BYOD/COPE/CYOD, Connection methods: Cellular/Wi-Fi/Bluetooth)
- 4.1.5 Wireless security settings (WPA3, AAA/RADIUS, Cryptographic protocols, Authentication protocols)
- 4.1.6 Application security (Input validation, Secure cookies, Static code analysis, Code signing)
- 4.1.7 Sandboxing
- 4.1.8 Monitoring

### Objective 4.2 — Explain the security implications of proper hardware, software, and data asset management.
- 4.2.1 Acquisition/procurement process
- 4.2.2 Assignment/accounting (Ownership, Classification)
- 4.2.3 Monitoring/asset tracking (Inventory, Enumeration)
- 4.2.4 Disposal/decommissioning (Sanitization, Destruction, Certification, Data retention)

### Objective 4.3 — Explain various activities associated with vulnerability management.
- 4.3.1 Identification methods (Vulnerability scan, Application security: Static/Dynamic analysis/Package monitoring; Threat feed: OSINT/Proprietary/Information-sharing/Dark web; Penetration testing, Responsible disclosure program: Bug bounty; System/process audit)
- 4.3.2 Analysis (Confirmation: False positive/False negative; Prioritize, CVSS, CVE, Vulnerability classification, Exposure factor, Environmental variables, Industry/organizational impact, Risk tolerance)
- 4.3.3 Vulnerability response and remediation (Patching, Insurance, Segmentation, Compensating controls, Exceptions and exemptions)
- 4.3.4 Validation of remediation (Rescanning, Audit, Verification)
- 4.3.5 Reporting

### Objective 4.4 — Explain security alerting and monitoring concepts and tools.
- 4.4.1 Monitoring computing resources (Systems, Applications, Infrastructure)
- 4.4.2 Activities (Log aggregation, Alerting, Scanning, Reporting, Archiving, Alert response and remediation/validation: Quarantine/Alert tuning)
- 4.4.3 Tools (SCAP, Benchmarks, Agents/agentless, SIEM, Antivirus, DLP, SNMP traps, NetFlow, Vulnerability scanners)

### Objective 4.5 — Given a scenario, modify enterprise capabilities to enhance security.
- 4.5.1 Firewall (Rules, Access lists, Ports/protocols, Screened subnets)
- 4.5.2 IDS/IPS (Trends, Signatures)
- 4.5.3 Web filter (Agent-based, Centralized proxy, URL scanning, Content categorization, Block rules, Reputation)
- 4.5.4 Operating system security (Group Policy, SELinux)
- 4.5.5 Implementation of secure protocols (Protocol selection, Port selection, Transport method)
- 4.5.6 DNS filtering
- 4.5.7 Email security (DMARC, DKIM, SPF, Gateway)
- 4.5.8 File integrity monitoring
- 4.5.9 DLP
- 4.5.10 Network access control (NAC)
- 4.5.11 Endpoint detection and response (EDR)/extended detection and response (XDR)
- 4.5.12 User behavior analytics

### Objective 4.6 — Given a scenario, implement and maintain identity and access management.
- 4.6.1 Provisioning/de-provisioning user accounts
- 4.6.2 Permission assignments and implications
- 4.6.3 Identity proofing
- 4.6.4 Federation
- 4.6.5 Single sign-on (SSO) (LDAP, OAuth, SAML)
- 4.6.6 Interoperability
- 4.6.7 Attestation
- 4.6.8 Access controls (Mandatory, Discretionary, Role-based, Rule-based, Attribute-based, Time-of-day restrictions, Least privilege)
- 4.6.9 Multifactor authentication (Implementations: Biometrics/Hard-soft tokens/Security keys; Factors: Something you know/have/are/Somewhere you are)
- 4.6.10 Password concepts (Best practices: Length/Complexity/Reuse/Expiration/Age; Password managers, Passwordless)
- 4.6.11 Privileged access management tools (Just-in-time permissions, Password vaulting, Ephemeral credentials)

### Objective 4.7 — Explain the importance of automation and orchestration related to secure operations.
- 4.7.1 Use cases of automation and scripting (User provisioning, Resource provisioning, Guard rails, Security groups, Ticket creation, Escalation, Enabling/disabling services and access, Continuous integration and testing, Integrations and APIs)
- 4.7.2 Benefits (Efficiency/time saving, Enforcing baselines, Standard infrastructure configurations, Scaling in a secure manner, Employee retention, Reaction time, Workforce multiplier)
- 4.7.3 Other considerations (Complexity, Cost, Single point of failure, Technical debt, Ongoing supportability)

### Objective 4.8 — Explain appropriate incident response activities.
- 4.8.1 Process (Preparation, Detection, Analysis, Containment, Eradication, Recovery, Lessons learned)
- 4.8.2 Training
- 4.8.3 Testing (Tabletop exercise, Simulation)
- 4.8.4 Root cause analysis
- 4.8.5 Threat hunting
- 4.8.6 Digital forensics (Legal hold, Chain of custody, Acquisition, Reporting, Preservation, E-discovery)

### Objective 4.9 — Given a scenario, use data sources to support an investigation.
- 4.9.1 Log data (Firewall logs, Application logs, Endpoint logs, OS-specific security logs, IPS/IDS logs, Network logs, Metadata)
- 4.9.2 Data sources (Vulnerability scans, Automated reports, Dashboards, Packet captures)

---

# VOLUME 5 — Domain 5.0: Security Program Management and Oversight (20%)

### Objective 5.1 — Summarize elements of effective security governance.
- 5.1.1 Guidelines
- 5.1.2 Policies (AUP, Information security policies, Business continuity, Disaster recovery, Incident response, SDLC, Change management)
- 5.1.3 Standards (Password, Access control, Physical security, Encryption)
- 5.1.4 Procedures (Change management, Onboarding/offboarding, Playbooks)
- 5.1.5 External considerations (Regulatory, Legal, Industry, Local/regional, National, Global)
- 5.1.6 Monitoring and revision
- 5.1.7 Types of governance structures (Boards, Committees, Government entities, Centralized/decentralized)
- 5.1.8 Roles and responsibilities for systems and data (Owners, Controllers, Processors, Custodians/stewards)

### Objective 5.2 — Explain elements of the risk management process.
- 5.2.1 Risk identification
- 5.2.2 Risk assessment (Ad hoc, Recurring, One-time, Continuous)
- 5.2.3 Risk analysis (Qualitative, Quantitative, SLE, ALE, ARO, Probability, Likelihood, Exposure factor, Impact)
- 5.2.4 Risk register (Key risk indicators, Risk owners, Risk threshold)
- 5.2.5 Risk tolerance
- 5.2.6 Risk appetite (Expansionary, Conservative, Neutral)
- 5.2.7 Risk management strategies (Transfer, Accept: Exemption/Exception; Avoid, Mitigate)
- 5.2.8 Risk reporting
- 5.2.9 Business impact analysis (RTO, RPO, MTTR, MTBF)

### Objective 5.3 — Explain the processes associated with third-party risk assessment and management.
- 5.3.1 Vendor assessment (Penetration testing, Right-to-audit clause, Evidence of internal audits, Independent assessments, Supply chain analysis)
- 5.3.2 Vendor selection (Due diligence, Conflict of interest)
- 5.3.3 Agreement types (SLA, MOA, MOU, MSA, WO/SOW, NDA, BPA)
- 5.3.4 Vendor monitoring
- 5.3.5 Questionnaires
- 5.3.6 Rules of engagement

### Objective 5.4 — Summarize elements of effective security compliance.
- 5.4.1 Compliance reporting (Internal, External)
- 5.4.2 Consequences of non-compliance (Fines, Sanctions, Reputational damage, Loss of license, Contractual impacts)
- 5.4.3 Compliance monitoring (Due diligence/care, Attestation and acknowledgement, Internal and external, Automation)
- 5.4.4 Privacy (Legal implications: Local/regional/National/Global; Data subject, Controller vs. processor, Ownership, Data inventory and retention, Right to be forgotten)

### Objective 5.5 — Explain types and purposes of audits and assessments.
- 5.5.1 Attestation
- 5.5.2 Internal (Compliance, Audit committee, Self-assessments)
- 5.5.3 External (Regulatory, Examinations, Assessment, Independent third-party audit)
- 5.5.4 Penetration testing (Physical, Offensive, Defensive, Integrated, Known/Partially known/Unknown environment, Reconnaissance: Passive/Active)

### Objective 5.6 — Given a scenario, implement security awareness practices.
- 5.6.1 Phishing (Campaigns, Recognizing a phishing attempt, Responding to reported suspicious messages)
- 5.6.2 Anomalous behavior recognition (Risky, Unexpected, Unintentional)
- 5.6.3 User guidance and training (Policy/handbooks, Situational awareness, Insider threat, Password management, Removable media and cables, Social engineering, Operational security, Hybrid/remote work)
- 5.6.4 Reporting and monitoring (Initial, Recurring)
- 5.6.5 Development
- 5.6.6 Execution

---

# VOLUME 6 — Security+ Master Reference

*(Cross-volume reference; not tied to a single objective. Built after the five core domains so it can cite finished chapters.)*

1. Ports & Protocols Reference
2. Complete Acronym Dictionary
3. Cryptography Reference (algorithms, key lengths, modes)
4. Certificates & PKI Reference
5. Authentication Reference (factors, protocols, models)
6. Linux Commands Reference
7. Windows Commands Reference
8. Networking Commands Reference
9. PowerShell Reference
10. Wireless Standards Reference
11. Cloud Models Reference
12. Threat Actors Reference
13. Malware Reference
14. Attack Types Reference
15. Security Controls Reference
16. Frameworks Reference
17. Compliance Reference
18. Security Tools Reference
19. PBQ Guide
20. Exam Cheat Sheets
21. Mnemonics
22. Comparison Tables (master index)

---

# VOLUME 7 — Security+ to SOC Analyst Roadmap

*(Career bridge; goes beyond the exam into job-readiness.)*

1. Networking for the SOC
2. Linux for the SOC
3. Windows Security
4. Active Directory
5. Wireshark
6. Nmap
7. Splunk
8. Microsoft Sentinel
9. MITRE ATT&CK
10. Cyber Kill Chain
11. Threat Hunting
12. Detection Engineering
13. SIEM
14. SOAR
15. EDR
16. XDR
17. OWASP Top 10
18. Burp Suite
19. Cloud Security
20. Home Lab
21. Virtual Machines
22. GitHub Portfolio
23. Resume
24. LinkedIn
25. Interview Preparation
26. 30-Day Roadmap
27. 90-Day Roadmap
28. 6-Month Roadmap
29. 12-Month Roadmap

---

# APPENDICES (after all five core domains)

- A. Ports & Protocols Reference
- B. Complete Acronym Dictionary
- C. Cryptography Reference
- D. Authentication Reference
- E. Networking Reference
- F. Linux Commands
- G. Windows Commands
- H. Security Tools
- I. PBQ Guide
- J. Exam Cheat Sheets
- K. Full Practice Exams
- L. Security+ Mistake Journal Template

---

## Per-Objective Chapter Template (applied to every objective)

1. Official Objective Number
2. Official CompTIA Objective Statement
3. Learning Outcomes
4. Concept Overview
5. Definitions
6. Deep Technical Explanation
7. Why It Exists
8. How It Works
9. Advantages
10. Disadvantages
11. Real-World Examples
12. Enterprise Usage
13. Security Implications
14. Attacker Perspective
15. Defender Perspective
16. Detection Techniques
17. Mitigation Techniques
18. Best Practices
19. Comparison Tables
20. ASCII Diagrams (when appropriate)
21. Exam Tips
22. Common CompTIA Question Styles
23. Interview Notes
24. Common Beginner Mistakes
25. Related Concepts
26. Memory Tricks
27. Key Facts
28. Quick Revision Sheet
29. Practice Questions
30. PBQ-style Scenarios (where appropriate)

> **Subsection rule:** every official sub-bullet becomes its own fully-taught subsection,
> completed before moving to the next.
