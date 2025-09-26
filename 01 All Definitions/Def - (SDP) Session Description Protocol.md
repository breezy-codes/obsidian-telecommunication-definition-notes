---
aliases:
  - Session Description Protocol
  - SDP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer6
  - telecommunications/OSI-model/layer7
---

**Session Description Protocol ([[Def - (SDP) Session Description Protocol|SDP]])** is a **text-based format** used to describe **multimedia communication sessions** for the purposes of session announcement, invitation, and parameter negotiation. It is defined in **RFC 4566** and is commonly used with protocols like **[[Def - (SIP) Session Initiation Protocol|SIP]]** and **RTSP** in VoIP and video conferencing systems.

[[Def - (SDP) Session Description Protocol|SDP]] is not a transport protocol—it carries **session metadata** rather than media—and is used to communicate:
- **Session details**: Title, originator, session ID.
- **Media information**: Media type (audio, video), codec, format.
- **Transport details**: [[Def - (IP) Internet Protocol|IP]] address, port, protocol (e.g. [[Def - (RTP) Real-time Transport Protocol|RTP]]/[[Def - (UDP) User Datagram Protocol|UDP]]).
- **Bandwidth and timing**: How long the session lasts, whether it's recurring.

An example [[Def - (SDP) Session Description Protocol|SDP]] message embedded in a [[Def - (SIP) Session Initiation Protocol|SIP]] INVITE might look like:

```
v=0
o=alice 2890844526 2890842807 IN IP4 host.example.com
s=Voice Call
c=IN IP4 192.0.2.4
t=0 0
m=audio 49170 RTP/AVP 0 96
a=rtpmap:0 PCMU/8000
a=rtpmap:96 opus/48000
```

[[Def - (SDP) Session Description Protocol|SDP]] is critical for **capability negotiation**, allowing endpoints to agree on compatible media formats and session parameters before initiating real-time communication.
