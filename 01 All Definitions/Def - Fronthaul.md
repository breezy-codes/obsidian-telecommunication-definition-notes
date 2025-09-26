---
aliases:
  - fronthaul
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**[[Def - Fronthaul|Fronthaul]]** refers to the segment of a mobile network that connects the **Radio Unit ([[Def - (RU) Radio Unit|RU]])** to the **Distributed Unit ([[Def - (DU) Distributed Unit|DU]])** in a disaggregated [[Def - (RAN) Radio Access Network|RAN]] architecture. It is responsible for transporting digitised radio signals and control information between the [[Def - (RF) Radio Frequency|RF]] front-end and the baseband processing components.

In legacy architectures, fronthaul referred to the connection between the Remote Radio Head ([[Def - (RRH) Remote Radio Head|RRH]]) and the Baseband Unit ([[Def - (BBU) Baseband Unit|BBU]]), typically over **[[Def - (CPRI) Common Public Radio Interface|CPRI]]** links. In modern 5G and [[Def - (O-RAN) Open Radio Access Network|O-RAN]] networks, **[[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]]** and packet-based transport (e.g. Ethernet) are commonly used to improve scalability and efficiency.

Key characteristics of fronthaul:
- **High bandwidth**: Carries raw or semi-processed I/Q data, requiring significant throughput.
- **Low latency and jitter**: Must meet strict timing requirements for real-time radio operations.
- **Deterministic performance**: Especially critical for synchronisation and [[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]] operations.

[[Def - Fronthaul|Fronthaul]] is typically deployed over fibre, though wireless fronthaul options also exist. Its performance directly impacts the efficiency and reliability of radio communication in the [[Def - (RAN) Radio Access Network|RAN]].
