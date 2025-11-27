# Unit 4 – Summary

Short list of topics, simple meanings, and key full forms.

## Main Topics & Simple Definitions

- **Data Classification & Tagging:** Mark data as **public, internal, confidential, etc.**, and add tags to show type, owner, and rules.
- **Data Management (Quality, Lineage):** Make sure data is **correct, complete, and traceable** from source to report.
- **Data Security Posture Management (DSPM):** Continuous **check of where sensitive data is, who can access it, and what risks exist**, especially in cloud.
- **Auditing & Logs:** **Record who did what, when, and from where** to prove control and find problems.
- **GDPR Right to be Forgotten:** User’s right to **have their personal data deleted** when certain conditions are met.
- **Ransomware Incident Response Steps:** **Detect → contain → remove malware → restore from clean backups → review and improve**.
- **Simple Logging for Failed Logins:** Store **time, user ID, IP, and result** to detect brute‑force or unusual login attempts.
- **Backup & Replication for Microservices:** Use **backups, snapshots, and replication** for databases and configs in cloud‑native apps.
- **ISO 27001 Controls:** Standard set of **information security rules** (access control, physical security, incident management, etc.).
- **Bulk Recovery / Bare‑Metal Restore:** **Rebuild full servers or many systems at once** from images/backups after big failure.
- **Classification Across Storage Tiers:** Keep personal/sensitive data **tagged and protected** even as it moves from hot to cold storage.
- **Encryption & Tokenization for Analytics:** Use **encryption and tokenization** to protect sensitive fields while still allowing reports.
- **Insider Threat Monitoring:** Use logs and rules to **spot large or strange data transfers**, especially at odd times.
- **Recovery Plan for Mid‑Size Enterprise:** Decide **which systems to restore first**, and **check data integrity** after recovery.
- **HIPAA in Cloud:** Protect health data in cloud with **strong access control, encryption, and audit logs**.
- **PCI DSS Requirement 3 (Stored Data):** Focus on **encrypting and protecting cardholder data at rest**.
- **AI/ML for Anomaly Detection:** Use models to **find unusual patterns in logs/network** that may mean attacks.
- **Phishing Incident Response:** **Block malicious emails, reset passwords, check devices and logs**, and train users.
- **Kubernetes Recovery Best Practices:** Restore **cluster configuration (YAML, etcd) and PVs**, then verify apps.
- **RBAC in Analytics Pipelines:** Let data scientists use **masked/aggregated data**, not raw sensitive data.
- **Multi‑Cloud vs Hybrid DR:** Multi‑cloud = **many clouds**; hybrid = **on‑prem + cloud** – both need careful planning for DR.
- **Metadata Tagging for Residency:** Use tags like **country/region** to ensure data **stays in allowed locations**.
- **PCI vs HIPAA Differences:** PCI = **card data**, HIPAA = **health data**; both have **different scope and exact rules**.
- **Data Stewardship:** People/roles who **own data quality, meaning, and policy** across systems.
- **ETL Backup & Retention:** Back up **source data, configs, and outputs**; keep only as long as needed.
- **AI/ML Pipeline Security Risks:** Risks like **data poisoning (bad training data)** and **stolen models**.
- **AI for Compliance Monitoring:** Use AI to **auto‑check logs and configs for policy violations**, but watch for **false positives**.
- **Cyber Recovery Vault Critique:** Vault for clean backups must be **isolated, tested, and regularly updated**, not just stored.
- **Automated Recovery & Failover:** Systems that **auto‑move traffic and restart services** when there is a failure.
- **Five‑Year Retention Policy:** Rules on **what to keep, where, and how to delete safely** after 5 years.
- **Monitoring & Logging Workflow:** Decide **which layer (web, app, DB, OS, network)** logs which metrics.
- **Cyber Recovery Fire Drill:** Test **full recovery steps, roles, and timing** for a real‑like cyber incident.
- **DR for Geo‑Distributed NoSQL:** Handle **regional failures and eventual consistency** when some nodes go down.
- **Multi‑Tenant SaaS Governance:** Make sure **one customer’s data cannot be seen by others** and access is properly separated.
- **Edge Computing Compliance:** Ensure **edge/IoT devices** use encryption, have physical security, and follow data rules.

## Important Terms & Full Forms

- **DSPM – Data Security Posture Management:** Continuous view of **data security risks and posture**, mainly in cloud.
- **GDPR – General Data Protection Regulation:** EU law for **personal data protection and privacy**.
- **HIPAA – Health Insurance Portability and Accountability Act:** US law to **protect patient health data**.
- **PCI DSS – Payment Card Industry Data Security Standard:** Rules to **protect cardholder data**.
- **ISO 27001:** International standard for **information security management systems (ISMS)**.
- **RBAC – Role‑Based Access Control:** Giving access **based on roles**, not individuals.
- **DR – Disaster Recovery:** Plan and tools to **bring systems and data back** after big failures.
- **CR – Cyber Recovery:** Focused on **recovering from cyber attacks**, especially ransomware.
- **ETL – Extract, Transform, Load:** Process to **take data from sources, change it, and load to target** systems.
- **NoSQL:** **Non‑relational databases** (like Cassandra, MongoDB) designed for scale and flexible models.
- **SaaS – Software as a Service:** Software delivered **over the internet**, managed by the provider.
- **IoT – Internet of Things:** **Smart, connected devices** like sensors, cameras, and meters.
