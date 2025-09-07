---
aliases:
  - Intermediate System to Intermediate System
  - IS-IS
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Intermediate System to Intermediate System ([[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]])** is a link-state routing protocol used to determine the best path for data within a single autonomous system. Originally developed for use with [[Def - OSI Model|OSI]] networking, it has since been adapted for [[Def - (IP) Internet Protocol|IP]] and is widely used in large service provider networks.

Like [[Def - (OSPF) Open Shortest Path First|OSPF]], [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]] routers exchange information about their links to build a full view of the network. They use Dijkstra’s algorithm to calculate the shortest paths and maintain fast, loop-free routing.

Key characteristics of [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]]:
- **Link-state protocol**: Builds a complete topology map for accurate route selection.
- **Scalable and robust**: Supports large, hierarchical networks with high stability.
- **Protocol-independent**: Works with multiple network layer protocols, including [[Def - (IPv4) Internet Protocol version 4|IPv4]] and [[Def - (IPv6) Internet Protocol version 6|IPv6]].
- **[[Def - (LSP) Label Switched Path|LSP]] flooding**: Disseminates link state information through Link State PDUs, ensuring up-to-date topology.

[[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]] is often used by large telcos and internet backbone providers due to its simplicity, flexibility, and ability to handle complex topologies.
