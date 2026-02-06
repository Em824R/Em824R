👨🏿‍💻 Diagnostic Rigor in Data Infrastructure

Senior SQL Server DBA • Azure SQL • AWS RDS • Always On
I design resilient, observable database platforms and fix root causes—not symptoms.


---

🧠 Diagnostic Rigor Manifesto

Treat incidents as clinical cases, not tickets to close.

Eliminate pathology at the source: schema, plans, statistics, architecture.

High Availability is design property, not a feature toggle.

Backups are only real when restores are proven.

Telemetry before opinions; evidence before changes.



---

🛠 Core Tooling

       
---

🧩 Architecture Mental Model

[Applications]
      │
[Read Replicas / AG Secondaries]
      │
[Primary SQL Platform]
      │
[Telemetry Layer: XEvents | Query Store | DMVs]
      │
[Automation: dbatools | GitHub Actions]
      │
[Backups 3-2-1-1-0 + Restore Drills]


---

🚦 Featured Projects (Starter Cockpit)

1) sql-diagnostic-toolkit

Purpose: Rapid clinical assessment of SQL Server health

Blocking chain collector (XEvents)

Parameter sniffing detector

AG latency & redo monitor

I/O saturation profiler
Outcome: MTTR from hours → minutes


2) dba-automation-lab

Purpose: Prevent the outage before it starts

dbatools patch orchestration

Backup validation (3-2-1-1-0)

Index & stats maintenance pipelines

Drift detection for configuration


3) alwayson-runbooks

Purpose: Safe, repeatable HA/DR operations

Failover decision tree

Split-brain recovery steps

Read-only routing validation


4) migration-playbooks

Purpose: Zero-downtime platform moves

SQL → Azure SQL MI patterns

AWS RDS Custom cutover

Data validation checklists



---

🧪 What I Work On

Performance engineering & Query Store forensics

Hybrid HA/DR across Azure & AWS

Secure data platforms (TDE, RLS, DDM, Audit)

Telemetry-first operations

Restore-tested backup strategy



---

🤝 Connect

I collaborate with teams where reliability is mission-critical and evidence beats guesswork.
