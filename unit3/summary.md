# Unit 3 – Summary

Short list of topics, simple meanings, and key full forms.

## Main Topics & Simple Definitions

- **Identity and Access Management (IAM):** System to **decide who can access what**, using logins, roles, and permissions.
- **Least Privilege:** Give each user **only the access they truly need**, nothing extra.
- **Encryption (In Transit & At Rest):** **Scrambling data** while it moves on networks and while stored on disks.
- **TLS / HTTPS:** Security layer that **protects web traffic** from spying and tampering.
- **Zero Trust Security:** **“Never trust, always verify”** – check identity and context every time, even inside the network.
- **Hybrid Cloud Security Challenges:** Keeping **same policies and good network separation** across on‑prem + cloud.
- **Logging & Monitoring for Compliance:** Keeping **detailed logs** of actions so you can **prove what happened**.
- **Containers vs VMs Security:** Containers **share the OS kernel**, VMs have **separate OS** – different isolation levels.
- **Multi‑Factor Authentication (MFA):** Login using **two or more factors** (password, OTP, device, biometrics).
- **IDS/IPS (Intrusion Detection/Prevention):** Tools that **watch traffic for attacks** and can **block or alert**.
- **Tokenization (e.g., Card Data):** Replace **real sensitive values with tokens** so databases don’t store real data.
- **Hashing & Salting Passwords:** Store **hashes + random salt**, not plain passwords, to resist cracking.
- **SIEM for Insider Threats:** Collect logs in one place and **spot strange user behavior**.
- **TDE – Transparent Data Encryption:** **Encrypt database files** automatically on disk.
- **Cloud‑Native Security Tools:** Use **security groups, WAF, IAM, etc.** built into cloud.
- **DoS vs DDoS Attacks:** **DoS = one source**, **DDoS = many sources** flooding a service.
- **Symmetric vs Asymmetric Encryption:** **Symmetric = one key**, fast; **asymmetric = key pair**, used for key exchange/signing.
- **Proactive vs Reactive Monitoring:** **Proactive = watch and hunt**, **reactive = respond after alerts/incidents**.
- **VM Escape Risk:** Attack where someone **breaks out of a VM to control the host**.
- **Cloud Firewalls vs Third‑Party Appliances:** Built‑in vs external tools, trade‑off in **features vs complexity**.
- **API Misconfig & BOLA:** Weak API access checks can let users **see others’ data**.
- **Key Rotation:** **Changing keys regularly** to limit damage if a key is stolen.
- **DoS Mitigation Techniques:** Use **rate limiting, WAF, CAPTCHAs, extra capacity, and scrubbing**.
- **Ransomware Detection Limits:** Many tools use **signatures**, so **new, unknown attacks** are harder to catch.
- **Compliance Frameworks (PCI DSS, HIPAA, etc.):** Standard sets of **security controls** by industry.
- **Password‑Only Policy Weakness:** Only passwords are **easy to steal/brute‑force**, so MFA is needed.
- **Continuous Auditing:** Constant checking of **configs and controls** to catch drift.
- **Threat Detection Approaches:** **Signature‑based, anomaly‑based, behavior‑based** – each with pros/cons.
- **STRIDE Threat Modeling:** Method to **list possible threat types** (Spoofing, Tampering, etc.).
- **Zero‑Trust for Startups:** Start small with **MFA, network split, and strict IAM**, then grow.
- **Endpoint Security for Remote Work:** Protect **laptops and devices** on home/public networks.
- **Key Lifecycle with HSM:** **Generate, store, rotate, and destroy keys** in secure hardware.
- **Defense‑in‑Depth:** Multiple **layers of security** – physical, network, host, app, data.
- **Insider Threat IR Plan:** Steps to **detect, investigate, and respond** to insider misuse.
- **GDPR Cloud Governance Checklist:** Controls for **data location, consent, and minimization** in cloud.
- **Ransomware Backup & Recovery:** Use **immutable, isolated backups** to restore after attack.
- **High Availability vs DoS:** Use **redundant servers and load balancers** to keep services up.
- **AI‑Driven Anomaly Detection:** Use ML models to **spot strange traffic or log patterns**.
- **RBAC for University Cloud:** Roles for **students, teachers, admins** with different access.
- **Cyber Recovery Fire Drill:** Practice **full technical + communication recovery** like a real attack.

## Important Terms & Full Forms

- **IAM – Identity and Access Management:** Controls **who can do what** on systems.
- **TLS – Transport Layer Security:** Protocol to **secure data in transit** (used in HTTPS).
- **HTTPS – HyperText Transfer Protocol Secure:** **Web protocol over TLS** for safe browsing.
- **MFA – Multi‑Factor Authentication:** Login using **two or more independent factors**.
- **IDS – Intrusion Detection System:** Tool that **detects attacks** in traffic.
- **IPS – Intrusion Prevention System:** Tool that **detects and blocks** attacks.
- **SIEM – Security Information and Event Management:** System that **collects and analyzes security logs**.
- **TDE – Transparent Data Encryption:** Database feature that **encrypts data at rest** automatically.
- **DoS – Denial of Service:** Attack that **overloads a service from one source**.
- **DDoS – Distributed Denial of Service:** DoS from **many sources/bots at once**.
- **VM – Virtual Machine:** Software‑based **virtual computer**.
- **WAF – Web Application Firewall:** Firewall **designed to protect web apps**.
- **PCI DSS – Payment Card Industry Data Security Standard:** Rules to **protect cardholder data**.
- **HIPAA – Health Insurance Portability and Accountability Act:** US law to **protect health data**.
- **STRIDE:** Threat model acronym – **Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, Elevation of privilege**.
- **HSM – Hardware Security Module:** **Special device** that securely stores and manages keys.
- **RBAC – Role‑Based Access Control:** Give permissions based on **roles instead of individuals**.
- **IRP – Incident Response Plan:** **Step‑by‑step plan** to handle security incidents.
