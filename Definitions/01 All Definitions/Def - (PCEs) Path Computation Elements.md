---
aliases:
  - Path Computation Elements
  - PCE
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer3
---

**Path Computation Elements ([[Def - (PCEs) Path Computation Elements|PCE]]s)** are network components or functions that calculate efficient and constraint-based paths through a network. They are typically used in environments where advanced traffic engineering is needed, such as **[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]]-TE**, **[[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]]**, or **optical transport networks**.

[[Def - (PCEs) Path Computation Elements|PCE]]s operate independently of the forwarding devices and have a global view of the network topology. They compute paths based on real-time or near-real-time data, including available resources, performance metrics, and policy constraints.

Key characteristics:
- **Centralised intelligence**: Can optimise routing across the whole network.
- **Supports [[Def - (PCEP) Path Computation Element Protocol|PCEP]]**: Communicates with clients ([[Def - (PCCs) Path Computation Clients|PCC]]s) to provide or update path computations.
- **Stateful or stateless**: A **stateful [[Def - (PCEs) Path Computation Elements|PCE]]** maintains awareness of existing paths and resources; a **stateless [[Def - (PCEs) Path Computation Elements|PCE]]** computes paths on request without memory of current usage.

[[Def - (PCEs) Path Computation Elements|PCE]]s are used in both traditional networks and **[[Def - (SDN) Software Defined Networking|SDN]]** architectures to improve resource utilisation and enable dynamic, on-demand services.
