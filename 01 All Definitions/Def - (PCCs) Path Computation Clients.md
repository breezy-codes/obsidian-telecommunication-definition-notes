---
aliases:
  - Path Computation Clients
  - PCC
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/OSI-model/layer3
---

**Path Computation Clients ([[Def - (PCCs) Path Computation Clients|PCC]]s)** are network elements, such as routers, switches, or controllers, that request optimal paths through the network from a **Path Computation Element ([[Def - (PCEs) Path Computation Elements|PCE]])**. [[Def - (PCCs) Path Computation Clients|PCC]]s rely on the [[Def - (PCEs) Path Computation Elements|PCE]] to compute routes that meet specific constraints like bandwidth, latency, or policy requirements.

A [[Def - (PCCs) Path Computation Clients|PCC]] sends a path request using the **Path Computation Element Protocol ([[Def - (PCEP) Path Computation Element Protocol|PCEP]])** and receives a response with a computed path that it can install into the network. [[Def - (PCCs) Path Computation Clients|PCC]]s may also report current path usage and status to stateful [[Def - (PCEs) Path Computation Elements|PCE]]s, enabling more intelligent decision-making.

Examples of [[Def - (PCCs) Path Computation Clients|PCC]]s:
- Edge routers in [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] networks
- [[Def - (SDN) Software Defined Networking|SDN]] controllers
- Network management systems

[[Def - (PCCs) Path Computation Clients|PCC]]s are a critical part of traffic engineering, enabling dynamic and policy-driven routing in large-scale [[Def - (IP) Internet Protocol|IP]], [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]], and optical networks.
