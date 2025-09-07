---
aliases:
  - Radio Resource Control
  - RRC
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer3
---

**Radio Resource Control ([[Def - (RRC) Radio Resource Control|RRC]])** is a protocol in mobile networks (including 3G, 4G, and 5G) that manages the control plane signalling between the **user equipment ([[Def - (UE) User Equipment|UE]])** and the **radio access network ([[Def - (RAN) Radio Access Network|RAN]])**. It plays a central role in configuring, maintaining, and releasing radio connections.

[[Def - (RRC) Radio Resource Control|RRC]] is responsible for tasks such as:
- **Connection setup and release**
- **Handover control**
- **Radio bearer configuration**
- **Paging and mobility procedures**
- **Measurement reporting**

In 5G and [[Def - (LTE) Long Term Evolution|LTE]], [[Def - (RRC) Radio Resource Control|RRC]] operates at the base station ([[Def - (gNB) Next Generation NodeB|gNB]] or [[Def - (eNodeB) Evolved NodeB|eNodeB]]) and interacts with the core network to deliver QoS and mobility services.

[[Def - (RRC) Radio Resource Control|RRC]] has several defined states, such as:
- **RRC_IDLE**: [[Def - (UE) User Equipment|UE]] is inactive but can receive paging.
- **RRC_CONNECTED**: [[Def - (UE) User Equipment|UE]] has an active signalling and data connection.
- **RRC_INACTIVE** (5G only): Intermediate state to reduce latency and power consumption.

Efficient [[Def - (RRC) Radio Resource Control|RRC]] management is crucial for balancing performance, battery life, and responsiveness in mobile devices.
