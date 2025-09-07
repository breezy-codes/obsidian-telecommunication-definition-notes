---
aliases:
  - Voice over Internet Protocol
  - VoIP
tags:
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/wireless-technologies
  - telecommunications/OSI-model/layer5
  - telecommunications/OSI-model/layer7
---

**Voice over Internet Protocol ([[Def - (VoIP) Voice over Internet Protocol|VoIP]])** is a technology that enables **voice communication and multimedia sessions over [[Def - (IP) Internet Protocol|IP]] networks**, such as the internet or private [[Def - (LAN) Local Area Network|LAN]]s/[[Def - (WAN) Wide Area Network|WAN]]s. Instead of using circuit-switched telephone networks (like PSTN), [[Def - (VoIP) Voice over Internet Protocol|VoIP]] digitises voice, compresses it, and transmits it in **packets** using protocols like [[Def - (RTP) Real-time Transport Protocol|RTP]].

[[Def - (VoIP) Voice over Internet Protocol|VoIP]] replaces traditional telephony infrastructure with **IP-based communication systems**, offering flexibility, cost savings, and integration with other services.

Core components of [[Def - (VoIP) Voice over Internet Protocol|VoIP]]:
- **Signalling protocol**: Used to set up and tear down calls (e.g. [[Def - (SIP) Session Initiation Protocol|SIP]], H.323, or MGCP).
- **Media transport**: [[Def - (RTP) Real-time Transport Protocol|RTP]] carries audio and video streams in real-time.
- **Codecs**: Compress voice data (e.g. G.711, G.729, Opus) to reduce bandwidth while maintaining quality.
- **Gateways and PBXs**: Interface with the PSTN or manage internal [[Def - (VoIP) Voice over Internet Protocol|VoIP]] call routing.

[[Def - (VoIP) Voice over Internet Protocol|VoIP]] architectures:
- **Hosted VoIP**: Cloud-based PBX and call services.
- **On-premises VoIP**: Locally managed systems, often integrated with enterprise networks.
- **Peer-to-peer VoIP**: Direct device-to-device calling over [[Def - (IP) Internet Protocol|IP]].

Benefits:
- **Lower cost**: Especially for long-distance and international calls.
- **Mobility**: Use the same number across devices and locations.
- **Advanced features**: Voicemail to email, call recording, video conferencing, presence awareness.

Challenges:
- **QoS-sensitive**: Dependent on network quality; requires low latency, jitter, and packet loss.
- **Security**: [[Def - (VoIP) Voice over Internet Protocol|VoIP]] systems must be protected against SIP attacks, spoofing, and eavesdropping (e.g. via [[Def - (TLS) Transport Layer Security|TLS]] and SRTP).
- **Emergency services**: [[Def - (VoIP) Voice over Internet Protocol|VoIP]] may lack reliable location tracking for 000/911 calls without additional configuration.

[[Def - (VoIP) Voice over Internet Protocol|VoIP]] has become the foundation of modern voice communications, used in personal apps (like Zoom, Skype, WhatsApp) and enterprise UC systems.
