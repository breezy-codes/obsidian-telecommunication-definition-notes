---
aliases:
  - Interior Gateway Protocol
  - IGP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---
**Interior Gateway Protocol ([[Def - (IGP) Interior Gateway Protocol|IGP]])** refers to a class of routing protocols used to exchange routing information **within** a single autonomous system ([[Def - (ASes) Autonomous Systems|AS]]). These protocols are responsible for determining the best path for data to travel inside an organisation or network domain.

Common [[Def - (IGP) Interior Gateway Protocol|IGP]]s include:
- **[[Def - (OSPF) Open Shortest Path First|OSPF]] (Open Shortest Path First)**: A link-state protocol that calculates shortest paths using Dijkstra’s algorithm.
- **[[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]] (Intermediate System to Intermediate System)**: Another link-state protocol, widely used in large service provider networks.
- **[[Def - (RIP) Routing Information Protocol|RIP]] (Routing Information Protocol)**: A simpler distance-vector protocol that uses hop count as its metric.

Key characteristics of [[Def - (IGP) Interior Gateway Protocol|IGP]]s:
- **Fast convergence**: Quickly adapts to changes in network topology.
- **Autonomous system scope**: Only operates within the boundaries of a single [[Def - (ASes) Autonomous Systems|AS]].
- **Hierarchical design support**: Helps manage large networks through areas or levels.

[[Def - (IGP) Interior Gateway Protocol|IGP]]s differ from **Exterior Gateway Protocols ([[Def - (EGPs) Exterior Gateway Protocols|EGP]]s)** like [[Def - (BGP) Border Gateway Protocol|BGP]], which are used to exchange routes between autonomous systems across the broader internet.
