---
aliases:
  - Stateless Address Autoconfiguration
  - SLAAC
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
---

**Stateless Address Autoconfiguration ([[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]])** is a mechanism in **[[Def - (IPv6) Internet Protocol version 6|IPv6]]** that allows hosts to **automatically configure their own [[Def - (IP) Internet Protocol|IP]] addresses** without relying on a [[Def - (DHCP) Dynamic Host Configuration Protocol|DHCP]] server. It simplifies the process of joining a network, particularly for end-user devices and IoT systems.

[[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]] works by combining:
- A **network prefix** advertised by a router via **Router Advertisement (RA)** messages.
- A host-generated **interface identifier** (typically based on its [[Def - (MAC) Medium Access Control|MAC]] address or a randomly generated value).

The resulting [[Def - (IPv6) Internet Protocol version 6|IPv6]] address is globally unique and routable, such as:
`2001:db8:abcd:1234::1`

Key benefits of [[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]]:
- **No central management required**: Devices can join networks with minimal configuration.
- **Works with [[Def - (NDP) Neighbour Discovery Protocol|NDP]]**: Uses Router Advertisements from [[Def - (NDP) Neighbour Discovery Protocol|NDP]] to learn prefixes, MTU, and default gateway.
- **Supports privacy extensions**: Temporary, randomised addresses can be generated to prevent tracking.

[[Def - (SLAAC) Stateless Address Autoconfiguration|SLAAC]] can be used on its own or alongside **stateless DHCPv6** for supplying additional configuration (like [[Def - (DNS) Domain Name System|DNS]] servers). It is ideal for plug-and-play connectivity in modern [[Def - (IPv6) Internet Protocol version 6|IPv6]] networks.
