---
aliases:
  - Evolved Packet Core
  - EPC
tags:
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer3
  - telecommunications/OSI-model/layer4
---

**[[Def - (EPC) Evolved Packet Core|Evolved Packet Core (EPC)]]** is the all-IP core network architecture introduced in [[Def - (LTE) Long Term Evolution|LTE]] (Long Term Evolution) to support high-speed, low-latency data and voice services. Unlike earlier mobile networks that used circuit switching for voice and packet switching for data, [[Def - (EPC) Evolved Packet Core|EPC]] uses a **flat, packet-switched architecture** for all types of traffic.

[[Def - (EPC) Evolved Packet Core|EPC]] is responsible for managing user sessions, mobility, authentication, policy enforcement, and connectivity to external networks (e.g. the Internet or IMS). It provides seamless mobility and QoS support across access technologies, including [[Def - (LTE) Long Term Evolution|LTE]], 3G, WiFi, and future 5G integration.

Core components of [[Def - (EPC) Evolved Packet Core|EPC]] include:
- **MME (Mobility Management Entity)**: Handles signalling, user authentication, and mobility management for [[Def - (LTE) Long Term Evolution|LTE]].
- **SGW (Serving Gateway)**: Routes and forwards user data packets, acts as the anchor point during handovers.
- **PGW (Packet Data Network Gateway)**: Connects to external packet networks, handles IP address allocation, QoS enforcement, and charging.
- **PCRF (Policy and Charging Rules Function)**: Determines policy rules and charging for each data flow.
- **HSS (Home Subscriber Server)**: Central database containing user profiles, subscription data, and authentication information.

Key features of [[Def - (EPC) Evolved Packet Core|EPC]]:
- **All-IP architecture**: Enables convergence of voice, video, and data over a single network.
- **Support for IMS**: Enables services like VoLTE (Voice over [[Def - (LTE) Long Term Evolution|LTE]]) and video calling.
- **Scalability and flexibility**: Designed to handle increasing data demands and diverse applications.

[[Def - (EPC) Evolved Packet Core|EPC]] laid the foundation for 4G LTE networks and continues to be relevant in 5G **non-standalone (NSA)** deployments, where 5G radios connect to an existing EPC before full transition to 5G Core.
