---
aliases:
  - Classless Inter-Domain Routing
  - CIDR
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Classless Inter-Domain Routing ([[Def - (CIDR) Classless Inter-Domain Routing|CIDR]])** is an [[Def - (IP) Internet Protocol|IP]] addressing scheme introduced to **replace the class-based system** (A, B, C) and improve the efficiency of [[Def - (IP) Internet Protocol|IP]] address allocation and routing. Defined in RFC 1519, [[Def - (CIDR) Classless Inter-Domain Routing|CIDR]] allows [[Def - (IP) Internet Protocol|IP]] addresses and routing prefixes to be assigned more flexibly using **variable-length subnet masking ([[Def - (VLSM) Variable-Length Subnet Masking|VLSM]])**.

[[Def - (CIDR) Classless Inter-Domain Routing|CIDR]] notation represents an [[Def - (IP) Internet Protocol|IP]] address followed by a forward slash and the subnet prefix length (e.g., `192.168.1.0/24`). The prefix length indicates how many bits define the network portion of the address.

Benefits of [[Def - (CIDR) Classless Inter-Domain Routing|CIDR]]:
- **Reduces address wastage**: Enables allocation of address blocks sized to actual need.
- **Supports route aggregation (supernetting)**: Combines multiple contiguous prefixes into a single routing entry to reduce routing table size.
- **Facilitates hierarchical addressing**: Improves efficiency in [[Def - (IP) Internet Protocol|IP]] allocation and global routing.

[[Def - (CIDR) Classless Inter-Domain Routing|CIDR]] is fundamental to the modern internet’s routing infrastructure and continues to be used in both **[[Def - (IPv4) Internet Protocol version 4|IPv4]]** and **[[Def - (IPv6) Internet Protocol version 6|IPv6]]** to manage and summarise [[Def - (IP) Internet Protocol|IP]] space.
