---
aliases:
  - Software Defined Networking
  - SDN
tags:
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/cross-layer
---

**Software Defined Networking ([[Def - (SDN) Software Defined Networking|SDN]])** is a networking architecture that separates the control plane (which decides how traffic is routed) from the data plane (which forwards traffic). This separation allows network control to become directly programmable, enabling more flexible and centralised management of network behaviour.

In traditional networks, each device (like a switch or router) independently makes routing decisions based on locally stored information. In contrast, [[Def - (SDN) Software Defined Networking|SDN]] introduces a centralised controller that has a global view of the network and dictates forwarding rules to all devices. These rules are communicated using protocols such as OpenFlow.

A typical [[Def - (SDN) Software Defined Networking|SDN]] setup includes three layers:
- **Application layer**: Network applications (e.g. load balancers, firewalls) that define network behaviour.
- **Control layer**: The [[Def - (SDN) Software Defined Networking|SDN]] controller that translates application requirements into network rules.
- **Infrastructure layer**: The physical or virtual network devices (switches, routers) that follow the rules set by the controller.

Benefits of [[Def - (SDN) Software Defined Networking|SDN]] include:
- **Centralised control**: Makes it easier to configure, monitor, and optimise the entire network.
- **Programmability**: Enables automation and dynamic adjustment of network policies.
- **Vendor neutrality**: Encourages use of open standards and interoperable equipment.

[[Def - (SDN) Software Defined Networking|SDN]] is especially valuable in large-scale, cloud, or dynamic environments where frequent changes and fine-grained control are required.
