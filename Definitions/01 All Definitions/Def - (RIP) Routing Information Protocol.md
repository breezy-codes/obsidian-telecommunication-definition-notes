---
aliases:
  - Routing Information Protocol
  - RIP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Routing Information Protocol ([[Def - (RIP) Routing Information Protocol|RIP]])** is one of the earliest **interior gateway protocols ([[Def - (IGP) Interior Gateway Protocol|IGP]]s)** used to route data within a single autonomous system. It is a **distance-vector** protocol that determines the best route based on the number of hops (routers) to the destination.

[[Def - (RIP) Routing Information Protocol|RIP]] routers share their routing tables at regular intervals, broadcasting them to their neighbours. The route with the fewest hops is preferred, with a maximum limit of 15 hops to prevent routing loops.

Key characteristics of [[Def - (RIP) Routing Information Protocol|RIP]]:
- **Simple to configure**: Easy to deploy in small networks.
- **Hop count metric**: Limited to 15 hops, making it unsuitable for large or complex networks.
- **Slow convergence**: Takes longer to adapt to changes compared to modern protocols.
- **Periodic updates**: Sends updates every 30 seconds, which can lead to unnecessary traffic.

Although largely replaced by more advanced protocols like [[Def - (OSPF) Open Shortest Path First|OSPF]] and [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]], [[Def - (RIP) Routing Information Protocol|RIP]] is still sometimes used in small or legacy networks where simplicity is more important than performance.
