---
aliases:
  - Internet Group Management Protocol
  - IGMP
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer3
---
**Internet Group Management Protocol ([[Def - (IGMP) Internet Group Management Protocol|IGMP]])** is a network-layer protocol used by IPv4 systems to manage multicast group memberships. It allows hosts to inform local routers that they want to receive multicast traffic for specific groups.

Multicast enables efficient one-to-many communication, such as streaming video or sending updates to multiple devices simultaneously, by delivering a single stream to multiple recipients.

How [[Def - (IGMP) Internet Group Management Protocol|IGMP]] works:
- **Join**: A host sends an [[Def - (IGMP) Internet Group Management Protocol|IGMP]] message to join a multicast group.
- **Query**: Routers send periodic queries to check which groups are still needed.
- **Leave**: Hosts notify the router when they no longer wish to receive a group's traffic.

Key characteristics:
- **Works on local networks**: [[Def - (IGMP) Internet Group Management Protocol|IGMP]] messages are not forwarded beyond the local subnet.
- **Supports multicast efficiency**: Reduces bandwidth by avoiding duplicate streams.
- **Used with multicast routing protocols**: Such as [[Def - (PIM) Protocol Independent Multicast|PIM]] (Protocol Independent Multicast), which route traffic based on [[Def - (IGMP) Internet Group Management Protocol|IGMP]] membership.

[[Def - (IGMP) Internet Group Management Protocol|IGMP]] is essential for enabling multicast applications like IPTV, conferencing, and network discovery services.
