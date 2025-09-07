---
aliases:
  - Diffusing Update Algorithm
  - DUAL
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Diffusing Update Algorithm ([[Def - (DUAL) Diffusing Update Algorithm|DUAL]])** is the core algorithm used by **[[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]] (Enhanced Interior Gateway Routing Protocol)** to calculate and maintain loop-free routes and ensure fast, deterministic convergence in [[Def - (IP) Internet Protocol|IP]] networks. Developed by Cisco, [[Def - (DUAL) Diffusing Update Algorithm|DUAL]] provides a mathematically guaranteed way to compute the best path and backup paths to each destination while preventing routing loops.

[[Def - (DUAL) Diffusing Update Algorithm|DUAL]] operates by maintaining a **topology table**, which stores all learned routes (including those not currently in use), and identifying the **successor** (primary next-hop) and **feasible successor** (backup route) for each destination.

Key concepts in [[Def - (DUAL) Diffusing Update Algorithm|DUAL]]:
- **Successor**: The best next-hop router to a destination, determined by the lowest metric.
- **Feasible Successor**: A backup route that satisfies the **Feasibility Condition**—its reported distance (from the neighbour to the destination) must be less than the local router’s feasible distance (FD) to that destination. This ensures the path is loop-free.
- **Feasibility Condition**: A mathematical test that ensures alternate paths don’t create loops.
- **Active and Passive States**: A route is **passive** when it is stable and has a known path. If the successor fails and no feasible successor is available, the route becomes **active**, triggering [[Def - (DUAL) Diffusing Update Algorithm|DUAL]] to send queries to neighbouring routers to recalculate the path.

Benefits of [[Def - (DUAL) Diffusing Update Algorithm|DUAL]]:
- **Fast convergence**: Backup routes are precomputed, allowing rapid failover.
- **Loop prevention**: The feasibility condition guarantees loop-free alternatives.
- **Selective updates**: Only routers affected by a change are notified, reducing overhead.

[[Def - (DUAL) Diffusing Update Algorithm|DUAL]] is a key innovation that sets [[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]] apart from traditional distance-vector protocols, offering [[Def - (IGP) Interior Gateway Protocol|IGP]]-level simplicity with near link-state performance and safety.
