---
aliases:
  - Label Edge Router
  - LER
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Label Edge Router (LER)** is a specialised router in an [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] (Multi-Protocol Label Switching) network that operates at the edge of the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] domain. Its main role is to interface between traditional IP networks and the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] core by assigning and removing labels from packets.

When a packet enters the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] network, the ingress LER examines the packet's IP header and determines the appropriate **Forwarding Equivalence Class ([[Def - (FEC) Forwarding Equivalence Class|FEC]])**—a group of packets that are treated the same way through the network. It then attaches an [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] label to the packet and forwards it into the core.

At the other end of the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] path, the egress LER receives the labelled packet, removes the label (a process called **label popping**), and forwards the original packet toward its final destination using standard IP routing.

Key responsibilities of an LER:
- **Label imposition**: Adds a label to incoming IP packets at the network edge.
- **Label removal**: Strips the label from [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] packets before forwarding them out of the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] domain.
- **Traffic classification**: Maps incoming packets to [[Def - (FEC) Forwarding Equivalence Class|FEC]]s based on destination, QoS, or other policies.
- **Policy enforcement**: Applies routing policies, access control, and quality of service settings at the network boundary.

LERs play a critical role in enabling [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] features such as traffic engineering, VPNs, and QoS. They are essential for translating between conventional IP forwarding and the label-based switching used in the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] core.
