---
aliases:
  - Autonomous Systems
  - ASes
  - AS
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

Autonomous Systems ([[Def - (ASes) Autonomous Systems|ASes]]) are independently managed networks or collections of [[Def - (IP) Internet Protocol|IP]] prefixes under a single administrative domain, such as an [[Def - (ISP) Internet Service Provider|ISP]], university, enterprise, or cloud provider. Each [[Def - (ASes) Autonomous Systems|AS]] has its own routing policies and operates as a unit within the global internet.

Each [[Def - (ASes) Autonomous Systems|AS]] is assigned a unique **Autonomous System Number ([[Def - (ASN) Autonomous System Number|ASN]])** by a regional internet registry (e.g. APNIC, ARIN). [[Def - (ASes) Autonomous Systems|ASes]] use **interior gateway protocols ([[Def - (IGP) Interior Gateway Protocol|IGP]]s)** like [[Def - (OSPF) Open Shortest Path First|OSPF]] or [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]] for internal routing, and **Border Gateway Protocol ([[Def - (BGP) Border Gateway Protocol|BGP]])** for exchanging routing information with other [[Def - (ASes) Autonomous Systems|ASes]].

There are different types of [[Def - (ASes) Autonomous Systems|ASes]]:
- **Stub AS**: Connects to only one other AS.
- **Transit AS**: Forwards traffic between other [[Def - (ASes) Autonomous Systems|ASes]].
- **Multihomed AS**: Connects to two or more [[Def - (ASes) Autonomous Systems|ASes]] but does not transit traffic.

[[Def - (ASes) Autonomous Systems|ASes]] form the building blocks of internet routing, with [[Def - (BGP) Border Gateway Protocol|BGP]] determining how data travels between them.
