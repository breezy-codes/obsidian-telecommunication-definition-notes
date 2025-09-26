---
aliases:
  - Internet Protocol version 6
  - IPv6
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Internet Protocol version 6 ([[Def - (IPv6) Internet Protocol version 6|IPv6]])** is the successor to [[Def - (IPv4) Internet Protocol version 4|IPv4]], designed to address its limitations—most notably the **exhaustion of address space**. [[Def - (IPv6) Internet Protocol version 6|IPv6]] uses **128-bit addresses**, allowing for approximately **340 undecillion** (3.4×10³⁸) unique [[Def - (IP) Internet Protocol|IP]] addresses.

An [[Def - (IPv6) Internet Protocol version 6|IPv6]] address is written in **colon-hexadecimal notation**, e.g. `2001:0db8:85a3::8a2e:0370:7334`, and includes features that improve scalability, routing, and efficiency.

Key features of [[Def - (IPv6) Internet Protocol version 6|IPv6]]:
- **Massive address space**: Eliminates the need for [[Def - (NAT) Network Address Translation|NAT]] by providing globally unique addresses.
- **Simplified headers**: Designed for faster processing by routers with fixed-length fields and extensions.
- **Auto-configuration**: Stateless Address Autoconfiguration ([[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]]) allows devices to configure themselves without [[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]].
- **Built-in [[Def - (IPsec) Internet Protocol Security|IPSec]]**: Security is a native part of the protocol suite.
- **Eliminates broadcast**: Uses multicast and anycast instead, improving efficiency.

IPv6 also includes new packet handling mechanisms:
- **Neighbour Discovery Protocol ([[Def - (NDP) Neighbour Discovery Protocol|NDP]])**: Replaces [[Def - (ARP) Address Resolution Protocol|ARP]] for address resolution and router discovery.
- **Flow labels**: Allows routers to identify traffic flows for QoS handling.

Although adoption has been gradual, [[Def - (IPv6) Internet Protocol version 6|IPv6]] is critical for the future of the internet, enabling billions of new devices to be connected securely and efficiently.
