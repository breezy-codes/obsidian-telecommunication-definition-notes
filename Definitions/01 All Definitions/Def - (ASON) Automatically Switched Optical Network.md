---
aliases:
  - Automatically Switched Optical Network
  - ASON
tags:
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/definitions/network-tech-and-concepts
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer1
  - telecommunications/OSI-model/layer2
---

**Automatically Switched Optical Network ([[Def - (ASON) Automatically Switched Optical Network|ASON]])** is a control-plane architecture for optical transport networks that enables dynamic, automated provisioning and management of optical connections. It allows optical paths (light-paths) to be set up, modified, or torn down in real time without manual intervention, improving the flexibility and efficiency of optical networks.

[[Def - (ASON) Automatically Switched Optical Network|ASON]] was developed by the International Telecommunication Union ([[Def - (ITU-T) ITU Telecom Standardisation Sector|ITU-T]]) to introduce intelligence into the optical transport layer. It separates the network into three planes:
- **Transport plane**: Carries the actual user data over optical channels.
- **Control plane**: Handles signalling, routing, and resource management to establish and manage connections.
- **Management plane**: Provides configuration, performance monitoring, and fault management.

The key functions of the [[Def - (ASON) Automatically Switched Optical Network|ASON]] control plane include:
- **Routing**: Determining viable paths through the network using protocols like [[Def - (OSPF) Open Shortest Path First|OSPF]]-TE.
- **Signalling**: Setting up and releasing connections using protocols such as [[Def - (GMPLS) Generalised Multi-Protocol Label Switching|GMPLS]].
- **Discovery and topology exchange**: Automatically learning and distributing information about network elements and their connectivity.

Benefits of [[Def - (ASON) Automatically Switched Optical Network|ASON]]:
- **Dynamic provisioning**: Connections can be established on demand, reducing setup times.
- **Improved resource utilisation**: Optimises use of wavelengths and paths based on network conditions.
- **Resilience and recovery**: Enables fast rerouting in response to faults or congestion.
- **Interoperability**: Based on standardised protocols, facilitating multi-vendor environments.

[[Def - (ASON) Automatically Switched Optical Network|ASON]] is especially useful in large, high-capacity optical backbones and metro networks where traffic patterns are variable and service agility is critical. It lays the groundwork for more advanced concepts such as intelligent and software-defined optical networking.
