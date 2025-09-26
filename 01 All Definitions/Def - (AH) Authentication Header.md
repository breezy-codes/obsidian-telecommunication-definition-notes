---
aliases:
  - Authentication Header
  - AH
tags:
  - telecommunications/definitions/security-and-authentication
  - telecommunications/definitions/network-protocols
  - telecommunications/definitions/routing-multicast-gateway-protocols
  - telecommunications/OSI-model/layer3
---

**Authentication Header ([[Def - (AH) Authentication Header|AH]])** is an [[Def - (IPsec) Internet Protocol Security|IPSec]] protocol that provides **connectionless integrity**, **data origin authentication**, and **optional anti-replay protection** for [[Def - (IP) Internet Protocol|IP]] packets—but **does not offer encryption**. It is used to ensure that data has not been tampered with and that it comes from a verified source.

[[Def - (AH) Authentication Header|AH]] protects both the payload and portions of the [[Def - (IP) Internet Protocol|IP]] header by computing a **message authentication code (MAC)** over the packet using a shared key. However, some [[Def - (IP) Internet Protocol|IP]] header fields that can change in transit (e.g. TTL) are excluded from the hash.

[[Def - (AH) Authentication Header|AH]] supports:
- **Transport mode**: Adds the [[Def - (AH) Authentication Header|AH]] between the [[Def - (IP) Internet Protocol|IP]] header and the payload.
- **Tunnel mode**: Encapsulates the entire original packet within a new [[Def - (IP) Internet Protocol|IP]] header and includes the [[Def - (AH) Authentication Header|AH]].

[[Def - (AH) Authentication Header|AH]] header fields include:
- **Next Header**: Identifies the type of payload (e.g. [[Def - (TCP) Transmission Control Protocol|TCP]], [[Def - (UDP) User Datagram Protocol|UDP]]).
- **SPI (Security Parameter Index)**: Identifies the Security Association ([[Def - (SAs) Security Associations|SA]]).
- **Sequence Number**: Prevents replay attacks.
- **Authentication Data**: The MAC used to verify the packet’s authenticity.

[[Def - (AH) Authentication Header|AH]] is less commonly used in practice than [[Def - (ESP) Encapsulating Security Payload|ESP]] because it does not provide encryption and can interfere with [[Def - (NAT) Network Address Translation|NAT]], which modifies [[Def - (IP) Internet Protocol|IP]] headers (breaking the integrity check). [[Def - (ESP) Encapsulating Security Payload|ESP]] with authentication is usually preferred for end-to-end protection.
