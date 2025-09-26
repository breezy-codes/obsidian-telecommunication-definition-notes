---
aliases:
  - Common Public Radio Interface
  - CPRI
sticker:
tags:
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Common Public Radio Interface ([[Def - (CPRI) Common Public Radio Interface|CPRI]])** is a standardised interface that defines how baseband signals are exchanged between the Baseband Unit ([[Def - (BBU) Baseband Unit|BBU]]) and the Remote Radio Head ([[Def - (RRH) Remote Radio Head|RRH]]) in traditional mobile [[Def - (RAN) Radio Access Network|RAN]] architectures. It was developed by a consortium of telecommunications companies to support efficient, high-speed digital transport over fibre between centralised and distributed radio components.

[[Def - (CPRI) Common Public Radio Interface|CPRI]] transmits digitised radio signals (I/Q data) over dedicated fibre using a serial communication protocol. This enables centralisation of baseband processing, supporting [[Def - (C-RAN) Centralised Radio Access Network|C-RAN]] (Centralised [[Def - (RAN) Radio Access Network|RAN]]) deployments.

Key characteristics of [[Def - (CPRI) Common Public Radio Interface|CPRI]]:
- **High bandwidth requirements**: Transmits raw data with minimal compression, requiring large fronthaul capacity.
- **Low latency**: Designed for real-time radio operations with tight delay budgets.
- **Proprietary and rigid**: Each link is typically vendor-specific and lacks packet-based flexibility.

While widely deployed in 4G networks, [[Def - (CPRI) Common Public Radio Interface|CPRI]]'s limitations in scalability and cost-efficiency led to the development of **[[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]]**, which supports packet-based transport and better suits the needs of 5G and [[Def - (O-RAN) Open Radio Access Network|O-RAN]].
