---
aliases:
  - Label Switched Path
  - LSP
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Label Switched Path ([[Def - (LSP) Label Switched Path|LSP]])** is a unidirectional path through an **[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] (Multiprotocol Label Switching)** network, established for forwarding packets based on **labels** rather than traditional [[Def - (IP) Internet Protocol|IP]] routing. An [[Def - (LSP) Label Switched Path|LSP]] is created between an **ingress Label Edge Router ([[Def - (LER) Label Edge Router|LER]])** and an **egress [[Def - (LER) Label Edge Router|LER]]**, with intermediate **Label Switch Routers ([[Def - (LSRs) Label Switch Routers|LSRs]]s)** forwarding packets by swapping labels.

In an [[Def - (LSP) Label Switched Path|LSP]], each packet is assigned a short fixed-length label at the ingress, and forwarding decisions at each hop are made based on that label, rather than a full [[Def - (IP) Internet Protocol|IP]] lookup. This allows [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] to offer fast, predictable forwarding and traffic engineering capabilities.

Key features of [[Def - (LSP) Label Switched Path|LSP]]s:
- **Pre-established or dynamically signalled**: Using protocols like [[Def - (RSVP) Resource Reservation Protocol|RSVP]]-TE (Resource Reservation Protocol with Traffic Engineering) or [[Def - (LDP) Label Distribution Protocol|LDP]] (Label Distribution Protocol).
- **Traffic engineering**: Operators can control the path that data takes through the network, avoiding congestion or prioritising specific traffic flows.
- **Supports QoS and [[Def - (VPN) Virtual Private Network|VPN]]s**: [[Def - (LSP) Label Switched Path|LSP]]s can be associated with different service levels and used to isolate customer traffic.
- **Efficient forwarding**: Label switching is faster than traditional [[Def - (IP) Internet Protocol|IP]] routing, especially in large networks.

[[Def - (LSP) Label Switched Path|LSP]]s are foundational to [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] networks, enabling services like Layer 3 [[Def - (VPN) Virtual Private Network|VPN]]s, Layer 2 pseudowires, and segment routing. Despite being unidirectional, they can be used in pairs to support bidirectional communication.
