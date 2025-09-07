---
aliases:
  - Automatic Repeat Request
  - ARQ
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/definitions/ran-architectures-and-components
  - telecommunications/OSI-model/layer2
---

**Automatic Repeat Request ([[Def - (ARQ) Automatic Repeat Request|ARQ]])** is a fundamental error control technique used in data communication systems to ensure reliable data transmission over potentially unreliable channels. It works by detecting errors in received packets (typically using checksums or CRCs) and requesting retransmissions when errors are found.

[[Def - (ARQ) Automatic Repeat Request|ARQ]] is a **stop-and-wait** or **acknowledgement-based** protocol: the sender transmits a data packet and waits for a positive acknowledgement (ACK) from the receiver. If an error is detected or no ACK is received within a timeout, the sender retransmits the packet.

There are several ARQ variants:
- **Stop-and-Wait ARQ**: Waits for an ACK before sending the next frame.
- **Go-Back-N ARQ**: Allows multiple frames in flight but retransmits from the error point.
- **Selective Repeat ARQ**: Retransmits only the specific erroneous frames, improving efficiency.

[[Def - (ARQ) Automatic Repeat Request|ARQ]] is typically used in higher-layer protocols like **[[Def - (TCP) Transmission Control Protocol|TCP]]** and in some wireless protocols. In mobile networks, it is complemented by **[[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]]** at the [[Def - (MAC) Medium Access Control|MAC]] layer, which adds forward error correction for faster retransmissions.
