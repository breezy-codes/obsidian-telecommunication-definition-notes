---
aliases:
  - MAC
  - Medium Access Control
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer2
---

**Medium Access Control ([[Def - (MAC) Medium Access Control|MAC]])** is a sublayer of the data link layer in mobile networks (part of Layer 2), responsible for controlling how data is transmitted over the shared radio channel. It operates between the [[Def - Physical (PHY) Layer|PHY]] (Physical) layer and the [[Def - (RLC) Radio Link Control|RLC]] (Radio Link Control) layer.

Key responsibilities of the [[Def - (MAC) Medium Access Control|MAC]] layer include:
- **Scheduling and multiplexing**: Allocates resources to [[Def - (UE) User Equipment|UE]]s based on instructions from the scheduler (usually in the [[Def - (DU) Distributed Unit|DU]]).
- **Hybrid Automatic Repeat Request ([[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]])**: Manages retransmissions to recover from errors without excessive delay.
- **Priority handling**: Ensures Quality of Service (QoS) by differentiating traffic types.
- **Random access control**: Handles initial access procedures and contention resolution.

The [[Def - (MAC) Medium Access Control|MAC]] layer is time-critical and implemented in the Distributed Unit ([[Def - (DU) Distributed Unit|DU]]) of the [[Def - (RAN) Radio Access Network|RAN]]. Its role is crucial for efficient use of radio resources and maintaining high system performance.
