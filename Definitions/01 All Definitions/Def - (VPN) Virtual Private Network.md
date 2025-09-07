---
aliases:
  - VPN
  - Virtual Private Network
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/OSI-model/layer3
---

**Virtual Private Network ([[Def - (VPN) Virtual Private Network|VPN]])** is a technology that creates a **secure, encrypted connection** over a public or untrusted network, such as the internet, enabling private communication between users or sites. [[Def - (VPN) Virtual Private Network|VPN]]s are commonly used to extend private networks across geographic boundaries, allowing remote users or offices to access resources securely.

There are several types of [[Def - (VPN) Virtual Private Network|VPN]]s:
- **Remote access VPN**: Connects individual users to a central network via software clients.
- **Site-to-site VPN**: Connects entire networks (e.g. between branches or data centres).
- **MPLS-based VPN**: Operates at Layer 3 or Layer 2 using [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] and Label Switched Paths ([[Def - (LSP) Label Switched Path|LSP]]s) for high-performance private networking across a shared service provider infrastructure.

Core features of [[Def - (VPN) Virtual Private Network|VPN]]s:
- **Encryption and tunnelling**: Protocols like IPsec, [[Def - (SSL) Secure Sockets Layer|SSL]]/[[Def - (TLS) Transport Layer Security|TLS]], or WireGuard encapsulate and secure data.
- **Authentication**: Ensures only authorised users or sites can access the [[Def - (VPN) Virtual Private Network|VPN]].
- **Data integrity and confidentiality**: Prevents tampering or eavesdropping in transit.
- **Traffic isolation**: In [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] [[Def - (VPN) Virtual Private Network|VPN]]s, customer traffic is separated using labels rather than [[Def - (IP) Internet Protocol|IP]] filtering.

[[Def - (VPN) Virtual Private Network|VPN]]s are widely used in enterprise, government, and personal contexts to protect sensitive data, support remote work, and interconnect distributed resources securely over shared or public infrastructure.
