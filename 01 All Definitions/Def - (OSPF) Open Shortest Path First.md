---
aliases:
  - Open Shortest Path First
  - OSPF
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Open Shortest Path First ([[Def - (OSPF) Open Shortest Path First|OSPF]])** is a widely used interior gateway protocol ([[Def - (IGP) Interior Gateway Protocol|IGP]]) for routing packets within a single autonomous system. It uses a **link-state** approach, where routers exchange information about their local links and construct a complete map of the network.

[[Def - (OSPF) Open Shortest Path First|OSPF]] routers calculate the shortest path to each destination using Dijkstra’s algorithm and build routing tables based on this topology.

Key characteristics of [[Def - (OSPF) Open Shortest Path First|OSPF]]:
- **Fast convergence**: Quickly adapts to changes in network topology.
- **Hierarchical design**: Supports areas to scale large networks and reduce routing overhead.
- **Cost-based metrics**: Chooses paths based on configurable link costs, not just hop count.
- **Support for [[Def - (VLSM) Variable-Length Subnet Masking|VLSM]]**: Handles variable-length subnet masking and [[Def - (CIDR) Classless Inter-Domain Routing|CIDR]] efficiently.

[[Def - (OSPF) Open Shortest Path First|OSPF]] is typically used in enterprise networks and large service provider infrastructures where fast, efficient, and loop-free routing is required within a controlled environment.
