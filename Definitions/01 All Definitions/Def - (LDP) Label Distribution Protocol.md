---
aliases:
  - Label Distribution Protocol
  - LDP
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Label Distribution Protocol (LDP)** is a signalling protocol used in **MPLS (Multiprotocol Label Switching)** networks to establish **Label Switched Paths (LSPs)** by distributing labels between routers. LDP operates by mapping IP routing information to label information, enabling routers to forward packets based on short labels instead of longer IP addresses.

LDP is a **protocol-driven** and **hop-by-hop** mechanism: each router independently selects a label for a destination prefix and advertises it to its neighbours. This builds an LSP that follows the same path as the underlying IGP (e.g. OSPF or IS-IS), without requiring explicit path definition.

Key features of LDP:
- **Automatic LSP setup**: Based on existing IGP routes, requiring no manual configuration of the path.
- **Label mapping**: Assigns and advertises labels for IP prefixes using UDP/TCP on port 646.
- **Session establishment**: Uses Hello messages to discover neighbours and TCP sessions to exchange label information.
- **Supports loop-free forwarding**: Ensures consistent label bindings across the MPLS domain.

While not offering advanced traffic engineering like RSVP-TE, LDP is simpler to deploy and manage, making it popular for best-effort MPLS services, including **Layer 3 VPNs** and basic transport networks.
