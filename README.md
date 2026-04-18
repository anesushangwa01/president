# General Handbook — Ministering Structure
### Harare Zimbabwe South Stake — Unit Level
**Date:** 13 April 2026
**Focus:** Causes & Generations

---

## Ministering Organisation Chart

```mermaid
flowchart TD
    Bishop(["🏛️ Bishop\nPresiding / MV Assist"])

    EQP(["👤 EQ President\n(Elders Quorum)"])
    RSP(["👤 RS President\n(Relief Society)"])

    EQC["👥 Counselor\n(Responsible for\nMinistering 2nd)"]
    RSC["👥 Counselor\n(Responsible for\nMinistering 2nd)"]

    EQMIN["📋 Ministerials\n(EQ)"]
    RSMIN["📋 Ministerials\n(RS)"]

    EQCOMP["👫 EQ Presidents\n+ Companions"]
    RSCOMP["👫 RS Presidents\n+ LS Presidents"]

    EQFAM["🏠 Assigned Families\n(EQ)"]
    RSFAM["🏠 Assigned Families\n(RS)"]

    EQINT["🗓️ Interviews\n(EQ)"]
    RSINFO["📢 Inform Ward Council\n+ LCR (RS)"]

    MIN(["🤝 Ministering\n(Goal & Outcome)"])

    Bishop -->|"delegates"| EQP
    Bishop -->|"delegates"| RSP

    EQP --> EQC
    RSP --> RSC

    EQC --> EQMIN
    RSC --> RSMIN

    EQMIN --> EQCOMP
    RSMIN --> RSCOMP

    EQCOMP --> EQFAM
    RSCOMP --> RSFAM

    EQCOMP --> EQINT
    RSCOMP --> RSINFO

    EQFAM --> MIN
    RSFAM --> MIN

    style Bishop fill:#4A90D9,color:#fff,stroke:#2c5f8a
    style EQP fill:#5B8DD9,color:#fff,stroke:#2c5f8a
    style RSP fill:#D96B8A,color:#fff,stroke:#8a2c4a
    style EQC fill:#7BAAD4,color:#fff,stroke:#2c5f8a
    style RSC fill:#D98AA8,color:#fff,stroke:#8a2c4a
    style EQMIN fill:#A8C8E8,color:#333,stroke:#2c5f8a
    style RSMIN fill:#E8A8C0,color:#333,stroke:#8a2c4a
    style EQCOMP fill:#C8DFF0,color:#333,stroke:#2c5f8a
    style RSCOMP fill:#F0C8D8,color:#333,stroke:#8a2c4a
    style EQFAM fill:#E8F4E8,color:#333,stroke:#2c7a2c
    style RSFAM fill:#F4E8F4,color:#333,stroke:#7a2c7a
    style EQINT fill:#FFF0C0,color:#333,stroke:#8a6a00
    style RSINFO fill:#FFF0C0,color:#333,stroke:#8a6a00
    style MIN fill:#2ECC71,color:#fff,stroke:#1a8a4a
```

---

## Key Roles & Responsibilities

| Role | Responsibility |
|------|---------------|
| **Bishop** | Presides over the unit; delegates ministering oversight |
| **EQ President** | Oversees Elders Quorum ministering assignments |
| **RS President** | Oversees Relief Society ministering assignments |
| **Counselor (EQ)** | Directly responsible for EQ ministering coordination |
| **Counselor (RS)** | Directly responsible for RS ministering coordination |
| **Ministerials (EQ)** | Assigned ministering brothers |
| **Ministerials (RS)** | Assigned ministering sisters |
| **LS Presidents** | Assist RS Presidents; report to Ward Council + LCR |

---

## Ministering Flow

1. **Bishop** presides and assigns oversight to **EQ President** and **RS President**
2. Each president appoints a **Counselor** responsible for ministering coordination
3. Counselors manage **Ministerial assignments** (brothers/sisters with companions)
4. Each pair is given **Assigned Families** to minister to
5. **EQ** tracks progress through **interviews**; **RS** reports to **Ward Council & LCR**
6. The outcome and goal is effective **Ministering** across all assigned families

---

## Companions Model

```mermaid
flowchart LR
    subgraph EQ_Side ["⚡ Elders Quorum Side"]
        direction TB
        EQM1["👤 EQ Minister 1\n+ Companion"]
        EQM2["👤 EQ Minister 2\n+ Companion"]
        EQM3["👤 EQ Minister 3\n+ Companion"]
        EQF1["🏠 Family A"]
        EQF2["🏠 Family B"]
        EQF3["🏠 Family C"]
        EQM1 --> EQF1
        EQM2 --> EQF2
        EQM3 --> EQF3
    end

    subgraph RS_Side ["💜 Relief Society Side"]
        direction TB
        RSM1["👤 RS Minister 1\n+ Companion"]
        RSM2["👤 RS Minister 2\n+ Companion"]
        RSM3["👤 RS Minister 3\n+ Companion"]
        RSF1["🏠 Family A"]
        RSF2["🏠 Family B"]
        RSF3["🏠 Family C"]
        RSM1 --> RSF1
        RSM2 --> RSF2
        RSM3 --> RSF3
    end

    style EQ_Side fill:#E8F4FF,stroke:#4A90D9
    style RS_Side fill:#FFF0F5,stroke:#D96B8A
```

---

*Harare Zimbabwe South Stake — General Handbook Ministering Reference*
*Date: 13 April 2026*
