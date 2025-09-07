---
aliases:
  - Centralised Unit
  - CU
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Central Unit ([[Def - (CU) Centralised Unit|CU]])** is the top-tier node in the disaggregated [[Def - (RAN) Radio Access Network|RAN]] architecture, typically responsible for non-real-time and higher-layer functions such as mobility management, session control, and protocol termination for signalling and data.

It is often split into two functional components: CU-CP (Control Plane) and CU-UP (User Plane), enabling Control and User Plane Separation ([[Def - (CUPS) Control and User Plane Separation|CUPS]]). This separation allows for independent scaling of control and data handling based on network demand.

Key functions of the CU:
- **[[Def - (RRC) Radio Resource Control|RRC]] (Radio Resource Control)**: Manages [[Def - (UE) User Equipment|UE]] context and signalling.
- **[[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] (Packet Data Convergence Protocol)**: Handles header compression and encryption.
- **Mobility anchoring**: Maintains session continuity during handovers between cells or [[Def - (DU) Distributed Unit|DU]]s.

The [[Def - (CU) Centralised Unit|CU]] connects to the [[Def - (DU) Distributed Unit|DU]] over the [[Def - Midhaul|midhaul]] and to the core network over the backhaul. It is typically located at centralised locations such as regional data centres, facilitating multi-site coordination, cost-efficiency, and simpler management in cloud-native environments.
