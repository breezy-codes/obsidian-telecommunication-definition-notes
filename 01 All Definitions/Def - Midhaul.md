---
aliases:
  - midhaul
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**[[Def - Midhaul|Midhaul]]** is the network segment that connects the **Distributed Unit ([[Def - (DU) Distributed Unit|DU]])** to the **Central Unit ([[Def - (CU) Centralised Unit|CU]])** in a disaggregated and virtualised [[Def - (RAN) Radio Access Network|RAN]] architecture such as 5G or [[Def - (O-RAN) Open Radio Access Network|O-RAN]]. It lies between the [[Def - Fronthaul|fronthaul]] and [[Def - Backhaul|backhaul]] and is part of the evolved split model used to modularise [[Def - (RAN) Radio Access Network|RAN]] functions.

The [[Def - Midhaul|midhaul]] transports data and control plane traffic from the [[Def - (DU) Distributed Unit|DU]], which handles time-sensitive lower-layer radio tasks, to the [[Def - (CU) Centralised Unit|CU]], which manages higher-layer functions like [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] and [[Def - (RRC) Radio Resource Control|RRC]].

Key characteristics of midhaul:
- **Moderate latency requirements**: More relaxed than fronthaul but still requires low enough delay to support session management and mobility.
- **Supports flexible deployment**: Allows [[Def - (DU) Distributed Unit|DU]]s to be placed closer to the edge while centralising [[Def - (CU) Centralised Unit|CU]]s in data centres.
- **Transport protocols**: Uses [[Def - (IP) Internet Protocol|IP]]-based technologies and standard Ethernet infrastructure.

[[Def - Midhaul|Midhaul]] is critical for enabling cloud-native [[Def - (RAN) Radio Access Network|RAN]] ([[Def - (C-RAN) Centralised Radio Access Network|C-RAN]]) and multi-site coordination, especially in scalable and vendor-neutral 5G deployments.
