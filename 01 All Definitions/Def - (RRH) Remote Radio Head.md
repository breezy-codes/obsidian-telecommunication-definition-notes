---
aliases:
  - Remote Radio Head
  - RRH
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Remote Radio Head ([[Def - (RRH) Remote Radio Head|RRH]])**, also known as **Remote Radio Unit (RRU)**, is a critical component of a cellular base station responsible for **transmitting and receiving radio frequency ([[Def - (RF) Radio Frequency|RF]]) signals** to and from user equipment ([[Def - (UE) User Equipment|UE]]). It performs the **analog front-end functions**, including **[[Def - (RF) Radio Frequency|RF]] amplification**, **filtering**, **frequency conversion**, and **analog-to-digital (A/D)** and **digital-to-analog (D/A)** conversion.

The [[Def - (RRH) Remote Radio Head|RRH]] is typically located at or near the **antenna**, often mounted on towers or rooftops, and is connected to the **Baseband Unit ([[Def - (BBU) Baseband Unit|BBU]])** via a **[[Def - Fronthaul|fronthaul]] link**, commonly using **[[Def - (CPRI) Common Public Radio Interface|CPRI]]**, **[[Def -  (eCPRI) Enhanced Common Public Radio Interface|eCPRI]]**, or **Ethernet**.

Functions of the RRH:
- **Transmit/receive radio signals** over the air interface
- **Power amplification** of uplink and downlink signals
- **Signal filtering and frequency conversion**
- **Analog/digital signal conversion**
- **Low-noise amplification (LNA)** to improve receiver sensitivity

Key benefits of using [[Def - (RRH) Remote Radio Head|RRH]]s:
- **Reduced feeder loss**: Mounting [[Def - (RRH) Remote Radio Head|RRH]]s close to the antennas minimises signal degradation compared to traditional long coaxial runs.
- **Simplified tower design**: Only fibre and power cables need to run between the tower and base station equipment.
- **Flexible deployment**: Supports distributed, centralised, or cloud [[Def - (RAN) Radio Access Network|RAN]] architectures.
- **Improved coverage and capacity**: [[Def - (RRH) Remote Radio Head|RRH]]s can be deployed more densely or alongside **Massive MIMO ([[Def - (mMIMO) Massive MIMO|mMIMO]])** antennas.

[[Def - (RRH) Remote Radio Head|RRH]]s are integral to **[[Def - (C-RAN) Centralised Radio Access Network|C-RAN]]** and **[[Def - (O-RAN) Open Radio Access Network|O-RAN]]** architectures, enabling **functional splits** between distributed and centralised units ([[Def - (DU) Distributed Unit|DU]]/[[Def - (CU) Centralised Unit|CU]]), and facilitating **network virtualisation**, **scalability**, and **5G readiness**.
