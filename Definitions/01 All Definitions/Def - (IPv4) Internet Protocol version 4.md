---
aliases:
  - Internet Protocol version 4
  - IPv4
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Internet Protocol version 4 ([[Def - (IPv4) Internet Protocol version 4|IPv4]])** is the fourth iteration of the [[Def - (IP) Internet Protocol|IP]] protocol and the first to be widely deployed across the internet. It uses **32-bit addressing**, allowing for approximately **4.3 billion unique [[Def - (IP) Internet Protocol|IP]] addresses** (2³²).

An [[Def - (IPv4) Internet Protocol version 4|IPv4]] address is written in **dotted decimal notation**, such as `192.168.0.1`, and consists of:
- **Network portion**: Identifies the network.
- **Host portion**: Identifies a specific device on that network.

Key features of IPv4:
- **Packet fragmentation and reassembly**: Handled at routers and endpoints to support different MTUs.
- **Header fields**: Includes TTL, source/destination addresses, protocol identifier (e.g. [[Def - (TCP) Transmission Control Protocol|TCP]]/[[Def - (UDP) User Datagram Protocol|UDP]]), and checksum.
- **Classful and [[Def - (CIDR) Classless Inter-Domain Routing|CIDR]] addressing**: Originally organised into Classes A/B/C, now replaced by Classless Inter-Domain Routing ([[Def - (CIDR) Classless Inter-Domain Routing|CIDR]]) for flexible allocation.

Limitations of IPv4:
- **Address exhaustion**: Prompted the need for [[Def - (NAT) Network Address Translation|NAT]] (Network Address Translation) and eventually [[Def - (IPv6) Internet Protocol version 6|IPv6]].
- **Limited built-in security**: [[Def - (IPsec) Internet Protocol Security|IPSec]] is optional and not widely adopted in [[Def - (IPv4) Internet Protocol version 4|IPv4]] deployments.

Despite its limitations, [[Def - (IPv4) Internet Protocol version 4|IPv4]] remains in extensive use, especially in private networks, though [[Def - (IPv6) Internet Protocol version 6|IPv6]] is gradually replacing it in modern infrastructure.
