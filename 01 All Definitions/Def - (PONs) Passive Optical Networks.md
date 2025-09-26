---
_templateName:
aliases:
  - Passive Optical Networks
  - PON
  - PONs
tags:
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Passive Optical Networks ([[Def - (PONs) Passive Optical Networks|PON]]s)** are fibre-optic access networks that use unpowered (passive) components to deliver broadband services from a central office to multiple end users. They rely on passive splitters to divide a single optical signal among many subscribers, reducing the amount of fibre and active equipment required in the field.

A typical PON consists of three main parts:
- **Optical Line Terminal ([[Def - (OLT) Optical Line Terminal|OLT]])**: Located at the service provider’s central office, it manages data transmission and reception across the network.
- **Optical Network Units ([[Def - (ONU) Optical Network Unit|ONU]]s) or Optical Network Terminals ([[Def - (ONTs) Optical Network Terminals|ONT]]s)**: Installed at the user premises to receive and transmit data.
- **Passive optical splitters**: Split the optical signal from the [[Def - (OLT) Optical Line Terminal|OLT]] into multiple paths to serve many [[Def - (ONU) Optical Network Unit|ONU]]s, usually in ratios like 1:16 or 1:32.

[[Def - (PONs) Passive Optical Networks|PON]]s use **Time Division Multiplexing ([[Def - (TDM) Time Division Multiplexing|TDM]])** or **Wavelength Division Multiplexing ([[Def - (WDM) Wavelength Division Multiplexing|WDM]])** to share bandwidth efficiently among users. In the downstream direction (from [[Def - (OLT) Optical Line Terminal|OLT]] to [[Def - (ONU) Optical Network Unit|ONU]]s), all users receive the same data stream and each [[Def - (ONU) Optical Network Unit|ONU]] extracts its own data. In the upstream direction, [[Def - (ONU) Optical Network Unit|ONU]]s transmit in assigned time slots to avoid collisions.

Common [[Def - (PONs) Passive Optical Networks|PON]] standards include:
- **GPON (Gigabit PON)**: Offers downstream speeds up to 2.5 Gbps.
- **XG-PON and XGS-PON**: Support 10 Gbps downstream (and upstream in the case of XGS).
- **NG-PON2**: Combines [[Def - (TDM) Time Division Multiplexing|TDM]] and [[Def - (WDM) Wavelength Division Multiplexing|WDM]] for higher capacity and flexibility.

Advantages of [[Def - (PONs) Passive Optical Networks|PON]]s:
- **Cost-effective**: Fewer active components reduce installation and maintenance costs.
- **Energy efficient**: Passive infrastructure consumes less power.
- **Scalable**: Split ratios and fibre layout can be adjusted as demand grows.

[[Def - (PONs) Passive Optical Networks|PON]]s are widely used for fibre-to-the-home ([[Def - (FTTH) Fibre to the Home|FTTH]]) deployments, enabling high-speed internet, voice, and video services over a shared optical infrastructure.

