---
aliases:
  - Transmission Control Protocol
  - TCP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer4
---

**Transmission Control Protocol ([[Def - (TCP) Transmission Control Protocol|TCP]])** is a connection-oriented, reliable transport layer protocol used in most internet applications. It provides reliable, in-order delivery of data between two endpoints by using acknowledgements, retransmissions, and flow control mechanisms.

Key features of [[Def - (TCP) Transmission Control Protocol|TCP]]:
- **Connection setup**: Uses a three-way handshake to establish a session.
- **Reliable delivery**: Implements [[Def - (ARQ) Automatic Repeat Request|ARQ]] with sequence numbers and ACKs to detect and recover from lost or out-of-order packets.
- **Flow control**: Uses a sliding window to manage data flow based on receiver capacity.
- **Congestion control**: Adjusts transmission rate in response to network congestion (e.g. using algorithms like TCP Reno or Cubic).

[[Def - (TCP) Transmission Control Protocol|TCP]] is used in applications that require guaranteed delivery, such as:
- **Web browsing (HTTP/HTTPS)**
- **Email ([[Def - (SMTP) Simple Mail Transfer Protocol|SMTP]], [[Def - (IMAP) Internet Message Access Protocol|IMAP]])**
- **File transfer ([[Def - (FTP) File Transfer Protocol|FTP]])**

Because of its robustness and built-in error correction, [[Def - (TCP) Transmission Control Protocol|TCP]] is heavier and slower than [[Def - (UDP) User Datagram Protocol|UDP]], but it ensures data arrives complete and in order. It is essential for reliability in most internet communications.
