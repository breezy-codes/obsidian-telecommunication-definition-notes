---
aliases:
  - Real-time Transport Control Protocol
  - RTCP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Real-time Transport Control Protocol ([[Def - (RTCP) Real-time Transport Control Protocol|RTCP]])** is a companion protocol to **[[Def - (RTP) Real-time Transport Protocol|RTP]] (Real-time Transport Protocol)** used to **monitor and manage media streaming sessions** over IP networks. Defined in **RFC 3550**, [[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] provides out-of-band control information to participants in a real-time session, enabling feedback on transmission quality, synchronisation, and session control.

While [[Def - (RTP) Real-time Transport Protocol|RTP]] handles the actual transport of audio, video, or other real-time data, [[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] operates **alongside [[Def - (RTP) Real-time Transport Protocol|RTP]]**, typically over a separate [[Def - (UDP) User Datagram Protocol|UDP]] port, sending periodic control packets that contain statistical and status information.

Key functions of [[Def - (RTCP) Real-time Transport Control Protocol|RTCP]]:
- **Quality of Service (QoS) monitoring**: Reports on packet loss, jitter, round-trip time, and delay.
- **Sender and receiver reports**: Include information such as:
  - **Packet count and byte count**
  - **Last sender timestamp (LSR)**
  - **Delay since last report (DLSR)**
- **Synchronisation**: Helps align audio and video streams in applications with multiple media types by correlating [[Def - (RTP) Real-time Transport Protocol|RTP]] timestamps to wall-clock time.
- **Participant identification**: Each participant includes a **canonical name (CNAME)**, allowing others to associate multiple streams from the same source.
- **Session scaling**: [[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] limits its own bandwidth usage (usually to 5% of session bandwidth) to avoid overwhelming the network.

Common [[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] packet types:
- `SR`: **Sender Report** – sent by active [[Def - (RTP) Real-time Transport Protocol|RTP]] senders with transmission and reception stats.
- `RR`: **Receiver Report** – sent by passive receivers with feedback on received streams.
- `SDES`: **Source Description** – conveys information such as name, email, and tool used.
- `BYE`: Indicates that a source is leaving the session.
- `APP`: Application-specific messages.

[[Def - (RTCP) Real-time Transport Control Protocol|RTCP]] is critical for **real-time session health** and enables adaptive behaviours like bit-rate adjustment and stream switching in response to network conditions. It is widely used in [[Def - (VoIP) Voice over Internet Protocol|VoIP]], video conferencing, streaming, and WebRTC-based communication.
