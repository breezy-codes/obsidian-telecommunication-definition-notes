---
aliases:
  - Forwarding Equivalence Class
  - FEC
tags:
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/OSI-model/layer3
---

**Forwarding Equivalence Class ([[Def - (FEC) Forwarding Equivalence Class|FEC]])** is a concept used in [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] (Multi-Protocol Label Switching) to group packets that are forwarded in the same way across the network. All packets in a given [[Def - (FEC) Forwarding Equivalence Class|FEC]] receive the same treatment, meaning they follow the same path and are subject to the same forwarding policies, regardless of their individual headers.

Rather than analysing the full [[Def - (IP) Internet Protocol|IP]] header at every hop, [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] networks classify incoming packets into [[Def - (FEC) Forwarding Equivalence Class|FEC]]s at the edge (by a [[Def - (LER) Label Edge Router |LER]]), assign each [[Def - (FEC) Forwarding Equivalence Class|FEC]] a label, and forward packets based on that label. This improves forwarding speed and allows for more efficient routing.

FECs can be defined based on:
- **Destination [[Def - (IP) Internet Protocol|IP]] address**
- **Source and destination pair**
- **Traffic type or QoS level**
- **[[Def - (VPN) Virtual Private Network|VPN]] membership**
- **Application or service policy**

Once packets are mapped to an [[Def - (FEC) Forwarding Equivalence Class|FEC]], they are handled identically by the network. Each [[Def - (FEC) Forwarding Equivalence Class|FEC]] is associated with a **Label Switched Path ([[Def - (LSP) Label Switched Path|LSP]])**, a predetermined route through the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] network.

Benefits of using FECs:
- **Simplified forwarding**: Reduces the need to process full packet headers at every hop.
- **Traffic engineering**: Enables precise control over how different types of traffic are routed.
- **Scalability**: Aggregates many flows into fewer, manageable forwarding classes.
- **Support for services**: Facilitates the creation of [[Def - (VPN) Virtual Private Network|VPN]]s and QoS policies by grouping traffic based on service-level requirements.

[[Def - (FEC) Forwarding Equivalence Class|FEC]]s are fundamental to how [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] achieves high-performance, flexible routing across complex and high-speed networks.
