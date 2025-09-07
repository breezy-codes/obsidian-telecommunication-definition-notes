---
aliases:
  - Packet Data Convergence Protocol
  - PDCP
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer2
---

**Packet Data Convergence Protocol ([[Def - (PDCP) Packet Data Convergence Protocol|PDCP]])** is a sublayer in the radio protocol stack used in [[Def - (LTE) Long Term Evolution|LTE]] and 5G networks, located above the [[Def - (RLC) Radio Link Control|RLC]] (Radio Link Control) layer and below the [[Def - (IP) Internet Protocol|IP]] layer. It exists in both the user plane and control plane, playing a key role in data integrity, security, and efficient transmission.

In the **user plane**, [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] handles:
- **Header compression**: Reduces [[Def - (IP) Internet Protocol|IP]]/[[Def - (UDP) User Datagram Protocol|UDP]]/[[Def - (RTP) Real-time Transport Protocol|RTP]] header size to save bandwidth using techniques like ROHC (Robust Header Compression).
- **Security functions**: Performs ciphering (encryption) and integrity protection to secure user data.
- **Reordering and duplication detection**: Ensures data packets arrive in order, especially in dual connectivity or multi-path scenarios.

In the **control plane**, [[Def - (PDCP) Packet Data Convergence Protocol|PDCP]] is responsible for:
- **Signalling ciphering and integrity protection**: Protects [[Def - (RRC) Radio Resource Control|RRC]] signalling messages between [[Def - (UE) User Equipment|UE]] and the network.

[[Def - (PDCP) Packet Data Convergence Protocol|PDCP]]’s position in the protocol stack enables it to manage end-to-end delivery properties before data is passed to or received from the core network. It is implemented in the [[Def - (CU) Centralised Unit|CU]] (Central Unit) in disaggregated [[Def - (RAN) Radio Access Network|RAN]] architectures.
