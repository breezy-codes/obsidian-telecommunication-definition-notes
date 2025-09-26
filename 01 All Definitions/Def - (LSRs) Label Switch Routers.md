---
aliases:
  - Label Switch Routers
  - LSRs
  - LSR
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer2
  - telecommunications/OSI-model/layer3
---

**Label Switch Routers ([[Def - (LSRs) Label Switch Routers|LSRs]])** are core components in an **[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] (Multiprotocol Label Switching)** network, responsible for forwarding packets based on **labels** rather than traditional [[Def - (IP) Internet Protocol|IP]] addresses. These routers operate within the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] domain, handling **label swapping** as packets traverse **Label Switched Paths ([[Def - (LSP) Label Switched Path|LSP]]s)**.

An [[Def - (LSRs) Label Switch Routers|LSR]] receives a labelled packet, examines the incoming label, and uses a **label forwarding table** to determine the next hop and the **outgoing label**. It then swaps the label and forwards the packet accordingly.

There are several types of [[Def - (LSRs) Label Switch Routers|LSRs]] based on their role in the [[Def - (LSP) Label Switched Path|LSP]]:
- **Ingress LSR**: Pushes the initial label onto an [[Def - (IP) Internet Protocol|IP]] packet at the start of an [[Def - (LSP) Label Switched Path|LSP]].
- **Transit LSR**: Swaps labels as packets move through the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] network.
- **Egress LSR**: Pops (removes) the label before forwarding the packet out of the [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] domain.

Key functions of [[Def - (LSRs) Label Switch Routers|LSRs]]:
- **Label switching**: Based on label forwarding tables populated via protocols like **[[Def - (LDP) Label Distribution Protocol|LDP]]** or **[[Def - (RSVP) Resource Reservation Protocol|RSVP]]-TE**.
- **Traffic engineering**: In advanced deployments, [[Def - (LSRs) Label Switch Routers|LSRs]] can implement policies for load balancing or priority forwarding.
- **Fast packet forwarding**: Label lookups are simpler and faster than full [[Def - (IP) Internet Protocol|IP]] routing table lookups.

[[Def - (LSRs) Label Switch Routers|LSRs]] enable [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] networks to offer scalable, high-performance services such as [[Def - (VPN) Virtual Private Network|VPN]]s, traffic engineering, and Quality of Service (QoS) guarantees.
