---
aliases:
  - External Border Gateway Protocol
  - eBGP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**External Border Gateway Protocol ([[Def - (eBGP) External Border Gateway Protocol|eBGP]])** is a variant of the Border Gateway Protocol ([[Def - (BGP) Border Gateway Protocol|BGP]]) used to exchange routing information between different **autonomous systems ([[Def - (ASes) Autonomous Systems|ASes]])** on the internet. It is the backbone of inter-domain routing, enabling Internet Service Providers ([[Def - (ISP) Internet Service Provider|ISP]]s), data centres, and large enterprises to establish routing policies and connectivity with external networks.

[[Def - (eBGP) External Border Gateway Protocol|eBGP]] sessions are established between routers in different [[Def - (ASes) Autonomous Systems|ASes]], typically across provider or peering links. Unlike traditional interior routing protocols (e.g. [[Def - (OSPF) Open Shortest Path First|OSPF]] or [[Def - (EIGRP) Enhanced Interior Gateway Routing Protocol|EIGRP]]), [[Def - (BGP) Border Gateway Protocol|BGP]] is **path-vector-based**, using [[Def - (ASes) Autonomous Systems|AS]] paths to make routing decisions and avoid loops.

Key characteristics of eBGP:
- **[[Def - (ASes) Autonomous Systems|AS]] path awareness**: Helps prevent routing loops and enables policy-based routing.
- **Default Time-To-Live (TTL)**: eBGP peers use a TTL of 1, indicating they are directly connected unless adjusted.
- **Policy control**: Uses routing attributes (e.g. LOCAL_PREF, MED, communities) for granular traffic engineering.
- **Route filtering**: Allows strict control over which prefixes are advertised or accepted.

[[Def - (eBGP) External Border Gateway Protocol|eBGP]] is essential for internet-scale routing, interconnecting thousands of [[Def - (ASes) Autonomous Systems|ASes]] and determining how data moves across the global network. It is also used in 5G transport networks to connect slices or domains under different administrative control.
