---
aliases:
  - Protocol Independent Multicast
  - PIM
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer3
---

**Protocol Independent Multicast ([[Def - (PIM) Protocol Independent Multicast|PIM]])** is a family of multicast routing protocols used to efficiently deliver data to multiple receivers across an [[Def - (IP) Internet Protocol|IP]] network. The “protocol independent” part means it works with any underlying unicast routing protocol (e.g. [[Def - (OSPF) Open Shortest Path First|OSPF]], [[Def - (IS-IS) Intermediate System to Intermediate System|IS-IS]], [[Def - (BGP) Border Gateway Protocol|BGP]]).

[[Def - (PIM) Protocol Independent Multicast|PIM]] does not build its own routing table, instead, it uses the existing unicast routing table to determine how to forward multicast traffic.

[[Def - (PIM) Protocol Independent Multicast|PIM]] has several operating modes:
- **PIM Dense Mode (PIM-DM)**: Assumes most nodes want to receive multicast traffic and initially floods it to all routers before pruning unused paths.
- **PIM Sparse Mode (PIM-SM)**: Assumes few nodes want the multicast data and only sends traffic to those who explicitly request it, using a shared tree rooted at a **Rendezvous Point (RP)**.
- **PIM-SSM (Source-Specific Multicast)**: Optimised for one-to-many multicast where receivers know the source.

[[Def - (PIM) Protocol Independent Multicast|PIM]] is widely used for applications like IPTV, video conferencing, and software distribution where efficient one-to-many communication is required.
