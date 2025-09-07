---
aliases:
  - Enhanced Interior Gateway Routing Protocol
  - EIGRP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---
**Enhanced Interior Gateway Routing Protocol ([[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]])** is a Cisco-proprietary dynamic routing protocol designed for use within a single autonomous system ([[Def - (ASes) Autonomous Systems|AS]]). It combines the benefits of distance-vector and link-state protocols, using a **hybrid** approach that offers fast convergence, scalability, and efficient routing updates.

[[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]] maintains a **topology table** and uses the **Diffusing Update Algorithm ([[Def - (DUAL) Diffusing Update Algorithm|DUAL]])** to calculate loop-free paths and determine backup routes (feasible successors) for fast recovery in case of failure. Unlike traditional distance-vector protocols, [[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]] only sends updates when changes occur and only to affected routers (partial and bounded updates).

Key features of [[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]]:
- **Uses composite metrics**: Based on bandwidth, delay, reliability, and load to select best paths.
- **Supports multiple protocols**: Including IPv4, IPv6, and legacy protocols like IPX (in older versions).
- **Neighbour relationships**: Established using Hello packets and maintained with hold timers.
- **Efficient convergence**: [[Def - (DUAL) Diffusing Update Algorithm|DUAL]] ensures quick recalculation of paths without routing loops.
- **Unequal-cost load balancing**: Can distribute traffic over multiple paths with different costs (via the `variance` command).

[[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]] is widely used in enterprise networks due to its ease of configuration, efficient use of bandwidth, and fast convergence. Although originally Cisco-exclusive, it was later partially opened through an informational RFC (RFC 7868), but remains primarily associated with Cisco environments.
