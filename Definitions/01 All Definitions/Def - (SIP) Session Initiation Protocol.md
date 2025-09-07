---
aliases:
  - Session Initiation Protocol
  - SIP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer7
---

**Session Initiation Protocol ([[Def - (SIP) Session Initiation Protocol|SIP]])** is an **application-layer signalling protocol** used to **establish, manage, and terminate real-time sessions** involving voice, video, messaging, and other media. It is widely used in **VoIP (Voice over IP)** and **Unified Communications** systems.

Defined in **RFC 3261**, [[Def - (SIP) Session Initiation Protocol|SIP]] initiates sessions between endpoints called **User Agents** (e.g. [[Def - (IP) Internet Protocol|IP]] phones, softphones, or gateways).

[[Def - (SIP) Session Initiation Protocol|SIP]] operates over:
- **[[Def - (UDP) User Datagram Protocol|UDP]] or [[Def - (TCP) Transmission Control Protocol|TCP]] port 5060**: Standard [[Def - (SIP) Session Initiation Protocol|SIP]] (plaintext).
- **[[Def - (TCP) Transmission Control Protocol|TCP]] port 5061**: [[Def - (SIP) Session Initiation Protocol|SIP]] over [[Def - (TLS) Transport Layer Security|TLS]] (encrypted).

Key features of [[Def - (SIP) Session Initiation Protocol|SIP]]:
- **Session establishment**: Handles call setup and teardown.
- **User location**: Resolves a user’s address and current [[Def - (IP) Internet Protocol|IP]] via a **[[Def - (SIP) Session Initiation Protocol|SIP]] registrar**.
- **Presence and mobility**: Allows devices to move or change [[Def - (IP) Internet Protocol|IP]]s while remaining reachable.
- **Supports multiple media types**: Audio, video, instant messaging.

[[Def - (SIP) Session Initiation Protocol|SIP]] works in conjunction with other protocols:
- **[[Def - (SDP) Session Description Protocol|SDP]] (Session Description Protocol)**: Describes media capabilities and negotiation.
- **[[Def - (RTP) Real-time Transport Protocol|RTP]] (Real-time Transport Protocol)**: Used to carry voice and video payloads after [[Def - (SIP) Session Initiation Protocol|SIP]] negotiates the session.

[[Def - (SIP) Session Initiation Protocol|SIP]] is central to modern **[[Def - (IP) Internet Protocol|IP]] telephony**, **video conferencing**, and **collaboration tools**, offering flexibility, scalability, and integration across networks and platforms.
