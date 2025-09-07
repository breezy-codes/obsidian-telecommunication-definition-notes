---
aliases:
  - Control and User Plane Separation
  - CUPS
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Control and User Plane Separation ([[Def - (CUPS) Control and User Plane Separation|CUPS]])** is an architectural concept used in both core and [[Def - (RAN) Radio Access Network|RAN]] networks (notably in 5G and [[Def - (O-RAN) Open Radio Access Network|O-RAN]]) to decouple the control plane and user plane functions, allowing each to scale and evolve independently.

- The **control plane** handles signalling, session setup, mobility management, and resource allocation (e.g. [[Def - (RRC) Radio Resource Control|RRC]] in [[Def - (RAN) Radio Access Network|RAN]], AMF/SMF in core).
- The **user plane** is responsible for forwarding user data traffic (e.g. [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]], UPF).

In the [[Def - (RAN) Radio Access Network|RAN]] context:
- The **Central Unit ([[Def - (CU) Centralised Unit|CU]])** is split into **CU-CP (Control Plane)** and **CU-UP (User Plane)**.
- This allows operators to place and scale the user plane functions closer to users (edge) while centralising control functions for efficiency.

Benefits of [[Def - (CUPS) Control and User Plane Separation|CUPS]]:
- **Scalability**: Independently scale data and control functions based on load.
- **Flexibility**: Deploy user plane nodes closer to [[Def - (UE) User Equipment|UE]]s to reduce latency.
- **Efficiency**: Optimised resource utilisation and simplified network management.

[[Def - (CUPS) Control and User Plane Separation|CUPS]] is foundational for cloud-native and service-based mobile network architectures.
