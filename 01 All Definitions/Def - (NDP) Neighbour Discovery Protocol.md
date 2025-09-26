---
aliases:
  - Neighbour Discovery Protocol
  - NDP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Neighbour Discovery Protocol ([[Def - (NDP) Neighbour Discovery Protocol|NDP]])** is a suite of messaging protocols used in **[[Def - (IPv6) Internet Protocol version 6|IPv6]]** networks to replace functions handled by [[Def - (ARP) Address Resolution Protocol|ARP]], [[Def - (ICMP) Internet Control Message Protocol|ICMP]] Router Discovery, and [[Def - (ICMP) Internet Control Message Protocol|ICMP]] Redirect in [[Def - (IPv4) Internet Protocol version 4|IPv4]]. It operates at Layer 3 and is essential for [[Def - (IPv6) Internet Protocol version 6|IPv6]] node-to-node interaction on the same link.

[[Def - (NDP) Neighbour Discovery Protocol|NDP]] uses **ICMPv6 messages** to perform several critical functions:
- **Router Discovery**: Hosts identify and learn about routers on the local network.
- **Prefix Discovery**: Determines the network prefix used for auto-configuration.
- **Address Resolution**: Maps [[Def - (IPv6) Internet Protocol version 6|IPv6]] addresses to [[Def - (MAC) Medium Access Control|MAC]] addresses (replacing [[Def - (ARP) Address Resolution Protocol|ARP]]).
- **Duplicate Address Detection ([[Def - (DAD) Duplicate Address Detection|DAD]])**: Ensures a host's address is unique on the local link.
- **Redirect Function**: Allows routers to inform hosts of a better next-hop.

[[Def - (NDP) Neighbour Discovery Protocol|NDP]] uses five ICMPv6 message types:
- Router Solicitation (RS)
- Router Advertisement (RA)
- Neighbour Solicitation (NS)
- Neighbour Advertisement (NA)
- Redirect

[[Def - (NDP) Neighbour Discovery Protocol|NDP]] plays a central role in **[[Def - (IPv6) Internet Protocol version 6|IPv6]] autoconfiguration**, security (with SEND extensions), and mobility, forming the basis of seamless device discovery and communication.
