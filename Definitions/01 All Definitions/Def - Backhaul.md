---
aliases:
  - Backhaul
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**[[Def - Backhaul|Backhaul]]** refers to the network segment that connects the **Radio Access Network ([[Def - (RAN) Radio Access Network|RAN]])**, specifically the **Central Unit ([[Def - (CU) Centralised Unit|CU]])** or **base station**, to the **core network**. It is responsible for carrying aggregated user traffic and signalling between the [[Def - (RAN) Radio Access Network|RAN]] and core network entities like the AMF, SMF, and UPF.

Backhaul can be implemented over various technologies:
- **Fibre-optic links**: High capacity and low latency, preferred in urban areas.
- **Microwave or [[Def - (mmWave) millimetre wave|mmWave]]**: Used in areas where fibre is impractical.
- **Satellite**: For remote or rural coverage, with higher latency.

Key characteristics of backhaul:
- **High throughput**: Aggregates traffic from many users and cells.
- **Latency-tolerant**: Compared to [[Def - Fronthaul|fronthaul]], [[Def - Backhaul|Backhaul]] has more relaxed timing constraints.
- **QoS management**: Must ensure consistent performance for multiple service types (e.g. voice, video, IoT).

[[Def - Backhaul|Backhaul]] is a vital component of mobile infrastructure, influencing overall network capacity, reliability, and user experience. In modern 5G systems, it must be scalable to support increasing bandwidth demands and flexible to integrate with [[Def - (SDN) Software Defined Networking|SDN]]/[[Def - (NFV) Network Functions Virtualisation|NFV]]-driven architectures.
