---
aliases:
  - Hybrid Automatic Repeat Request
  - HARQ
tags:
  - telecommunications/definitions/radio-protocols
  - telecommunications/OSI-model/layer2
---

**Hybrid Automatic Repeat Request ([[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]])** is a key error control mechanism used in [[Def - (LTE) Long Term Evolution|LTE]], 5G, and other wireless communication systems. It combines traditional Automatic Repeat Request ([[Def - (ARQ) Automatic Repeat Request|ARQ]]) with Forward Error Correction (FEC) to improve reliability and efficiency in transmitting data over noisy or unreliable channels.

When a data packet is received with errors, [[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]] requests a retransmission, but instead of sending the entire packet again, it transmits additional redundancy (parity) bits. The receiver then combines the original and retransmitted data to reconstruct the correct message, improving the chances of successful decoding.

Key aspects of [[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]]:
- **Soft combining**: Stores previous transmissions and combines them with new ones to improve decoding.
- **Fast retransmissions**: Operates with low latency, essential for real-time applications.
- **Multiple processes**: Supports parallel [[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]] processes to maintain throughput.

[[Def - (HARQ) Hybrid Automatic Repeat Request|HARQ]] is managed at the [[Def - (MAC) Medium Access Control|MAC]] layer and is a fundamental part of how mobile networks achieve both high performance and robustness in varying radio conditions.
