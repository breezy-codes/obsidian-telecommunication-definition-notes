---
aliases:
  - Baseband Unit
  - BBU
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Baseband Unit ([[Def - (BBU) Baseband Unit|BBU]])** is a key component of a cellular base station responsible for all digital signal processing tasks, including encoding, decoding, modulation, demodulation, scheduling, and radio resource management. It sits between the core network and the radio units that handle the physical transmission over the air.

In traditional [[Def - (RAN) Radio Access Network|RAN]] architectures, the [[Def - (BBU) Baseband Unit|BBU]] is co-located with the radio unit ([[Def - (RU) Radio Unit|RU]]) at the cell site. In modern architectures like **[[Def - (C-RAN) Centralised Radio Access Network|C-RAN]]** and **[[Def - (O-RAN) Open Radio Access Network|O-RAN]]**, [[Def - (BBU) Baseband Unit|BBU]]s are centralised and virtualised, allowing them to serve multiple radio sites from a shared location.

Functions of the [[Def - (BBU) Baseband Unit|BBU]]:
- **Physical layer processing**
- **[[Def - (MAC) Medium Access Control|MAC]] and [[Def - (RLC) Radio Link Control|RLC]] layer functions**
- **Mobility management and handover control**
- **Interface with the core network (via S1 or NG interfaces)**

By separating the [[Def - (BBU) Baseband Unit|BBU]] from the [[Def - (RU) Radio Unit|RU]], operators gain flexibility, reduce costs, and prepare the network for software-defined and cloud-based deployments.
