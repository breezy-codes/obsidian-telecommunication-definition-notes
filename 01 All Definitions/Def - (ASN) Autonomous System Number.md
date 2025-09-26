---
aliases:
  - Autonomous System Number
  - ASN
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Autonomous System Number ([[Def - (ASN) Autonomous System Number|ASN]])** is a unique identifier assigned to each autonomous system ([[Def - (ASes) Autonomous Systems|AS]]) on the internet. It is used in [[Def - (BGP) Border Gateway Protocol|BGP]] routing to identify which [[Def - (ASes) Autonomous Systems|ASes]] a route has passed through and to enforce routing policies between networks.

There are two main types of [[Def - (ASN) Autonomous System Number|ASN]]s:
- **16-bit [[Def - (ASN) Autonomous System Number|ASN]]s**: Range from 1 to 65,535 (now mostly exhausted).
- **32-bit [[Def - (ASN) Autonomous System Number|ASN]]s**: Extended range from 65,536 to 4,294,967,295.

ASNs are allocated by regional internet registries (RIRs) such as APNIC, ARIN, RIPE NCC, etc. They are essential for:
- **[[Def - (BGP) Border Gateway Protocol|BGP]] operations**: Each [[Def - (BGP) Border Gateway Protocol|BGP]] speaker includes its [[Def - (ASN) Autonomous System Number|ASN]] in routing announcements.
- **Route policy enforcement**: Helps networks filter and prioritise routing decisions.
- **Identifying network ownership**: [[Def - (ASN) Autonomous System Number|ASN]] information can be used to trace the origin of [[Def - (IP) Internet Protocol|IP]] address blocks.

[[Def - (ASN) Autonomous System Number|ASN]]s are a core part of internet infrastructure, enabling the coordination of independent networks while maintaining global connectivity.
