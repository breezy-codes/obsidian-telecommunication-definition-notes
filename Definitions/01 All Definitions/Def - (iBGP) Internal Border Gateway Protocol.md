---
aliases:
  - Internal Border Gateway Protocol
  - iBGP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---
**Internal Border Gateway Protocol ([[Def - (iBGP) Internal Border Gateway Protocol|iBGP]])** is the form of [[Def - (BGP) Border Gateway Protocol|BGP]] used to exchange routing information **within a single autonomous system ([[Def - (ASes) Autonomous Systems|AS]])**. Unlike [[Def - (eBGP) External Border Gateway Protocol|eBGP]], which connects different [[Def - (ASes) Autonomous Systems|ASes]], [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] connects routers that belong to the same [[Def - (ASes) Autonomous Systems|AS]], typically over existing [[Def - (IGP) Interior Gateway Protocol|IGP]] infrastructure.

[[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] is used to **distribute external routes** (learned via [[Def - (eBGP) External Border Gateway Protocol|eBGP]]) internally so that all routers in the [[Def - (ASes) Autonomous Systems|AS]] are aware of the external prefixes. It does not participate in path selection based on shortest path metrics like traditional [[Def - (IGP) Interior Gateway Protocol|IGP]]s; instead, it preserves routing attributes received from [[Def - (eBGP) External Border Gateway Protocol|eBGP]] and relies on local policies.

Key aspects of [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]]:
- **Full mesh or route reflectors**: Routers must either form a full mesh of sessions or use route reflectors to scale.
- **Next-hop behaviour**: By default, [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] does not modify the next-hop attribute, requiring [[Def - (IGP) Interior Gateway Protocol|IGP]] reachability.
- **Loop prevention**: [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] does not advertise routes learned from another [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] peer (split horizon rule).
- **Control plane separation**: [[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] routes are kept separate from [[Def - (IGP) Interior Gateway Protocol|IGP]] routes, allowing more control over external traffic flows.

[[Def - (iBGP) Internal Border Gateway Protocol|iBGP]] plays a critical role in large-scale networks, enabling scalable, policy-driven distribution of routes without exposing internal topology details to external peers.
