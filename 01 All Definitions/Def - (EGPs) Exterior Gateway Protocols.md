---
aliases:
  - Exterior Gateway Protocols
  - EGP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Exterior Gateway Protocols ([[Def - (EGPs) Exterior Gateway Protocols|EGPs]])** are routing protocols used to exchange routing information **between** autonomous systems ([[Def - (ASes) Autonomous Systems|ASes]]) on the internet. They are designed for inter-domain routing, where each AS may have its own policies, topology, and administrative control.

The most widely used and practically the only [[Def - (EGPs) Exterior Gateway Protocols|EGP]] in use today is the **Border Gateway Protocol ([[Def - (BGP) Border Gateway Protocol|BGP]])**. Earlier versions of [[Def - (EGPs) Exterior Gateway Protocols|EGP]] (such as the original protocol named [[Def - (EGPs) Exterior Gateway Protocols|EGP]]) are now obsolete.

Key characteristics of [[Def - (EGPs) Exterior Gateway Protocols|EGP]]s:
- **Policy-based routing**: Routes are selected based on administrative policies, not just metrics like hop count or delay.
- **Scalable**: Designed to support the global internet with thousands of interconnected [[Def - (ASes) Autonomous Systems|ASes]].
- **Inter-AS focus**: Operate between different organisations, such as [[Def - (ISP) Internet Service Provider|ISP]]s, governments, or enterprises.

[[Def - (EGPs) Exterior Gateway Protocols|EGP]]s differ from **Interior Gateway Protocols ([[Def - (IGP) Interior Gateway Protocol|IGP]]s)**, which handle routing **within** a single AS. While [[Def - (IGP) Interior Gateway Protocol|IGP]]s prioritise speed and responsiveness, [[Def - (EGPs) Exterior Gateway Protocols|EGP]]s prioritise policy control and stability.
