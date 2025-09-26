---
aliases:
  - Real-time Transport Protocol
  - RTP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Real-time Transport Protocol ([[Def - (RTP) Real-time Transport Protocol|RTP]])** is a **network protocol** used to **deliver audio, video, and other real-time media** over [[Def - (IP) Internet Protocol|IP]] networks. Defined in **RFC 3550**, [[Def - (RTP) Real-time Transport Protocol|RTP]] is widely used in **VoIP**, **video conferencing**, **streaming**, and **online gaming**, where low latency and timely delivery are essential.

RTP operates typically over:
- **[[Def - (UDP) User Datagram Protocol|UDP]]**: Using ephemeral ports negotiated during session setup (e.g. via [[Def - (SIP) Session Initiation Protocol|SIP]]/[[Def - (SDP) Session Description Protocol|SDP]]).
- **RTP/RTCP pair**:[[Def - (RTP) Real-time Transport Protocol|RTP]] carries media, while RTCP ([[Def - (RTP) Real-time Transport Protocol|RTP]] Control Protocol) monitors quality and synchronisation.

Key features:
- **Sequence numbers**: Ensure packet ordering and detect loss.
- **Timestamps**: Used to synchronise and reconstruct playback timing.
- **Payload types**: Indicate codec and format (e.g. G.711, H.264).
- **Extensible headers**: Allow for custom application-specific features.

[[Def - (RTP) Real-time Transport Protocol|RTP]] does **not guarantee delivery** (as it's based on [[Def - (UDP) User Datagram Protocol|UDP]]), but is designed to support **jitter buffering**, **packet reordering**, and **loss concealment** in real-time applications. It forms the media transport backbone of modern voice and video services, alongside [[Def - (SIP) Session Initiation Protocol|SIP]] and [[Def - (SDP) Session Description Protocol|SDP]] for session control and negotiation.
