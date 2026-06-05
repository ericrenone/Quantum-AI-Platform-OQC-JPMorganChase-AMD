# ⚛️ Quantum-AI Platform — OQC × JPMorganChase × AMD

> **Announced June 3, 2026 · London, UK**  
> A dedicated Quantum-AI Data Centre converging quantum hardware, AI, and high-performance classical computing to solve the hardest problems in financial services.

---

## Table of Contents

- [Overview](#overview)
- [Partners](#partners)
- [Platform Architecture](#platform-architecture)
- [Research Agenda](#research-agenda)
- [Key Applications](#key-applications)
- [Leadership](#leadership)
- [Timeline & Status](#timeline--status)
- [Why This Matters](#why-this-matters)
- [References](#references)

---

## Overview

OQC, JPMorganChase and AMD have launched a research collaboration centred on a dedicated Quantum-AI Data Centre in London to study how quantum computing, AI, and high-performance computing can be combined for financial services applications.

JPMorganChase will be the first dedicated user of the platform, which will integrate OQC's GENESIS quantum system with AMD-supported AI and classical computing infrastructure in a secure enterprise environment expected to be operational within 12 months.

The central ambition: move hybrid quantum-classical applications from isolated laboratory experiments into secure, reproducible, enterprise-grade workflows — tested against the operational standards of global financial services.

---

## Partners

| Partner | Role | Contribution |
|---|---|---|
| **OQC** (Oxford Quantum Circuits) | Platform builder & quantum hardware | GENESIS quantum system; Quantum-AI Data Centre facility |
| **JPMorganChase** | Anchor research user & domain expertise | Financial research agenda; hybrid workflow validation |
| **AMD** | Classical compute & AI infrastructure | HPC resources; AI accelerators; circuit optimisation tooling |

### OQC
UK-headquartered quantum computing company building a secure, scalable Quantum-AI Data Centre platform for enterprise and government customers. The platform integrates quantum computing with trusted infrastructure and AI supercomputing. → [oqc.tech](https://www.oqc.tech)

### JPMorganChase
JPMorgan Chase & Co. (NYSE: JPM) had $4.9 trillion in assets and $364 billion in stockholders' equity as of March 31, 2026. With approximately 65,000 technologists globally and an annual tech investment of $19.8 billion, JPMorganChase is dedicated to improving the design, analytics, development, coding, testing and application programming that goes into creating high quality software and new products. → [jpmorgan.com](https://www.jpmorgan.com/technology)

### AMD
Advanced Micro Devices provides the HPC and AI compute layer — processing infrastructure, accelerators, and classical tooling that surrounds and supports the quantum hardware. → [amd.com](https://www.amd.com)

---

## Platform Architecture

The environment will physically integrate the OQC GENESIS quantum system with AMD-supported AI and classical compute, high-performance computing resources, and application-level tooling for simulation, optimisation, AI model development and benchmarking.

Rather than accessing quantum hardware via public cloud configurations that introduce latency and security risks, the London facility places quantum hardware directly inside a secure enterprise compute environment.

```
┌──────────────────────────────────────────────────────────────────┐
│                   Quantum-AI Data Centre · London                │
│                                                                  │
│   ┌─────────────────────┐        ┌────────────────────────────┐  │
│   │   OQC GENESIS       │◄──────►│   AMD HPC Infrastructure   │  │
│   │   Quantum System    │        │   + AI Accelerators        │  │
│   │   (superconducting) │        │   + Classical Compute      │  │
│   └─────────────────────┘        └────────────────────────────┘  │
│              │                              │                    │
│              └──────────────┬───────────────┘                    │
│                             ▼                                    │
│              ┌──────────────────────────────┐                    │
│              │   Hybrid Orchestration Layer │                    │
│              │   · Error mitigation         │                    │
│              │   · Circuit compilation      │                    │
│              │   · Syndrome extraction      │                    │
│              └──────────────────────────────┘                    │
│                             │                                    │
│                             ▼                                    │
│              ┌──────────────────────────────┐                    │
│              │   JPMorganChase Research     │                    │
│              │   Applications               │                    │
│              └──────────────────────────────┘                    │
└──────────────────────────────────────────────────────────────────┘
```

---

## Research Agenda

The partners will research hybrid quantum-classical use cases including portfolio optimization, quantum machine learning, AI-assisted quantum circuit improvement, and the development of future financial algorithms.

### 1 · Portfolio Optimization
Finding optimal asset allocations across large, constrained solution spaces — QAOA and VQE approaches evaluated against classical integer programming baselines.

### 2 · Quantum Machine Learning
Expanding explorations around quantum-enhanced feature spaces and kernel methods. Evaluating where hybrid quantum-classical ML provides measurable advantage over purely classical approaches.

### 3 · Circuit Performance Optimization
Developing custom classical AI models powered by AMD hardware to automate error mitigation, map logical gates, and optimize circuit compilation directly on the OQC GENESIS superconducting substrate.

### 4 · Fault-Tolerant Algorithm Research
Investigating the role of classical compute towards scalable quantum algorithms. The testing phase will examine how classical supercomputing elements can efficiently handle syndrome extraction loops required to manage future, scalable fault-tolerant quantum algorithms.

### 5 · Novel Financial Algorithm Discovery
Investigating how quantum-enhanced AI models can accelerate the discovery of novel algorithms purpose-built for financial use cases.

---

## Key Applications

| Domain | Quantum Approach | Classical Baseline |
|---|---|---|
| Option pricing | Quantum amplitude estimation | Monte Carlo simulation |
| Portfolio management | QAOA / VQE optimization | Integer programming |
| Risk analysis | Quantum Monte Carlo methods | Variance reduction techniques |
| Machine learning | Quantum kernels, QNNs | Classical neural networks |
| Circuit compilation | AI-assisted gate mapping | Manual / rule-based compilers |

---

## Leadership

| Name | Title | Organisation |
|---|---|---|
| **Gerald Mullally** | CEO | OQC |
| **Lori Beer** | Global Chief Information Officer | JPMorganChase |
| **Mark Papermaster** | Chief Technology Officer | AMD |

> *"Quantum computing has to move from isolated experiments into the secure compute environments where enterprises actually work."*  
> — Gerald Mullally, CEO, OQC

---

## Timeline & Status

| Milestone | Date / Target |
|---|---|
| Research collaboration announced | June 3, 2026 |
| Data centre construction (OQC, London) | Underway |
| GENESIS + AMD infrastructure integration | In progress |
| Platform fully operational | Within 12 months of announcement |
| JPMorganChase as inaugural anchor user | Upon operational launch |

---

## Why This Matters

Three structural shifts in financial services are converging simultaneously:

**Scale** — Portfolio sizes, derivative books, and simulation spaces are growing faster than classical compute scaling can deliver.

**Regulation** — Real-time risk reporting requirements demand faster, more accurate scenario engines with verifiable, reproducible outputs.

**AI integration** — ML workloads increasingly benefit from hybrid quantum-classical computation as problem complexity exceeds classical neural network efficiency.

The deployment moves quantum acceleration out of isolated laboratory setups and into standard data-center environments capable of executing production-grade enterprise workflows. By physically co-locating quantum hardware with classical HPC and AI infrastructure inside a secure enterprise environment, the platform is designed to evaluate hybrid workflows against the data replication, latency, and security standards mandated by global financial services — conditions that cloud-based quantum access cannot currently meet.

---

## References

**Press Release**
- AMD Newsroom: [OQC, JPMorganChase and AMD Commence Research Collaboration](https://www.amd.com/en/newsroom/press-releases/2026-6-3-oqc-jpmorganchase-and-amd-commence-research-collaborata.html) — June 3, 2026
- JPMorganChase Technology Blog: [OQC × JPMorganChase × AMD Quantum-AI Platform](https://www.jpmorganchase.com/about/technology/blog/oqc-jpmc-amd-quantum-ai-platform)

**Coverage**
- The Quantum Insider: [OQC, JPMorganChase and AMD Commence Research Collaboration](https://thequantuminsider.com/2026/06/05/oqc-jpmorganchase-and-amd-commence-research-collaboration-to-develop-new-quantum-ai-platform-in-london/)
- Quantum Computing Report: [OQC, JPMorganChase, and AMD Establish Quantum-AI Data Center Initiative in London](https://quantumcomputingreport.com/oxford-quantum-circuits-jpmorganchase-and-amd-establish-quantum-ai-data-center-initiative-in-london/)
- HPCwire: [OQC, JPMorganChase and AMD to Explore Hybrid Quantum-Classical Computing in Finance](https://www.hpcwire.com/off-the-wire/oqc-jpmorganchase-and-amd-to-explore-hybrid-quantum-classical-computing-in-finance/)
- Tech.eu: [OQC, JPMorgan Chase and AMD launch Quantum-AI data centre](https://tech.eu/2026/06/05/oqc-jpmorgan-chase-and-amd-launch-dedicated-quantum-ai-data-centre-to-explore-real-world-financial-applications/)
- CIOTechOutlook: [OQC, JPMorgan, AMD Team Up on Quantum AI Platform](https://www.ciotechoutlook.com/news/oqc-jpmorgan-amd-team-up-on-quantum-ai-platform-nid-14721-cid-198.html)
- UKTN: [OQC, JPMorganChase and AMD to develop quantum AI platform in London](https://www.uktech.news/quantum/oqc-jpmorganchase-and-amd-to-develop-quantum-ai-platform-in-london-20260604)

**OQC Background**
- Prior certified randomness expansion anchor: Liu, M. et al. (JPMorganChase / Quantinuum). "Certified Randomness Using a Trapped-Ion Quantum Computer." *Nature*, March 26, 2025.

---

*London, UK · Announced June 3, 2026 · Strategic Research Collaboration*  
*OQC · JPMorganChase · AMD*
