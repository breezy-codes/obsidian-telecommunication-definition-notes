---
aliases:
  - Border Gateway Protocol
  - BGP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Border Gateway Protocol ([[Def - (BGP) Border Gateway Protocol|BGP]])** is the primary routing protocol used to exchange routing information between autonomous systems ([[Def - (ASes) Autonomous Systems|ASes]]) on the internet. It determines how packets are routed across large-scale networks, making it essential for the operation of the global internet.

[[Def - (BGP) Border Gateway Protocol|BGP]] is a **path vector protocol** that uses attributes like [[Def - (ASes) Autonomous Systems|AS]] path, prefix length, and policies to choose the best route for each destination. Unlike interior routing protocols, which focus on speed and responsiveness, [[Def - (BGP) Border Gateway Protocol|BGP]] prioritises policy control and routing stability.

Key features of [[Def - (BGP) Border Gateway Protocol|BGP]]:
- **Inter-domain routing**: Connects different organisations’ networks (e.g. [[Def - (ISP) Internet Service Provider|ISP]]s, data centres).
- **Policy-based routing**: Allows fine-grained control over route selection and advertisement.
- **Loop prevention**: Tracks the [[Def - (ASes) Autonomous Systems|AS]] path to avoid routing loops.

[[Def - (BGP) Border Gateway Protocol|BGP]] comes in two forms:
- **[[Def - (eBGP) External Border Gateway Protocol|eBGP]]**: Between different autonomous systems.
- **[[Def - (iBGP) Internal Border Gateway Protocol|iBGP]]**: Within the same autonomous system.

[[Def - (BGP) Border Gateway Protocol|BGP]] is vital for internet scalability and resilience, enabling complex routing decisions across thousands of networks.
