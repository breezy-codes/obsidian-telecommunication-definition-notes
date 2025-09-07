---
aliases:
  - Source-Specific Multicast
  - SSM
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer3
---

**Source-Specific Multicast ([[Def - (SSM) Source-Specific Multicast|SSM]])** is a form of [[Def - (IP) Internet Protocol|IP]] multicast that allows receivers to receive traffic only from a **specific source** rather than from any sender in a multicast group. This provides greater control, security, and efficiency compared to traditional multicast models.

In [[Def - (SSM) Source-Specific Multicast|SSM]], receivers specify both the **multicast group address** and the **[[Def - (IP) Internet Protocol|IP]] address of the source** they want to receive traffic from. This is known as an (S,G) join, where **S** is the source and **G** is the multicast group.

Key benefits of [[Def - (SSM) Source-Specific Multicast|SSM]]:
- **Improved security**: Prevents unwanted or malicious senders from injecting traffic into the group.
- **Simplified routing**: Removes the need for shared trees or Rendezvous Points (RPs) used in [[Def - (PIM) Protocol Independent Multicast|PIM]]-SM.
- **Efficient delivery**: Builds shortest-path trees directly from source to receiver.

[[Def - (SSM) Source-Specific Multicast|SSM]] is commonly used in applications like IPTV, live video streaming, and conferencing, where the source is known and fixed. It relies on **IGMPv3** (for [[Def - (IPv4) Internet Protocol version 4|IPv4]]) or **MLDv2** (for [[Def - (IPv6) Internet Protocol version 6|IPv6]]) and operates with **PIM-SSM** as the routing protocol.
