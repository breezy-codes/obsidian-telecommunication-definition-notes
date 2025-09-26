---
aliases:
  - Distributed Unit
  - DU
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Distributed Unit ([[Def - (DU) Distributed Unit|DU]])** is a logical node in the disaggregated [[Def - (RAN) Radio Access Network|RAN]] architecture responsible for time-sensitive and lower-layer baseband processing tasks. It sits between the Radio Unit ([[Def - (RU) Radio Unit|RU]]) and the Centralised Unit ([[Def - (CU) Centralised Unit|CU]]), typically connected to the [[Def - (RU) Radio Unit|RU]] via a [[Def - Fronthaul|fronthaul]] link and to the [[Def - (CU) Centralised Unit|CU]] via a [[Def - Midhaul|midhaul]] interface.

The [[Def - (DU) Distributed Unit|DU]] handles real-time functions such as [[Def - (MAC) Medium Access Control|MAC]] (Medium Access Control), parts of the [[Def - Physical (PHY) Layer|PHY]] (Physical) layer, and portions of the [[Def - (RLC) Radio Link Control|RLC]] (Radio Link Control) layer. It manages scheduling, hybrid [[Def - (ARQ) Automatic Repeat Request|ARQ]], and other delay-critical operations required to maintain efficient and reliable radio transmission.

Key responsibilities of the [[Def - (DU) Distributed Unit|DU]]:
- **Radio scheduling and resource allocation**: Ensures efficient spectrum use.
- **[[Def - (MAC) Medium Access Control|MAC]] and lower [[Def - Physical (PHY) Layer|PHY]] layer processing**: Handles re-transmissions and channel coding.
- **Time-critical operations**: Must meet strict latency requirements (<1 ms in some scenarios).

[[Def - (DU) Distributed Unit|DU]]s are typically deployed at the edge of the network, such as at base station sites or edge data centres, to meet latency needs while enabling flexibility in how [[Def - (RAN) Radio Access Network|RAN]] resources are managed and scaled.
