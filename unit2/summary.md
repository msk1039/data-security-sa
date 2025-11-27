# Unit 2 – Summary

Short list of topics, simple meanings, and key full forms.

## Main Topics & Simple Definitions

- **Snapshots:** Quick **point‑in‑time pictures of data/VMs** used for fast rollback.
- **Copy Data Management (CDM):** Tools to **create many test/dev copies** of data quickly and with less storage.
- **Data Deduplication:** **Remove duplicate data blocks** so the same content is stored only once.
- **Replication vs Backup:** **Replication = live copy (very small data loss)**; **backup = past copies (bigger gap but history)**.
- **Media Management & 3‑2‑1 Rule:** Proper handling of **tapes/disks/cloud** so you keep **3 copies, 2 media types, 1 offsite**.
- **System Recovery vs Data Restore:** **System recovery = rebuild full server/app stack**; **data restore = just bring back files/data**.
- **Storage Tiering (Hot/Warm/Cold):** Put **active data on fast storage** and **old data on slow, cheap storage**.
- **Cloud Backup Design:** Plan for **cost, egress charges, security, and restore speed** in cloud backups.
- **Protecting Containers & PVs:** Focus on **persistent volumes, cluster configs, and app‑consistent backups** in Kubernetes/Docker.
- **Backup ≠ Archival:** **Backups** are for **short‑term recovery**; **archives** are for **long‑term legal/history**.
- **Snapshot RPO Design:** Use **frequent snapshots** (e.g., every 15 minutes) to meet tight data loss targets.
- **Small Business Backup Plan:** Mix of **daily incremental, weekly full, local + cloud copies**, and **tested restores**.
- **Deduplication Savings:** High dedupe % means **much less real storage** is needed for backups.
- **Near‑Zero RPO Replication:** Use **synchronous/near‑sync replication** between sites for almost no data loss.
- **Tiered Storage in Hybrid Cloud:** Map **active, recent, and old data** to **hot, warm, and cold** tiers across on‑prem + cloud.
- **Media for 7+ Year Retention:** Use **tape and/or cold cloud** for very long‑term, cheap keeping of regulatory data.
- **CDM in DevOps:** Use snapshots/clones in pipelines so **test environments get fresh data quickly**.
- **Kubernetes Data Protection Plan:** Back up **etcd, manifests, and PVs**, and test **full cluster rebuilds**.
- **VM Snapshots for Fast Recovery:** Take **VM snapshots before risky changes**, revert quickly if there’s a problem.
- **Cloud Backup Best Practices:** **Encrypt, limit access, use incrementals, control egress costs, and set lifecycle rules**.
- **Tape vs Disk for Archive:** **Tape = very cheap, slow**; **disk = faster, more expensive**.
- **Snapshots vs File/Image Backups:** **Snapshots store only changes**; **traditional backups copy full files/images**.
- **Inline vs Post‑Process Dedup:** **Inline dedup** happens during write (saves space early, uses CPU); **post‑process** happens later.
- **Sync vs Async Replication:** **Sync = zero RPO, needs low latency**; **async = some data loss but works over distance**.
- **Multi‑Tier Storage Architecture:** Mix of **fast, medium, and slow storage** to meet different app SLAs.
- **Backup vs Archive Confusion:** Treating backups like archives **breaks legal retention and immutability**.
- **Media Failure & RTO:** Bad tapes/disks **delay restores** and can **break RTO promises**.
- **Hybrid/Edge Protection Challenges:** Many small sites and weak links make **central backup harder**.
- **Snapshot Sprawl:** Too many unmanaged snapshots **eat storage** and are hard to track.
- **Latency in Sync Replication:** Extra network delay **slows writes and commits**.
- **Replication Diagrams & Flows:** Show **write path and ACKs** for sync and async modes.
- **RPO/RTO/Cost Trade‑off:** **Lower RPO/RTO = higher cost** (more hardware, network, licenses).
- **Backup Strategy for Fast Restore:** **Full + differential** usually gives **faster restore** than many incrementals.
- **Snapshot‑Only SLA Limits:** Snapshots on the same array **don’t protect against array failure**; need off‑array copies.
- **Tiered Storage Plan (10/30/60):** 10% hot, 30% warm, 60% cold based on how often data is used.
- **DR Flow Across Media:** **Production → disk backup → tape/cloud offsite** for DR and archive.
- **Layered Protection Architecture:** **Production → backup → dedupe → encryption → storage → management**.
- **CDM Policy Framework:** Rules for **who can create clones, how long they live, and how to secure them**.

## Important Terms & Full Forms

- **CDM – Copy Data Management:** Managing **extra copies of data** (dev, test, analytics) in a smart way.
- **RPO – Recovery Point Objective:** **How much data (time) you can afford to lose**.
- **RTO – Recovery Time Objective:** **How fast you must bring systems back** after a failure.
- **VM – Virtual Machine:** **Software‑based computer** running on a hypervisor.
- **PVs – Persistent Volumes:** **Storage used by containers** that keeps data even if pods die.
- **LTO – Linear Tape-Open:** A **popular tape format** for backup/archival.
- **SLA – Service Level Agreement:** **Promised level of service**, like uptime, RPO, RTO.
