---
aliases:
  - Internet Protocol
  - IP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Internet Protocol ([[Def - (IP) Internet Protocol|IP]])** is a fundamental network layer protocol that enables devices to **identify**, **address**, and **route** data across interconnected networks (the internet or private networks). It defines how data packets are formatted, addressed, transmitted, and delivered.

[[Def - (IPv6) Internet Protocol version 6|IPv6]] is responsible for:
- **Packet addressing**: Each packet contains source and destination [[Def - (IP) Internet Protocol|IP]] addresses.
- **Fragmentation and reassembly**: Breaks large packets into smaller pieces suitable for transmission.
- **Best-effort delivery**: [[Def - (IP) Internet Protocol|IP]] does not guarantee delivery, order, or error correction (these are handled by higher-layer protocols like [[Def - (TCP) Transmission Control Protocol|TCP]]).

There are two versions in widespread use:
- **[[Def - (IPv4) Internet Protocol version 4|IPv4]]**: Uses 32-bit addresses (e.g. 192.168.1.1), supporting ~4.3 billion unique addresses.
- **[[Def - (IPv6) Internet Protocol version 6|IPv6]]**: Uses 128-bit addresses (e.g. 2001:db8::1), designed to vastly expand address space and improve routing efficiency.

Key characteristics of [[Def - (IP) Internet Protocol|IP]]:
- **Connectionless protocol**: Each packet is routed independently, possibly taking different paths.
- **Routing**: Works in conjunction with routing protocols (e.g. [[Def - (OSPF) Open Shortest Path First|OSPF]], [[Def - (BGP) Border Gateway Protocol|BGP]]) to determine packet paths.
- **Foundation of all internet communication**: Used by protocols like [[Def - (TCP) Transmission Control Protocol|TCP]], [[Def - (UDP) User Datagram Protocol|UDP]], and ICMP.

[[Def - (IP) Internet Protocol|IP]] is essential to how the internet functions, forming the basis of all modern networked communication.
