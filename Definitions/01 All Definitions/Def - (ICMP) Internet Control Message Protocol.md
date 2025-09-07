---
aliases:
  - Internet Control Message Protocol
  - ICMP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/OSI-model/layer3
---

**Internet Control Message Protocol ([[Def - (ICMP) Internet Control Message Protocol|ICMP]])** is a network-layer protocol used to send **error messages, diagnostics, and control information** between [[Def - (IPv6) Internet Protocol version 6|IPv6]] devices. It is an integral part of [[Def - (IP) Internet Protocol|IP]] networking, providing feedback about issues in data delivery rather than delivering data itself.

[[Def - (ICMP) Internet Control Message Protocol|ICMP]] messages are typically generated in response to:
- **Routing errors** (e.g. unreachable hosts or networks)
- **Packet delivery issues** (e.g. time exceeded)
- **Diagnostic tools** (e.g. `ping` and `traceroute`)

Key types of [[Def - (ICMP) Internet Control Message Protocol|ICMP]] messages:
- **Echo Request and Echo Reply**: Used in `ping` to test reachability.
- **Destination Unreachable**: Indicates that a packet could not reach its destination.
- **Time Exceeded**: Informs that a packet was discarded because its TTL expired.
- **Redirect**: Suggests a better route to the destination.

[[Def - (ICMP) Internet Control Message Protocol|ICMP]] operates directly over [[Def - (IPv6) Internet Protocol version 6|IPv6]] (protocol number 1 for [[Def - (IPv4) Internet Protocol version 4|IPv4]] and 58 for [[Def - (IPv6) Internet Protocol version 6|IPv6]]) and is not typically used by applications directly, but by the network layer and tools to diagnose and report issues. While [[Def - (ICMP) Internet Control Message Protocol|ICMP]] is essential for healthy network operations, it is sometimes restricted by firewalls to mitigate abuse in denial-of-service attacks.
