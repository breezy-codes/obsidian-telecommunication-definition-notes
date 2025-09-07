---
aliases:
  - Radio Link Control
  - RLC
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer2
---

**Radio Link Control ([[Def - (RLC) Radio Link Control|RLC]])** is a sublayer in the Layer 2 protocol stack of [[Def - (LTE) Long Term Evolution|LTE]] and 5G that operates between the [[Def - (MAC) Medium Access Control|MAC]] and [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] layers. Its main role is to ensure reliable transfer of data across the radio interface, providing segmentation, retransmission, and in-sequence delivery of packets.

RLC supports three operational modes:
- **Transparent Mode (TM)**: No RLC headers, used for fixed-size messages like broadcast information.
- **Unacknowledged Mode (UM)**: Provides error detection without retransmission (used for streaming).
- **Acknowledged Mode (AM)**: Offers full reliability via retransmissions (used for critical data transfer).

Core functions of [[Def - (RLC) Radio Link Control|RLC]] include:
- **Segmentation and reassembly**: Divides and reconstructs [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] SDUs to fit [[Def - (MAC) Medium Access Control|MAC]] PDU sizes.
- **Retransmission**: In AM mode, ensures data delivery by retransmitting lost or corrupted PDUs.
- **In-order delivery**: Ensures that data is passed up to [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] in the correct sequence.

[[Def - (RLC) Radio Link Control|RLC]] is typically implemented in the [[Def - (DU) Distributed Unit|DU]] in 5G networks due to its real-time processing requirements.
