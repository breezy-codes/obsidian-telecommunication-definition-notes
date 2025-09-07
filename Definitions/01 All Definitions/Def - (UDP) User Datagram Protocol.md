---
aliases:
  - User Datagram Protocol
  - UDP
tags:
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/application-layer-protocols
  - telecommunications/definitions/security-and-authentication
  - telecommunications/OSI-model/layer4
---

**User Datagram Protocol ([[Def - (UDP) User Datagram Protocol|UDP]])** is a connectionless, lightweight transport layer protocol defined by the [[Def - (IETF) Internet Engineering Task Force|IETF]], used for transmitting datagrams with minimal overhead. It provides **no guarantee of delivery**, **ordering**, or **reliability**, making it suitable for applications that prioritise speed over reliability.

[[Def - (UDP) User Datagram Protocol|UDP]] is built on top of [[Def - (IP) Internet Protocol|IP]] and simply adds a short header to each message containing source and destination ports, length, and a checksum. Because there’s no need to establish or maintain a connection, it allows for low-latency communication and high throughput.

Common use cases for [[Def - (UDP) User Datagram Protocol|UDP]]:
- **Real-time applications**: Such as [[Def - (VoIP) Voice over Internet Protocol|VoIP]], video streaming, and online gaming, where dropped packets are preferable to delayed delivery.
- **[[Def - (DNS) Domain Name System|DNS]] queries**: Which are small and can be resent if lost.
- **IoT applications**: Where overhead and complexity need to be minimised.

While [[Def - (UDP) User Datagram Protocol|UDP]] itself lacks features like retransmission and flow control, these can be implemented at the application level if needed. Its simplicity makes it highly efficient but unsuitable for data that must arrive reliably and in order.
