---
aliases:
  - Real-Time Streaming Protocol
  - RTSP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Real-Time Streaming Protocol ([[Def - (RTSP) Real-Time Streaming Protocol|RTSP]])** is an **application-layer protocol** used to **control the delivery of multimedia streams** over [[Def - (IP) Internet Protocol|IP]] networks. Defined in **RFC 2326**, [[Def - (RTSP) Real-Time Streaming Protocol|RTSP]] acts as a **network remote control**, allowing clients to issue commands such as **play, pause, record, and seek** for audio and video streams.

[[Def - (RTSP) Real-Time Streaming Protocol|RTSP]] is commonly used in:
- **Streaming media servers**: To deliver content such as live broadcasts or on-demand video.
- **IP cameras and surveillance systems**: To enable real-time monitoring.
- **Multimedia applications**: That require precise stream control independent of the transport layer.

[[Def - (RTSP) Real-Time Streaming Protocol|RTSP]] typically works with:
- **[[Def - (RTP) Real-time Transport Protocol|RTP]] (Real-time Transport Protocol)** for media delivery.
- **[[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] (RTP Control Protocol)** for performance feedback and quality monitoring.

Key RTSP operations:
- **SETUP**: Establishes a stream and negotiates transport.
- **PLAY**: Starts media delivery.
- **PAUSE**: Temporarily halts the stream.
- **TEARDOWN**: Ends the session and releases resources.
- **DESCRIBE**: Retrieves metadata or stream descriptions (often using SDP).

Transport:
- [[Def - (RTSP) Real-Time Streaming Protocol|RTSP]] itself typically uses **[[Def - (TCP) Transmission Control Protocol|TCP]] port 554**.
- [[Def - (RTP) Real-time Transport Protocol|RTP]] media may be sent over [[Def - (UDP) User Datagram Protocol|UDP]] or [[Def - (TCP) Transmission Control Protocol|TCP]], depending on configuration and firewall constraints.

Unlike HTTP, which is stateless, [[Def - (RTSP) Real-Time Streaming Protocol|RTSP]] maintains **session state**, making it ideal for interactive media applications. However, it is being supplemented or replaced in some contexts by **HTTP-based streaming** (e.g. HLS, MPEG-DASH) for better compatibility with firewalls and CDNs.
