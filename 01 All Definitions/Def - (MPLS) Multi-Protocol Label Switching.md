---
aliases:
  - Multi-Protocol Label Switching
  - MPLS
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/network-tech-and-concepts
---

**Multi-Protocol Label Switching ([[Def - (MPLS) Multi-Protocol Label Switching|MPLS]])** is a high-performance data forwarding technique used in modern telecommunications networks to route packets based on short path labels rather than long network addresses. It is designed to speed up traffic flow and enable efficient use of network resources across large-scale networks.

In [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]], when a packet enters the network, it is assigned a label by a router known as a **Label Edge Router ([[Def - (LER) Label Edge Router |LER]])**. This label acts as a shorthand for the path the packet should follow. As the packet travels through the network, **Label Switching Routers ([[Def - (LSRs) Label Switch Routers|LSRs]])** use the label to quickly forward the packet without inspecting its [[Def - (IP) Internet Protocol|IP]] header. Labels can be swapped at each hop, enabling flexible and efficient routing.

[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] operates between Layer 2 (data link layer) and Layer 3 (network layer) of the [[Def - OSI Model|OSI Model]], and supports multiple network protocols, including [[Def - (IP) Internet Protocol|IP]], Ethernet, and ATM.

Key features of [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]]:
- **Traffic engineering**: Allows fine-grained control over routing paths, improving performance and reliability.
- **Quality of Service (QoS)**: Supports prioritisation of different traffic types (e.g. voice, video, data).
- **Scalability**: Efficient for handling large volumes of traffic across service provider backbones.
- **[[Def - (VPN) Virtual Private Network|VPN]] support**: Enables Layer 3 and Layer 2 Virtual Private Networks by isolating traffic between customers.

Common [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] applications include:
- **Service provider backbones**: Core networks for [[Def - (ISP) Internet Service Provider|ISP]]s and carriers.
- **Virtual Private Networks ([[Def - (VPN) Virtual Private Network|VPN]]s)**: Secure and scalable connectivity for enterprise customers.
- **Carrier Ethernet**: Delivering Ethernet services with high reliability and service guarantees.

[[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] remains a key technology in many telecom networks and forms the foundation for more advanced architectures such as [[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]] and Segment Routing.
