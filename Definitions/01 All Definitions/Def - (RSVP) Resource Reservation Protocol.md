---
aliases:
  - Resource Reservation Protocol
  - RSVP
tags:
  - telecommunications/definitions/control-label-switching-and-management
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/definitions/optical-network-and-components
  - telecommunications/OSI-model/layer3
---

**Resource Reservation Protocol ([[Def - (RSVP) Resource Reservation Protocol|RSVP]])** is a network control protocol used to reserve resources across an [[Def - (IP) Internet Protocol|IP]] network for data flows that require specific Quality of Service (QoS), such as voice, video, or real-time applications. It allows devices to request and reserve bandwidth along the route that data will travel, helping ensure consistent performance.

[[Def - (RSVP) Resource Reservation Protocol|RSVP]] operates by sending **PATH** and **RESV** messages:
- A **PATH** message is sent from the sender to the receiver, identifying the flow and its resource needs.
- A **RESV** message travels back from the receiver to the sender, reserving the necessary resources along the way.

Key characteristics:
- **Soft state**: Reservations are refreshed periodically and automatically expire if not maintained.
- **Receiver-oriented**: The receiver determines how much bandwidth to reserve.
- **Works with IP routing**: [[Def - (RSVP) Resource Reservation Protocol|RSVP]] doesn’t determine the route but reserves resources along the existing path.

[[Def - (RSVP) Resource Reservation Protocol|RSVP]] is used in integrated services (IntServ) networks and as part of the control plane in [[Def - (MPLS) Multi-Protocol Label Switching|MPLS]] traffic engineering (RSVP-TE), where it helps establish Label Switched Paths with bandwidth guarantees.
