---
aliases:
  - Address Resolution Protocol
  - ARP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Address Resolution Protocol ([[Def - (ARP) Address Resolution Protocol|ARP]])** is a network protocol used in **[[Def - (IPv4) Internet Protocol version 4|IPv4]]** to map **IP addresses** to **[[Def - (MAC) Medium Access Control|MAC]] (Media Access Control) addresses** on a local area network ([[Def - (LAN) Local Area Network|LAN]]). It operates at the boundary between Layer 2 (Data Link) and Layer 3 (Network) of the [[Def - OSI Model|OSI Model]] and enables devices to discover the physical hardware address associated with an [[Def - (IP) Internet Protocol|IP]] address on the same subnet.

When a device wants to send a packet to another host on the same LAN, it checks its **[[Def - (ARP) Address Resolution Protocol|ARP]] cache**:
- If the [[Def - (MAC) Medium Access Control|MAC]] address for the destination [[Def - (IP) Internet Protocol|IP]] is not known, the device broadcasts an **[[Def - (ARP) Address Resolution Protocol|ARP]] Request** packet.
- The device with the matching [[Def - (IP) Internet Protocol|IP]] address replies with an **[[Def - (ARP) Address Resolution Protocol|ARP]] Reply**, supplying its [[Def - (MAC) Medium Access Control|MAC]] address.
- The sender stores this mapping in its [[Def - (ARP) Address Resolution Protocol|ARP]] cache for future use.

Key features of [[Def - (ARP) Address Resolution Protocol|ARP]]:
- **Broadcast-based discovery**: [[Def - (ARP) Address Resolution Protocol|ARP]] Requests are sent to all devices on the local subnet.
- **Stateless protocol**: Each request is independent; there's no formal session or handshake.
- **Vulnerable to spoofing**: Lacks authentication, making it susceptible to [[Def - (ARP) Address Resolution Protocol|ARP]] poisoning attacks (e.g. MITM attacks).
- **Cached entries**: Reduce network traffic by storing mappings temporarily.

[[Def - (ARP) Address Resolution Protocol|ARP]] is **used only in [[Def - (IPv4) Internet Protocol version 4|IPv4]]**. In **[[Def - (IPv6) Internet Protocol version 6|IPv6]]**, it is replaced by **Neighbour Discovery Protocol ([[Def - (NDP) Neighbour Discovery Protocol|NDP]])**, which performs similar functions but with added security and features.
