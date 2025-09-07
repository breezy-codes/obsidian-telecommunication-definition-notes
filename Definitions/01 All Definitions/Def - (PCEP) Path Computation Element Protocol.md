---
aliases:
  - Path Computation Element Protocol
  - PCEP
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/OSI-model/layer3
---

**Path Computation Element Protocol ([[Def - (PCEP) Path Computation Element Protocol|PCEP]])** is a communication protocol used between **Path Computation Clients ([[Def - (PCCs) Path Computation Clients|PCC]]s)** and **Path Computation Elements ([[Def - (PCEs) Path Computation Elements|PCE]]s)** to compute network paths, typically in traffic-engineered networks like [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] or optical transport systems.

A **[[Def - (PCEs) Path Computation Elements|PCE]]** is a network function that determines optimal paths based on constraints such as bandwidth, latency, topology, and policy. The **[[Def - (PCCs) Path Computation Clients|PCC]]**, such as an ingress router or [[Def - (SDN) Software Defined Networking|SDN]] controller, requests a path and receives a computed route in response.

Key features of [[Def - (PCEP) Path Computation Element Protocol|PCEP]]:
- **Supports constrained path computation**: Handles complex policies, bandwidth guarantees, and disjoint paths.
- **Enables centralised control**: Works well with [[Def - (SDN) Software Defined Networking|SDN]] architectures where [[Def - (PCEs) Path Computation Elements|PCE]]s assist with global path optimisation.
- **Extensible**: Supports stateful [[Def - (PCEs) Path Computation Elements|PCE]]s that maintain awareness of current network usage and can initiate path updates.

[[Def - (PCEP) Path Computation Element Protocol|PCEP]] is often used in **[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]]-TE** and **[[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]]** environments and is defined by [[Def - (IETF) Internet Engineering Task Force|IETF]] standards to improve network resource management, scalability, and efficiency in large transport networks.
